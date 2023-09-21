A Simple  Spring boot Reactive OTP generation service application

Steps : 
1. Go to twilio.com and sign-up [Trail and Free]
2. Copy Sid, Auth Token and Temporary mobile number generated
3. Add these in application properties file
4. Start the application 
API
http://localhost:8080/router/sendOTP  [POST]
{
"phoneNumber":"+919010058555",
"userName":"rajesh"
}

http://localhost:8080/router/validateOTP [POST]
{
"oneTimePassword":"676539",
"userName":"rajesh"
}