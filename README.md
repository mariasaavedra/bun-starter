# bun-starter
A minimalist and performance-oriented boilerplate that leverages the simplicity and efficiency of Bun, Express, React, and raw SQL.

inimalist Web Boilerplate with Bun, Express, React, and Raw SQL

## Overview

This boilerplate is designed for developers seeking a lean and efficient approach to building web applications. By utilizing Bun for its modern JavaScript runtime, Express for server-side logic, React for dynamic user interfaces, and raw SQL for direct database interactions, this project prioritizes performance and simplicity. The inclusion of Docker ensures a seamless development and deployment process, encapsulating the application in a consistent environment across different stages.

## Features

- **Bun**: A cutting-edge JavaScript runtime that promises faster performance and improved developer experience.
- **Express**: A minimalist web framework for Node.js, facilitating the rapid development of server-side logic and APIs.
- **React**: A front-end library for building user interfaces with a focus on efficiency and flexibility.
- **Raw SQL**: Direct database interactions for full control over queries and database operations, bypassing the complexity of ORMs.
- **Docker**: Containerization of the application to streamline development, testing, and deployment across various environments.

## Getting Started

### Prerequisites

- Docker
- Bun (for local development)
- Node.js (for local development)

### Setup

1. **Clone the repository**

```bash
git clone https://github.com/your-repository.git
cd your-repository
```

2. **Build the Docker container**

```bash
docker build -t your-application-name .
```

3. **Run the application**

```bash
docker run -p 3000:3000 your-application-name
```

The application should now be running on `http://localhost:3000`.

### Development

For local development, ensure Bun and Node.js are installed on your machine. Navigate to the project directory and install dependencies:

```bash
bun install
```

To start the Express server:

```bash
bun run start
```

For React development, navigate to the client directory and start the React app:

```bash
cd client
bun run start
```

## Architecture

- **/server**: Contains Express server configuration and API routes.
- **/client**: Houses the React application codebase.
- **/database**: Includes raw SQL scripts for database schema and seed data.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for discussion.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

