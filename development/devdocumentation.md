# This document is for the notes and information related to the development of Openlinks. This is all Public.

## Development Enviroment

Command for version specific install of dependencies- This may not be needed because the modules are already within the app files- check to make sure

npm install auth0-js@9.13.4 auth0-lock@11.25.1 express@4.17.1 express-jwt@5.3.1 express-jwt-authz@1.0.0 jwks-rsa@1.3.0 npm-run-all@4.1.5 react-router-dom@5.2.0

After that then you need to set-up your routes within Auth0 to make sure the front-end works as intended with a dummy auth0 Login account- 

## Configure Auth0

- Sign up for Auth0

- Create Auth0 Application to point to our React Front-End. You do that using the Auth0 Interface. 

  1.  Click the button that says "new applicaiton".
  2.  Choose single-page app for your configuration
  3.  Within the application uri section, Set the Login URI to (x...........) and set the "Allowed Callback URL" too (x.........).

maybe add this all within its own document... 

- Configure .env values to match your Auth0 Account

When you create your Auth0 Tenant configuration, think of the tenant like a development enviorment. It must be unique, so pick your own name- 

Then you need to create a new Auth0 App. Choose single page app and then go straight to settings. 

## Currently Working On- 

- IPNS updates
- UI updates

## IPNS Notes

Stop wasting time and just use W3.Names. Coming up with your own configuration will take too much time Noryev... Focus on that later when there is time for that.... 

http://web3.storage.ipns.localhost:8080/docs/how-tos/w3name/
