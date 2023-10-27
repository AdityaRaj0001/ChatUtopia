# ChatUtopia

I am Beside you's (IBY) Assignment submission by ADITYA RAJ, 2021CEB1007, IIT ROPAR, CIVIL DEPT.

[Deployment Link](https://chat-app-for-testing.vercel.app/)

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
- Click on a user from the list of "Users" to send them to DM list, then further click on your DM's and start a real time conversation!
 ![image](https://github.com/AdityaRaj0001/ChatUtopia/assets/92699283/be7558ec-a9b1-46f5-8182-52bc29663818)
 ![image](https://github.com/AdityaRaj0001/ChatUtopia/assets/92699283/9d2a15fd-62e4-47f5-ac07-94f2ebc8c6a6)
- Click on the "Plus" icon and type the name of the group in the INPUT box, also select the members from the available list of "users" and hit "OK" to create a chat with multiple users in realtime!
 ![image](https://github.com/AdityaRaj0001/ChatUtopia/assets/92699283/038c8c9a-c2e5-4d78-a612-a75422acc7ca)




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

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

This project is licensed under the MIT License

---
