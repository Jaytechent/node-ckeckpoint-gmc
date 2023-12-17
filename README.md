## Node JS checkpoint

- I installed Node.js

# Task 1

- I created a package.json file with "npm init --y"
- Then created the hello-world.js file, and filled it with the code
  `console.log("HELLO WORLD") `
- Then logged it to the console with
  `node hello-world`

# Task 2

- Create a file server.js
- Write a program in the file to create a server on port 3000.
- Then Respond with <h1>Hello Node!!!!</h1>\n when someone reaches http://localhost:3000.
- Then logged it to the console with
  `node server` to start up the server

# Task 3

- Create a file fileSystem.js
- Then required the fs module in the fileSystem.js
- create a file with `fs.writeFileSync('welcome.txt', 'Hello Node');`
- create a new file called hello.txt and input some data there
- Read that data with a readFileSync and nput the data in the console

# Task 4

- Create a file named password-generator.js
- I install the password generator package with `npm i generate-password`
- require generate password in the file
- then generate the password with the generate method
- console log what the password was

# Task 5

- Create a file named email-sender.js
- install the install node mailer package with `npm install nodemailer`
- require nodemailer in the file
- I Set up the transporter with the mail service I wanna use and the authorizing details of my email and password
- I set up the email contents with the from and to who, with the email head and email text
- I send the email using `transporter.sendMail()` method console logging any error and the response gotten if successful
