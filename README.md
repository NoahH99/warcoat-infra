# Warcoat Infra

Infrastructure components for the Warcoat Discord bot microservice system.

## Overview

This repository contains the infrastructure configuration for the Warcoat Discord bot system. The system is designed with a microservice architecture to ensure scalability and maintainability.

## Components

- Docker Compose configuration for local development and deployment
- Database migration scripts for schema management
- Infrastructure as code resources

## Getting Started

### Prerequisites

- Docker and Docker Compose
- Database client (for connecting to the deployed services)

### Setup

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/warcoat-infra.git
   cd warcoat-infra
   ```

2. Start the infrastructure:
   ```
   docker-compose up -d
   ```

3. To stop the services:
   ```
   docker-compose down
   ```

## Database Migrations

Database migrations are managed with Flyway and stored in the `migrations/` directory.

## License

This project is licensed under the [MIT License](LICENSE).

```
MIT License

Copyright (c) 2025 Noah Hendrickson

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
