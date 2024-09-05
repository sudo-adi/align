
## Prerequisites

- Node.js (>=22.x)
- npm (>=10.x) for the client
- yarn (>=1.22) for the server

## Setup

### Client Setup

1. **Navigate to the `client` folder:**

    ```bash
    cd align/client
    ```

2. **Install the client dependencies using npm:**

    ```bash
    npm install
    ```

### Server Setup

1. **Navigate to the `server` folder:**

    ```bash
    cd align/server
    ```

2. **Install the server dependencies using yarn:**

    ```bash
    yarn
    ```

## Running the Application

### Start the Server

# The server can use port 4000 port

**make sure to make .env file before preceeding to other steps.**

``PORT=4000``
paste the bove line in .env file



1. **Navigate to the `server` folder:**

    ```bash
    cd align/server
    ```

2. **Start the server:**

    ```bash
    yarn dev
    ```

   The server will run on `http://localhost:3000` by default. You can adjust the port in your `.env` file if needed.

### Start the Client

1. **Navigate to the `client` folder:**

    ```bash
    cd align/client
    ```

2. **Start the client:**

    ```bash
    npm run dev
    ```

   The client will run on `http://localhost:3001` by default. Adjust the port as needed in the client configuration.

## Endpoints

The server exposes the following endpoint:

- `GET /v1/api/align` - Returns the text "align".

## Environment Variables

The server uses environment variables defined in a `.env` file. Create a `.env` file in the `server` folder and add the following:

