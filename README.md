

---

# Stock Trading Application 

## Overview
This Stock Trading Application is a web-based platform built using the Express.js framework in TypeScript. It allows users to place limit orders for stocks, managing their portfolios of various stock holdings and currency balances. The application is designed with simplicity in mind, providing a robust backend for stock trading functionality.

## Features
- User registration and management.
- Real-time placing of bid and ask orders.
- Portfolio management with stock and currency balances.
- Support for the "GOOGLE" stock ticker (extendable to other stocks).

## Getting Started

### Prerequisites
- Node.js
- npm (Node Package Manager)

### Installation
1. Clone the repository:

2. Navigate to the project directory:

3. Install the dependencies:
   ```
   npm install
   ```

### Running the Application
1. Start the server:
   ```
   npm start
   ```
2. The server will be running at `http://localhost:3000`.

## Usage
- To place an order, send a POST request to `/order` with the following JSON body:
  ```json
  {
    "side": "bid", // or "ask"
    "price": 100,
    "quantity": 10,
    "userId": "1"
  }
  ```
- Additional endpoints and usage instructions can be found in the documentation.



## Contributing
Contributions to the project are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

---

