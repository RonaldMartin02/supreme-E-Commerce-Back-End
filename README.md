# supreme-E-Commerce-Back-End

## Table of Contents

- [Description](#description)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Description

Supreme E-Commerce Back-End is the back-end component of a comprehensive e-commerce application. It provides the server-side functionality necessary to manage and process product data, categories, and tags. The application utilizes a RESTful API architecture to handle CRUD operations, allowing for seamless integration with a front-end application.

---

## Technologies Used

The back-end is built using the following technologies:

- **Node.js**: A JavaScript runtime for server-side development.
- **Express.js**: A web application framework for Node.js, used for building the API.
- **Sequelize**: An ORM (Object-Relational Mapping) library for interacting with databases.
- **MySQL**: The chosen relational database management system for storing and retrieving data.
- **dotenv**: A zero-dependency module that loads environment variables from a .env file.

---

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/RonaldMartin02/supreme-E-Commerce-Back-End.git
   ```
2. Navigate to the project directory:
   ``` bash
   cd supreme-E-Commerce-Back-End
   ```
3. Install dependencies:
   ```bash 
   npm install
   ```
4. Create a .env file in the root directory and set the following variables:
    ```env 
    DB_NAME=your_database_name
    DB_USER=your_database_user
    DB_PASSWORD=your_database_password
    ```
5. Initialize the database:
    ```bash 
    npm run seed
    ```
6. Start the application:
    ```bash
    npm start
    ```
    The server should now be running on http://localhost:3001.

---
## Deployment
<video src="./assets/MP4/13_ORM.mp4"></video>

[Link to the Youtube video](https://www.youtube.com/watch?v=ermnjEHeGPM)

---
## Usage

The API exposes endpoints for managing products, categories, and tags. You can refer to the API documentation for details on available routes and their functionalities. Make sure to integrate this back-end with the corresponding front-end application for a complete e-commerce experience.

---

## Contributing

Contributions are welcome! If you find a bug or have a suggestion, please open an issue or submit a pull request. Follow the [Contributing Guidelines](CONTRIBUTING.md) for more details.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
## Contact

For any inquiries, please contact:

- **Ronald Martin**
  - GitHub: [RonaldMartin02](https://github.com/RonaldMartin02)
  
Feel free to reach out for support or collaboration.

---