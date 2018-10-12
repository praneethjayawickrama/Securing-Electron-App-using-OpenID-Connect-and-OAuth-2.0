# Securing Electron Applicartion using OpenID Connect and OAuth 2.0



The flow of the application will be the following:

Your users will start the Electron application.
As they were not signed in before, you Electron app will show them a login screen (a page provided by the authorization server).
After authenticating, the authorization server will provide your Electron app a code.
The Electron app will issue a request to a token endpoint to exchange this code for an access token and an id token.
After getting back these tokens, the Electron app will show a secured route with where users will be able to click a button to fetch the static message from the /private endpoint on the API.
Although simple, this workflow shows the whole picture of how you will have to integrate and secure your backend APIs and Electron apps while using OAuth 2.0 and OpenID Connect. The following screenshot shows what the app will look like when ready.


make sure you are on the frontend directory
# npm i keytar
In the next section, you will see keytar in action.


as you have defined the start script before
# npm start




