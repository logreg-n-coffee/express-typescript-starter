# Express TypeScript Starter

This project provides a simple setup for building web applications using Express and TypeScript.

## Features

- **Express**: A minimal and flexible Node.js web application framework.
- **TypeScript**: A superset of JavaScript that adds optional static typing.
- **Dotenv**: Zero-dependency module that loads environment variables from a `.env` file.

## Prerequisites

Before you begin, ensure you have installed:

- Node.js
- npm (comes bundled with Node.js)

## Installation

1. Clone the repository:

   ```bash
   git clone [repository_url]
   ```

2. Navigate to the project directory:

    ```bash
    cd express-typescript-starter
    ```

3. Install the dependencies:

    ```bash
    npm install
    ```

## Scripts

The project comes with the following npm scripts:

- `npm run init`: Installs project dependencies.
- `npm run build`: Compiles TypeScript files to JavaScript in the `./dist` directory.
- `npm run start`: Starts the server from the compiled JavaScript.
- `npm run dev`: Runs the server in development mode with hot-reloading enabled.

## Running the Server

For development purposes, run:

```bash
npm run dev
```

Once started, you can navigate to `http://localhost:3000` in your browser (or whatever port you've defined in your `.env` file) and you should see:

`Express + TypeScript Server is running now! 🚀`

## Environment Variables

Create a `.env` file in the root directory and define the environment variables you'd like to use. For example:

`PORT=4000`

This will set the server's port to 4000.

## Author

Rui Hu

## License

ISC

---

Happy coding! 🚀
