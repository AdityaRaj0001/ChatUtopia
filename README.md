# ChatUtopia

I am Beside you's (IBY) Assignment submission by ADITYA RAJ, 2021CEB1007, IIT ROPAR, CIVIL DEPT. 

This is a chat application built with NEXT.js for the frontend and Express, Node.js, and MongoDB for the backend. The application allows users to engage in real-time chat with others using SOCKET.IO

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js: Make sure you have Node.js installed. You can download it [here](https://nodejs.org/).
- Git: Make sure you have Git installed. You can download it [here](https://git-scm.com/).
- MongoDB Atlas Account: You must have a MongoDB Atlas account to set up the database. You can sign up for a free account at [MongoDB Atlas](https://www.mongodb.com/cloud/atlas).

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/AdityaRaj0001/ChatUtopia.git
   ```

2. Frontend setup:

   ```bash
   cd frontend
   npm install
   npm run dev
   ```

   This will start the frontend on [http://localhost:3000](http://localhost:3000).

3. Backend setup:

   - Create a `.env` file in the `backend` directory.

     ```
     MONGO_URI=your-mongodb-uri
     ```

     Replace `your-mongodb-uri` with the URI for your MongoDB Atlas database.

   - Install backend dependencies and start the server:

     ```bash
     cd backend
     npm install
     node index.js
     ```

   The backend will be running on [http://localhost:3001](http://localhost:3001).

## Usage

- Access the chat application by opening your web browser and navigating to [http://localhost:3000](http://localhost:3000).
- Sign up or log in to start chatting with other users.
- Explore the features and enjoy real-time messaging with your friends.

## Contributing

We welcome contributions to improve this project. To contribute, follow these steps:

1. Fork the repository on GitHub.
2. Create a new branch with a descriptive name:
   ```bash
   git checkout -b feature/your-feature
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m 'Add your feature'
   ```
4. Push your changes to your fork on GitHub:
   ```bash
   git push origin feature/your-feature
   ```
5. Open a pull request to the main repository.


## License

Certainly, here's an updated README with instructions for creating a `.env` file and specifying the need for a MongoDB Atlas database account:

```markdown
# Chat Application

This is a chat application built with NEXT.js for the frontend and Express, Node.js, and MongoDB for the backend. The application allows users to engage in real-time chat with others.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js: Make sure you have Node.js installed. You can download it [here](https://nodejs.org/).
- Git: Make sure you have Git installed. You can download it [here](https://git-scm.com/).
- MongoDB Atlas Account: You must have a MongoDB Atlas account to set up the database. You can sign up for a free account at [MongoDB Atlas](https://www.mongodb.com/cloud/atlas).

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/your-repo.git
   ```

2. Frontend setup:

   ```bash
   cd frontend
   npm install
   npm run dev
   ```

   This will start the frontend on [http://localhost:3000](http://localhost:3000).

3. Backend setup:

   - Create a `.env` file in the `backend` directory.

     ```
     MONGO_URI=your-mongodb-uri
     ```

     Replace `your-mongodb-uri` with the URI for your MongoDB Atlas database.

   - Install backend dependencies and start the server:

     ```bash
     cd backend
     npm install
     node index.js
     ```

     The backend will be running on [http://localhost:your-backend-port](http://localhost:your-backend-port).

## Usage

- Access the chat application by opening your web browser and navigating to [http://localhost:3000](http://localhost:3000).
- Sign up or log in to start chatting with other users.
- Explore the features and enjoy real-time messaging with your friends.

## Contributing

We welcome contributions to improve this project. To contribute, follow these steps:

1. Fork the repository on GitHub.
2. Create a new branch with a descriptive name:
   ```bash
   git checkout -b feature/your-feature
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m 'Add your feature'
   ```
4. Push your changes to your fork on GitHub:
   ```bash
   git push origin feature/your-feature
   ```
5. Open a pull request to the main repository.

Please review our [Contributing Guidelines](CONTRIBUTING.md) for more details.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

We hope you find this README helpful. Enjoy using your chat application! If you have any questions or encounter issues, please feel free to open an issue or contact us.

Don't forget to replace "yourusername" and "your-repo" with your actual GitHub username and repository name.
```

In the updated instructions, users are required to create a `.env` file in the `backend` directory and add their MongoDB Atlas URI to it. This ensures that users have a properly configured database connection. Additionally, I've mentioned the need for a MongoDB Atlas account in the prerequisites section.

This project is licensed under the MIT License

---
