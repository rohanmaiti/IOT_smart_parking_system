# Parking Management System

This project implements a Parking Management System where users can register vehicles, assign parking spaces, and manage parking operations. It provides CRUD (Create, Read, Update, Delete) operations for users, vehicles, and parking spaces. The system is implemented using a RESTful API framework in Node.js.

## API Endpoints

### Users

- **GET /users**: Retrieve all users.
- **GET /users/:userID**: Retrieve user by ID.
- **POST /users**: Register a new user.

### Vehicles

- **GET /vehicles**: Retrieve all parked vehicles.
- **GET /vehicles/:PlateNum**: Retrieve vehicle by license plate number.
- **POST /vehicles/in**: Assign a parking space and record entry time.
- **POST /vehicles/out**: Create the fare for parking and release the parking space.

### Parking Spaces

- **GET /parking**: Retrieve current parking spaces.
- **POST /parking/in**: Assign a new parking space.
- **POST /parking/out**: Release a parking space.

## Technologies Used

- Node.js
- Express.js (or any other RESTful API framework)
- MongoDB (or any other database system for storing data)
- JavaScript

## Usage

1. Install Node.js and MongoDB on your system.
2. Clone this repository.
3. Install dependencies using `npm install`.
4. Configure the database connection in the `.env` file.
5. Start the server using `npm start`.
6. Access the API endpoints using a tool like Postman or any REST client.

## Contributing

Contributions to this project are welcome! Feel free to open issues or submit pull requests for bug fixes, features, or enhancements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
