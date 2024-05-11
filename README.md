# TikTok Clone Project

This project is a clone of the popular TikTok app. It consists of two main components: a client-side web application (`tiktok-client`) and a server-side API (`tiktok-server`).

The main goal of the project is to learn and practice Web Development skills that require knowledge of different technologies such as HTML, CSS, Javascript, ReactJs, NodeJs, MongoDB, etc.

This project is still in development and more features will be implemented in the future, as well as error fixing and performance improvement.

## What is there in Tiktok-clone?

There are currently a few things you can do on this web application project:

1. Sign up, login with your account.
2. Reset your password with a reset token sent through email (currently NOT available since i'm using Mailtrap.io instead of a paid service for email sending).
3. Render a list of random videos or of the users you are following.
4. Like a video.
5. Comment on a video.
6. Save a video to favorite list.
7. Follow an user.
8. Upload a video and select a frame of it as cover (thumbnail).
9. Chang the app language.
10. Toggle betwween dark mode and light mode.

## Soon to be implemented

1. Notification.
2. Messaging.
3. Login with Facebook, Google, etc with Firebase authentication.
4. Users' stories.
5. Server-side media optimization.
6. Billing and payment.
7. Content based on geopositioning.
8. ... and many more.

## Client deployment

The client-side web app (`tiktok-client`) is deployed on Netlify. You can access the deployed website at https://klong-tiktok-clone.netlify.app.

## Server deployment

The server-side API (`tiktok-server`) is deployed on Render.com. You can access the deployed API at https://tiktok-server-cr45.onrender.com. <br/>
It might take a minute for the server to start up on your first access.

## Technologies used

- React.js for the client-side application
- Node.js and Express.js for the server-side API
- MongoDB for database storage
- Firebase Storage for media storage
- Netlify for client deployment
- Render for server deployment

## Installation

To run the TikTok client locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/KhanhLong611/tiktok-clone.git

   ```
2. Navigate to the client directory:

   ```bash
   cd tiktok-clone/client

   ```

3. Install dependencies:
   ```bash
   npm install

   ```
4. Start the development server:
   ```bash
   npm start
   ```

## License

This project is licensed under the MIT License.
