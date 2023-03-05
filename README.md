# user auth signup (express and mysql)

Building an APIs where users can sign up, have a validation, and able to send notification email to registered email after user sign up successfully.  

## Utilization 

### Install dependencies

bash 
npm install


### Run on http://localhost:5000/users/

for production
bash 
npm run start

for developer
bash 
npm run dev


### Add information about public API

Rename *sample.env* to *.env* and edit the values

For the public APIs mysql databases are 
-DB_NAME="YOUR_DATABASE_NAME"
-DB_USER="YOUR_USER_ROOT_NAME"
-DB_PASS="YOUR_PASSWORD"
-DB_HOST="localhost"
-DB_DIAL="mysql" 

For the public APIs smtp gmail are 
-HOST_EMAIL="YOUR_HOST_GMAIL"
-PORT_EMAIL=YOUR_PORT(integer)
-SECU_EMAIL=YOUR_SECURITY(boolean)
-USER_EMAIL="YOUR_EMAIL"
-PASS_EMAIL="YOUR_PASSWORD"

### Additional

- Add new routes as per your requirement.
- Modify rate limiting and caching to desired values.
