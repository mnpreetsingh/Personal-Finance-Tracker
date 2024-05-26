# Personal Finance Tracker

## Overview

Finance Tracker is a web application built using the MERN stack (MongoDB, Express.js, React, Node.js) that helps users track their expenses and income. It integrates Clerk for seamless signup and signout functionality.

## Features

- **User Authentication:** Secure signup and signout powered by Clerk.
- **Expense Tracking:** Log and categorize your expenses.
- **Income Tracking:** Record and manage your sources of income.
- **Dashboard:** Visualize your financial data with charts and summaries.
- **Responsive Design:** Accessible on both desktop and mobile devices.

## Technologies Used

- **Frontend:** React.js
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** Clerk
- **Styling:** CSS, Bootstrap

## Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/mnpreetsingh/Personal-Finance-Tracker
    cd Personal-Finance-Tracker
    ```

2. **Install dependencies for the server:**
    ```sh
    cd server
    npm install
    ```

3. **Install dependencies for the client:**
    ```sh
    cd ../client
    npm install
    ```

4. **Set up environment variables:**
   - Create a `.env` file in the `server` directory and add the following:
     ```env
     MONGO_URI=your_mongodb_connection_string
     CLERK_FRONTEND_API=your_clerk_frontend_api
     CLERK_API_KEY=your_clerk_api_key
     ```
   - Create a `.env` file in the `client` directory and add the following:
     ```env
     REACT_APP_CLERK_FRONTEND_API=your_clerk_frontend_api
     ```

## Usage

1. **Start the server:**
    ```sh
    cd server
    npm start
    ```

2. **Start the client:**
    ```sh
    cd ../client
    npm start
    ```

3. **Open your browser and navigate to:**
    ```sh
    http://localhost:5173
    ```

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.


