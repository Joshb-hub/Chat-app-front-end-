
# Chat App Front-End

## Overview

This repository contains the front-end code for a real-time chat application. The application allows users to:

- Sign up and log in securely.
- Engage in real-time messaging with other users.
- Receive notifications for new messages.

## Technologies Used

- **React.js**: JavaScript library for building user interfaces.
- **Redux**: State management for React applications.
- **Socket.io-client**: Real-time, bidirectional communication between web clients and servers.
- **Axios**: Promise-based HTTP client for making API requests.
- **Tailwind CSS**: Utility-first CSS framework for styling.

## Features

- **User Authentication**: Secure sign-up and login functionality.
- **Real-Time Messaging**: Instant communication between users using Socket.io.
- **Responsive Design**: Optimized for various screen sizes and devices.
- **State Management**: Efficient handling of application state with Redux.

## Getting Started

### Prerequisites

- **Node.js**: Ensure you have Node.js installed. [Download Node.js](https://nodejs.org/)
- **npm or yarn**: Package managers for JavaScript. npm comes with Node.js; alternatively, you can use yarn.

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Joshb-hub/Chat-app-front-end.git
   cd Chat-app-front-end
   ```

2. **Install dependencies**:

   Using npm:

   ```bash
   npm install
   ```

   Or using yarn:

   ```bash
   yarn install
   ```

3. **Set up environment variables**:

   Create a `.env` file in the root directory and add the following:

   ```env
   REACT_APP_API_URL=your_backend_api_url
   ```

   Replace `your_backend_api_url` with the URL of your back-end API.

### Running the Application

To start the development server:

Using npm:

```bash
npm start
```

Or using yarn:

```bash
yarn start
```

The application will be accessible at `http://localhost:3000`.

## Deployment

To build the application for production:

Using npm:

```bash
npm run build
```

Or using yarn:

```bash
yarn build
```

The optimized and minified files will be in the `build` directory, ready for deployment.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch:

   ```bash
   git checkout -b feature/your-feature-name
   ```

3. Commit your changes:

   ```bash
   git commit -m 'Add your feature'
   ```

4. Push to the branch:

   ```bash
   git push origin feature/your-feature-name
   ```

5. Open a pull request detailing your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Acknowledgements

- [React.js](https://reactjs.org/)
- [Redux](https://redux.js.org/)
- [Socket.io](https://socket.io/)
- [Axios](https://axios-http.com/)
- [Tailwind CSS](https://tailwindcss.com/)

