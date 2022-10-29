# Email-OTP-System

Setup instructions:

  a. Install the folder using git or download the zipped folder.
  b. Unzip the project folder.
  c. Open the project folder in Code Editor like Visual Studio Code.
  d. Open the terminal.
  e. Run the command npm i.
  f. After installing dependencies, exit the terminal.
  g. Open the terminal and run the command "npm run dev".
  h. Now, go the browser and write "localhost:5000" in the address bar. Hit Enter.
  You can see the application.
  
Dependencies:

  1. node
  2. npm

How to try?

1. After running the server with "npm run dev" anf opening "localhost:5000" in the browser, click on "Login" Button.
2. Enter any email in the input field and click on 'Request OTP' button.
3. Screen with the message "OTP Generated!! Go Copy From Terminal" will be displayed.
4. Go to code editor's terminal and copy the OTP.
5. Now click the "Click here to verify the OTP" button.
6. Enter the copied in otp input field.
7. Perform step 4-6 in 30 seconds, else the OTP will get expired.
8. If the OTP expires, or doesn't match with the generated OTP, change the email(if required) and click on 'Request Another OTP' button. 
9. Repeat steps 3-7.
10. When the OTP is verified, a screen with the message "Login Successful Hurray!!!" will be displayed.
11. Click on 'Back to Home Page' button.
12. Entered email with Logout button will be displayed.
13. Close the screen and reopen it after sometime, you will be logged in already with your email.
14. Click on Logout button to log out.
