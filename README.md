# Nodemailer-Contact
A node and express application to implement Nodemailer module for contacting via email. The sender address is an ethereal generated email address, so if you want to use your own personal address then implement it with OAuth2 or make sure your code isn't shared to sidestep security vulnerabilities.

## Requirements
Node (Version>8.x.x) [Download link: https://nodejs.org/en/download]

## How to start
1. Install all the dependencies and packages using <code>npm install</code> in the terminal.
2. Run the app using <code>npm start</code> 
3. Browse to https://localhost:3000 

## Configurations for Email Services

![Screenshot (67)](https://user-images.githubusercontent.com/31178132/61475493-8a377180-a9a8-11e9-95bb-b262d497f271.png)

- Open app.js file and edit SMTP transporter object

- Change the host to smtp.gmail.com or whatever mail services you use.
( If using, OAuth2 or any other security autherisation, change the port to 465, secure to true and remove tls )

- Edit user and pass in auth with your credentials

- Edit from and to in mailOptions with the sending and receiving addresses and the rest according to your needs.

- Save all the changes and reload the server to get going!

> <b>Warning: </b>Don't share your code or push it on GitHub if you are using your personal mail credentials as a sender in SMPT transportation auth or else it'll be visible to all. <br>
> Use OAuth2 or any other security autherisation if you want to use personal email address.

![Screenshot (64)](https://user-images.githubusercontent.com/31178132/61473765-bfda5b80-a9a4-11e9-864a-46d1327ce659.png)
![Screenshot (65)](https://user-images.githubusercontent.com/31178132/61473769-c23cb580-a9a4-11e9-9f59-0d090fe7ae5a.png)
![Screenshot (66)](https://user-images.githubusercontent.com/31178132/61473774-c4067900-a9a4-11e9-920d-62ce5aa026b0.png)
