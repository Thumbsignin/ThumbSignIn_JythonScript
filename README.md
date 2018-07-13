# ThumbSignIn_JythonScript

This is a person authentication module for oxAuth that enables [ThumbSignIn Authentication](https://thumbsignin.com/) for user authentication.

The module has a few properties:

1) ts_host - It's mandatory property. The URL of the ThumbSignIn API server.
Value: `https://api.thumbsignin.com`


2) ts_apiKey - It's mandatory property. These keys are required for ThumbSignIn authentication puropose.
  

3) ts_apiSecret - It's mandatory property. These keys are required for ThumbSignIn authentication puropose.


The above ts_apiKey and ts_apiSecret key can be generated by following the below steps.
	
1. Sign Up(https://thumbsignin.com/) for ThumbSignIn account 
2. Type your email id and click try it button
3. Scan the QR code displayed in your screen using thumbsignin mobile app.
4. After successful registration, you will be redirecting to the home page.
5. Then click My apps in the Menu
6. Copy the Application ID  which is ts_apikey
7. Copy the  Secret Key which is ts_apiSecret
