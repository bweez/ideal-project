# Ideal Project

Welcome to the **Ideal Project**, a comprehensive framework designed to streamline the process of creating and maintaining web applications. This setup captures every aspect from design, coding, testing, to deployment using modern tools and best practices.

## Features

- **Storybook for Design**: Build UI components in isolation and visualize your component library. Storybook helps maintain a consistent design system throughout the project.
- **AppMap for API Documentation and Testing**: AppMap captures the execution of your code to help you understand and document API and database interactions. It also helps with performance analysis and testing.
- **OpenAPI Integration**: Automatically generate API documentation using OpenAPI specifications. This ensures your APIs are well-documented and easy to integrate.
- **Docker for Deployment**: Deploy the application in a containerized environment to ensure consistency across different platforms.
- **TypeScript and Deno**: The entire project is written in TypeScript, leveraging the modern runtime Deno for security and simplicity in development.

## Getting Started

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/bweez/ideal-project.git
    cd ideal-project
    ```

2. Install dependencies using Deno:

    ```bash
    deno task install
    ```

3. Start the development environment:

    ```bash
    deno task dev
    ```

### Storybook Setup

Run Storybook to develop UI components in isolation:

```bash
deno task storybook
