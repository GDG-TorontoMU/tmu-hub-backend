# TMU Hub Backend - Node.js

TMU Hub is an innovative open-source platform designed to enhance student engagement at Toronto Metropolitan University. This repository contains the Node.js backend server that powers the platform by providing RESTful APIs, secure data handling, and robust business logic.

## Features

- **RESTful API Endpoints:** Provides secure endpoints for user authentication, resource management, and other core functionalities.
- **Security:** Implements best practices with middleware such as `helmet` and `cors` to secure HTTP headers and manage cross-origin requests.
- **Modular Architecture:** Clean separation of concerns through controllers, routes, models, and utility functions for scalability and maintainability.
- **Database Integration:** Uses MongoDB with Mongoose for robust and flexible data storage.
- **Testing & Linting:** Comprehensive unit and integration tests with Jest and code quality checks via ESLint.
- **CI/CD Integration:** Automated workflows with GitHub Actions to ensure quality with each commit and pull request.

## Tech Stack

- **Node.js** with **Express.js** - Server framework
- **MongoDB** with **Mongoose** - Database management
- **dotenv** - Environment variable management
- **helmet** & **cors** - Security middleware
- **Jest** - Testing framework
- **Nodemon** - Development server auto-reload

## Getting Started

### Prerequisites

- **Node.js** (v14 or later recommended)
- **npm** (or yarn)
- A running instance of **MongoDB** (local or cloud)

### Installation

1. **Clone the Repository**
```bash
git clone https://github.com/your-org/tmu-hub-backend-node.git
cd tmu-hub-backend-node
```

2. **Install Dependencies**
```bash
npm install
```
Or, if you use yarn:
```bash
yarn install
```

3. **Setup Environment Variables**  
Create a `.env` file in the root directory with:
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
```

4. **Run the Server**
- Development Mode:
```bash
npm run dev
```
- Production Mode:
```bash
npm start
```

### Running Tests

```bash
npm test
```

## Project Structure

```
tmu-hub-backend-node/
├── src/
│   ├── config/       # Configuration files
│   ├── controllers/  # API logic
│   ├── models/       # Mongoose models
│   ├── routes/       # Express routes
│   ├── utils/        # Utilities
│   └── app.js        # Main entry
├── test/            # Tests
├── .env             # Environment vars
├── .gitignore
├── package.json
└── README.md
```

## Contributing

Please review our [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## Code of Conduct

See [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).

## License

MIT License. See [LICENSE](LICENSE) file.

## Acknowledgements

- [Express.js](https://expressjs.com/)
- [Mongoose](https://mongoosejs.com/)
- [Jest](https://jestjs.io/)
- All TMU Hub contributors
