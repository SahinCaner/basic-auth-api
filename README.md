# basic-auth-api

node.js authentication API for any type of mobile and web project.

## User wants to sign up

1) User enters password and email
2) User ID and App's secret code from config.js file creates JSON Web Token
3) With given token, user can access to permission only URLs


## User wants to sign in

1) User enters password and email
2) If user has a correct password and token, user can access to restricted area

### Don't forget to add config.js file to root directory.

Sample config.js
module.exports = {
    secret: 'yourSecretCode'
}
