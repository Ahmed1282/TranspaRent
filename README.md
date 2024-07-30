# TranspaRent

## Overview

TranspaRent is an innovative rental property management application designed to bring efficiency, security, and transparency to the rental process. By integrating blockchain technology, it ensures immutable and transparent contract management, reducing disputes and enhancing trust. The AI-powered backend leverages machine learning to provide intelligent insights and automation, streamlining operations for property managers and tenants alike. The client application offers a user-friendly interface for seamless interaction with the system, making rental management more accessible and effective.

## Project Structure

The project is divided into three main components:
- **Blockchain**: Handles contract management using blockchain technology.
- **AI**: AI-powered backend services.
- **Client**: Frontend client application.

## Prerequisites

Make sure you have the following installed:
- Node.js
- Python 3.x
- Truffle
- Flask

## Setup Instructions

### 1. Blockchain

1. Navigate to the Blockchain directory:
    ```bash
    cd Blockchain
    ```

2. Deploy the contracts:
    ```bash
    truffle migrate --reset --config ./truffle-config.cjs
    ```

### 2. AI

1. Navigate to the AI directory:
    ```bash
    cd AI
    ```

2. Start the Flask server:
    ```bash
    python flaskapp.py
    ```

### 3. Client

1. Navigate to the Client directory:
    ```bash
    cd Client
    ```

2. Install the necessary dependencies:
    ```bash
    npm install
    ```

3. Start the development server:
    ```bash
    npm run dev
    ```

## Running the Project

To run the entire project, follow these steps:

1. Open three separate terminal windows or tabs.

2. In the first terminal, deploy the blockchain contracts:
    ```bash
    cd Blockchain
    truffle migrate --reset --config ./truffle-config.cjs
    ```

3. In the second terminal, start the AI backend:
    ```bash
    cd AI
    python flaskapp.py
    ```

4. In the third terminal, start the client application:
    ```bash
    cd Client
    npm run dev
    ```

## Project Team

- **Usman Kamal**
  - [GitHub](https://github.com/usmanokamal)
  - [LinkedIn](https://www.linkedin.com/in/usmanokamal)
- **Ameera Haider**
  - [GitHub](https://github.com/ameerahaider)
  - [LinkedIn](https://www.linkedin.com/in/ameerahaider)
- **Ahmed Baig**
  - [GitHub](https://github.com/Ahmed1282)
  - [LinkedIn](https://www.linkedin.com/in/ahmedbaig1282)

## Supervisors

- **Dr. Qaiser Shafi**
  - [LinkedIn](https://www.linkedin.com/in/dr-qaisar-shafi-b3b03839)
- **Dr. Muhammad Asim**
  - [LinkedIn](https://www.linkedin.com/in/muhammad-asim-3874312a)
