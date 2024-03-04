# Blog Website Project

Welcome to the Blog Website project! This project is built using Node.js and EJS for creating a dynamic and interactive blog website.

## Features

- **User Authentication**: Implement user authentication to allow users to sign up, log in, and manage their profiles.
- **Create and Edit Posts**: Users can create new blog posts and edit existing ones.
- **Comments**: Enable users to leave comments on blog posts.
- **Categories**: Organize posts into different categories for easy navigation.
- **Search**: Implement a search functionality to allow users to search for posts based on keywords.
- **Responsive Design**: Ensure the website is responsive and accessible on various devices.

## Technologies Used

- **Node.js**: A JavaScript runtime for building server-side applications.
- **Express.js**: A web application framework for Node.js used to handle routes and middleware.
- **EJS (Embedded JavaScript)**: A simple templating language used to generate HTML markup with plain JavaScript.
- **MongoDB**: A NoSQL database used to store user data, blog posts, comments, and other information.
- **Mongoose**: An Object Data Modeling (ODM) library for MongoDB and Node.js.
- **Passport.js**: Authentication middleware for Node.js used to authenticate users.
- **Bootstrap**: A front-end framework for developing responsive and mobile-first websites.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/ayushsinha-13/Tales.git
    ```

2. Install dependencies:

    ```bash
    cd Tales
    npm install
    ```

3. Set up environment variables:

    Create a `.env` file in the root directory and add the following variables:

    ```plaintext
    MONGODB_URI=<your-mongodb-uri>
    ```

    Replace `<your-mongodb-uri>` with your MongoDB connection URI.

4. Start the server:

    ```bash
    npm start
    ```

    The server will start running at `http://localhost:3000`.

## Contributing

Contributions are welcome! If you'd like to contribute to the project, please fork the repository and create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
