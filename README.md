# E-commerce Application

A full-stack e-commerce application built with Spring Boot and React.

## Tech Stack

### Backend
- **Java 17+** with Spring Boot
- **Maven** for dependency management
- **Spring Boot** framework

### Frontend
- **React 19** with Vite
- **Modern JavaScript (ES2020+)**
- **ESLint** for code quality

## Project Structure

```
.
├── backend/                 # Spring Boot application
│   ├── src/
│   ├── pom.xml
│   └── mvnw
└── frontend/               # React application
    ├── src/
    ├── package.json
    └── vite.config.js
```

## Getting Started

### Prerequisites
- Java 17 or higher
- Node.js 18+ and npm
- Maven (or use included Maven wrapper)

### Backend Setup

1. Navigate to the backend directory:
```bash
cd backend
```

2. Run the application using Maven wrapper:
```bash
./mvnw spring-boot:run
```

Or on Windows:
```bash
mvnw.cmd spring-boot:run
```

The backend will start on `http://localhost:8080`

### Frontend Setup

1. Navigate to the frontend directory:
```bash
cd frontend
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

The frontend will start on `http://localhost:5173`

## Available Scripts

### Backend
- `./mvnw spring-boot:run` - Run the application
- `./mvnw clean install` - Build the project
- `./mvnw test` - Run tests

### Frontend
- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Configuration

### Backend
Configuration can be modified in `src/main/resources/application.properties`

### Frontend
Vite configuration is available in `vite.config.js`

## Development

### Code Quality
The project includes ESLint configuration for maintaining code quality standards in the frontend.

### Hot Module Replacement
The React frontend supports HMR for fast development experience.

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License.

## Contact

For questions or support, please open an issue in the repository.
