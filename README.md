# PhoneBuzz Phase 1
Coding challenge

### To Run the Application:
1. Start server by running:

   ```
   $ sh bin/startup.sh.
   ```
1. Expose application via ngrok
   ```bash
   $ ngrok http 8080
   ```

1. Use the following link as the request URL for your twilio number.
   ```
   http://<your-ngrok-subdomain>.ngrok.io/twilio/phonebuzz
   ```

1. Call your twilio number and play Phone Buzz!

Note: You can find your ngrok URL at
   ```
   localhost:4040/status
   ```
