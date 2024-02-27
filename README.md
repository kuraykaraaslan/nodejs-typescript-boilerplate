# Node.js TypeScript Boilerplate

This boilerplate provides a foundation for building Node.js applications using TypeScript.

## Features

- Pre-configured setup for Node.js applications with TypeScript.
- Includes essential dependencies for development and production.
- Ready-to-use scripts for building, testing, and running the application.
- Integrated with popular libraries like dotenv and helmet for better security and environment configuration.

## Prerequisites

Before getting started, ensure you have the following installed on your machine:

- Node.js
- npm or yarn

## Installation

1. Clone the repository:

```bash
git clone https://github.com/kuraykaraaslan/nodejs-typescript-boilerplate.git
```

2. Navigate to the project directory:

```bash
cd nodejs-typescript-boilerplate
```

3. Install dependencies:

```bash
npm install
```

## Usage

### Development

To run the application in development mode:

```bash
npm run dev
```

This command starts the application using `ts-node-dev`, which automatically restarts the server on file changes.

### Production

To build the application for production:

```bash
npm run build
```

This command compiles TypeScript files into JavaScript in the `dist` directory.

To start the production server:

```bash
npm start
```

### Testing

To run tests:

```bash
npm test
```

## Configuration

- Environment variables can be configured using a `.env` file.
- Check `src/index.ts` for the main application entry point.

## License

This project is licensed under the [UNLICENSED](LICENSE) License.

## Author

- [Kuray Karaaslan](https://github.com/kuraykaraaslan)

## Contributing

Contributions are welcome! Fork the repository and submit a pull request.

