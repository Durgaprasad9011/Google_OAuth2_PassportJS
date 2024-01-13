# Google OAuth2 Authentication using PassportJS, NodeJS & Express

## Getting Started

To run this application locally, follow these steps:

```bash
$ git clone https://github.com/Durgaprasad9011/Google_OAuth2_PassportJS.git
$ cd Google_OAuth2_PassportJS
$ code .
```
The files will be opened in VS Code

## Note

This application requires OAuth 2.0 credentials from Google. To obtain these credentials, follow the steps below:

1. Go to the [Google API Console](https://console.cloud.google.com/apis/dashboard?project=notify-app-c3242).
2. Navigate to "Credentials" and click on "Add Credentials," then select "OAuth client ID."
3. Set the application name according to your preference and configure the redirect URI of the OAuth client to 'http://localhost:5000/google/callback'.

Now you're ready to run the app, start the server:

```bash
$ npm start
```
And head over to https://localhost:5000 in your browser.
