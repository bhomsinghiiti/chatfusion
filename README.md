# ChatFusion - A Real-Time Chat Application

ChatFusion is a real-time chat application developed using the MERN stack (MongoDB, Express.js, React.js, Node.js) and seamlessly integrated with Socket.IO for instant real-time messaging. This project offers a user-friendly and responsive platform for users to engage in real-time conversations with one another.

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)

## Features

- **Real-Time Messaging:** Engage in real-time conversations with other users, with messages appearing instantly on the screen.
- **User Authentication:** Ensured privacy and access control through secure user authentication using JWT (JSON Web Tokens).
- **User Profiles:** Users can create and manage their profiles, including profile pictures and personal information.
- **Private and Group Chats:** Initiate private conversations or create group chats with multiple participants.
- **Message History:** Access your chat history and scroll back through previous messages.
- **Notifications:** Receive notifications for new messages, even when the app is running in the background.
- **Responsive Design:** The application offers a fully responsive experience, delivering seamless usage on both desktop and mobile devices.

## Demo

You can explore a live demo of ChatFusion [here](https://chatfusion-demo.com/). Feel free to dive into the app and start real-time chatting with others!

## Prerequisites

Before you get started, please ensure you meet the following requirements:

- **Node.js:** Make sure you have Node.js installed on your system. You can download it from [nodejs.org](https://nodejs.org/).
- **MongoDB:** You'll require a MongoDB database. You can create a free account and set up a database on [MongoDB Atlas](https://www.mongodb.com/cloud/atlas).
- **Socket.IO:** Familiarize yourself with Socket.IO for real-time messaging. For more details, refer to the [Socket.IO documentation](https://socket.io/docs/v4/).

## Installation

Follow these steps to set up and run ChatFusion on your local machine:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/chatfusion.git
   ```

2. Navigate to the project directory:

   ```bash
   cd chatfusion
   ```

3. Install server dependencies:

   ```bash
   npm install
   ```

4. Install client dependencies:

   ```bash
   cd client
   npm install
   ```

5. Create a `.env` file in the project root and set the following environment variables:

   ```
   NODE_ENV=development
   PORT=5000
   MONGODB_URI=your-mongodb-uri
   SECRET_KEY=your-secret-key
   ```

   Replace `your-mongodb-uri` with your MongoDB URI and `your-secret-key` with a secret key for JWT.

6. Start the server:

   ```bash
   npm run server
   ```

7. In another terminal, navigate to the `client` directory and launch the client:

   ```bash
   cd client
   npm start
   ```

8. Access the application in your web browser at `http://localhost:3000`.

## Usage

- Register and log in to your account.
- Explore chat rooms or create new private or group chats.
- Commence real-time messaging with your contacts.
- Personalize your profile settings.
- Experience seamless communication with friends and colleagues!

## Technologies Used

- **Frontend:**
  - React.js
  - Socket.IO-client
  - Axios
  - React-Emoji
- **Backend:**
  - Node.js
  - Express.js
  - MongoDB
  - Mongoose
  - Socket.IO
  - JWT (JSON Web Tokens)
- **Deployment:**
  - Render (server)
- **Version Control:**
  - Git
  - GitHub

## Contributing

We heartily welcome contributions from the community. If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Implement your changes and thoroughly test them.
4. Propose a pull request to the main repository.

---

Thank you for choosing ChatFusion! We trust that you'll derive as much enjoyment from using this real-time chat application as we did creating it. Should you encounter any issues or have suggestions for enhancements, please don't hesitate to open an issue on our GitHub repository. Happy chatting!
