# Video Call Application

![Video Call](https://img.icons8.com/ios-filled/50/000000/video-call.png)

A video call application built with React.js using WebRTC for real-time communication and Node.js for the backend.

## Features

- 📹 Real-time video and audio communication
- 👥 Peer-to-peer connection using WebRTC
- 🔒 Secure connections with WebRTC protocols
- 🌐 Easy to use with a clean user interface

## Demo

![Demo](https://img.icons8.com/color/50/000000/video-conference.png)

You can try out the live demo [here](#) (replace with actual demo link if available).

## Getting Started

Follow these instructions to set up and run the project on your local machine.

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. **Clone the repository**

    ```sh
    git clone https://github.com/kathan-shah1893/video-call-react.git
    cd video-call-react
    ```

2. **Install dependencies for both client and server**

    ```sh
    # For client
    cd client
    npm install
    # or
    yarn install

    # For server
    cd ../server
    npm install
    # or
    yarn install
    ```

### Running the Application

1. **Start the backend server**

    ```sh
    cd server
    npm start
    # or
    yarn start
    ```

2. **Start the React frontend**

    ```sh
    cd client
    npm start
    # or
    yarn start
    ```

The application should now be running on `http://localhost:3000`.

## Usage

1. Open the application in your browser.
2. Allow the browser to access your camera and microphone.
3. Share the room link with a friend to start a video call.

## Project Structure

```sh
video-call-react/
│
├── client/                # React frontend
│   ├── public/
│   └── src/
│       ├── components/
│       ├── hooks/
│       ├── utils/
│       ├── App.js
│       ├── index.js
│       └── ...
│
├── server/                # Node.js backend
│   ├── controllers/
│   ├── routes/
│   ├── services/
│   ├── index.js
│   └── ...
│
└── README.md
```

Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

Fork the Project
Create your Feature Branch (git checkout -b feature/AmazingFeature)
Commit your Changes (git commit -m 'Add some AmazingFeature')
Push to the Branch (git push origin feature/AmazingFeature)
Open a Pull Request
License
Distributed under the MIT License. See LICENSE for more information.

Contact

Kathan Shah - @kathan-shah1893

Project Link: https://github.com/kathan-shah1893/video-call-react

Acknowledgements
WebRTC
React.js
Node.js
Icons8 for icons