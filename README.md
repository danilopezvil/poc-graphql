# GraphQL PoC

A Proof of Concept project demonstrating GraphQL implementation using Spring Boot.

## Overview

This project is a demonstration of GraphQL implementation using Spring Boot 3.4.5 and Java 21. It showcases how to build a GraphQL API with Spring Boot's GraphQL support.

## Prerequisites

- Java 21 or higher
- Maven 3.6.x or higher

## Technology Stack

- Spring Boot 3.4.5
- Spring GraphQL
- Lombok
- Maven

## Getting Started

1. Clone the repository:
```bash
git clone [repository-url]
cd poc-graphql
```

2. Build the project:
```bash
./mvnw clean install
```

3. Run the application:
```bash
./mvnw spring-boot:run
```

The application will start on the default port 8080.

## Project Structure

```
src/
├── main/
│   ├── java/        # Java source files
│   └── resources/
│       └── graphql/ # GraphQL schema files
└── test/            # Test files
```

## Features

- GraphQL API implementation
- Spring Boot integration
- Lombok for reducing boilerplate code

## Development

This project uses:
- Maven for dependency management
- Spring Boot for the application framework
- GraphQL for API implementation
- Lombok for reducing boilerplate code

## Testing

Run the tests using:
```bash
./mvnw test
```

## License

[Add your license information here]

## Contributing

[Add contribution guidelines here] 