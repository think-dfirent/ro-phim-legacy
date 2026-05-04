# RoPhimLegacy - Movie Discovery & Recommendation System

**RoPhimLegacy** is a modern movie management and recommendation application, built with a robust Fullstack architecture. The project focuses on a smooth user experience and movie analysis capabilities through AI.

## Technologies Used

### Backend (Server)

- **Java 21** & **Spring Boot 3.2.2**
- **Spring Security** & **JWT** (Stateless/Stateful Hybrid Authentication)
- **Spring Data MongoDB**: NoSQL database management
- **Google Gemini API**: AI Service feature support
- **Maven**: Dependency and project lifecycle management

### Frontend (Client)

- **React** (Vite)
- **Axios**: API request handling with Interceptors
- **Modern CSS**: Dark Mode interface for optimized experience

### Testing & Tools

- **Cypress**: E2E Testing
- **JUnit 5 & Mockito**: Unit Test for the Service layer
- **MongoDB Compass**: Visual data management

## Key Features

- **Movie Discovery**: Extensive movie list with high-quality images from TMDB.
- **Smart Recommendation**: Movie recommendation system based on user preferences.
- **Rating System**: Users can rate movies (Excellent, Okay, Bad, Terrible) and write reviews.
- **Administrator (Admin)**: Privileges to edit and delete movies directly on the interface.
- **High Security**: Multi-layer Authentication system to protect against XSS and CSRF attacks.

## Installation

1. **System Requirements**: Pre-installed Java 21, Node.js, and Local MongoDB.
2. **Environment Variables Configuration**: Copy `.env.example` to `.env` and fill in the information:
   - `MONGODB_URI`
   - `GOOGLE_API_KEY`
   - `SECRET_KEY` (For JWT)
3. **Run Backend**:Bash

   `cd ./Server/RoPhimLegacyServer
mvn spring-boot:run`

4. **Run Frontend**:Bash

   `cd ./Client/ro-phim-legacy-client
npm run dev`
