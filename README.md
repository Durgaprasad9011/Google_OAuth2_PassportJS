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





# Output


### 1. Initial Setup

- Open your browser and navigate to [https://localhost:5000](https://localhost:5000)
- The homepage will be displayed.
- Click on "Click to authenticate with Google."

![Home Page](https://drive.google.com/uc?id=1fq7I0aZZBVmvMBzwe0cfx0atWomyaJd9)

### 2. Google Authentication

- You will be redirected to the "Sign in with Google" page.
- Choose any of your Google email accounts.

![Google Authentication](https://drive.google.com/uc?id=17MIn9qzY-SndOwiOTJ_biSngNV6dbYAt)

### 3. Session Information

- After authentication, you will be redirected to another page.
- This page displays information, as shown in the figure, and generates a session ID.

![Session Information](https://drive.google.com/uc?id=1kEiK-SlUkaAwwUdvsCrYSkcvqfMwAVYw)

### 4. Logout

- Pressing the "Logout" button will redirect you to the logout page.

![Logout](https://drive.google.com/uc?id=1NWRDftVOFGG5y44zVrDuNq5_TVbnqf29)

### Note

- Sessions are managed. If you type [http://localhost:5000/return](http://localhost:5000/return) directly in your browser, without sign in initially it will show "Unauthorized."

![Unauthorized](https://drive.google.com/uc?id=1EyM27c84w0ANfySkm8xoWnhiBSvbmN1k)


