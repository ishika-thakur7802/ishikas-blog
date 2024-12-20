# Ishika's Blog

## Overview
Welcome to the repository for my personal blog website! This project is a tech blog platform where I share insights, tutorials, and experiences related to various technical topics and projects. The blog is enhanced with a unique AI chatbot, **Ishika AI**, designed to provide users with personalized guidance and complement the blog's content.

## Features
- **Home Page**:
  - Main banner with a welcome message and site logo.
  - Featured Post of the Day.
  - Recent Posts section for quick access to the latest blogs.
  - Sidebar with search functionality, social media links, and "Ask Ishika AI" button.
- **Blog Post Page**:
  - Detailed content display with options to highlight text.
  - Interactive AI widget accessible throughout the page.
  - Related Articles section at the bottom.
  - Like, comment, and share functionality.
- **Interactive AI Chatbot**:
  - Personalized as "Ishika" to offer insights based on blog content.
  - In-depth answers for blog-related queries, referencing specific blog posts.
  - High-level responses for uncovered topics, with an option to notify the author to create relevant content.
- **Text Highlighting**:
  - Highlight text in blogs for personal emphasis or to ask AI for detailed explanations.
- **User Preferences**:
  - Light/Dark theme toggle.
  - User profiles for personalized experiences.

## Tech Stack
### Frontend
- **React**
  - React Router for navigation.
  - Axios for API communication.
  - Material-UI or Tailwind CSS for responsive design.

### Backend
- **Spring Boot**
  - REST APIs for blog management, comments, and AI interaction.
  - Spring Security for user authentication and role-based access.
  - Spring Data JPA for database interactions.

### Database
- **MySQL** or **PostgreSQL**
  - Tables for users, blog posts, comments, and highlights.

### AI Integration
- Custom AI model fine-tuned on blog content or integration with GPT models.
- Full-text search indexing using ElasticSearch or custom indexing logic.

### Deployment
- **Frontend**: Netlify, Vercel, or AWS S3 + CloudFront.
- **Backend**: Heroku, AWS Elastic Beanstalk, or DigitalOcean.
- **Database**: AWS RDS or Cloud SQL.

## Setup Instructions
### Prerequisites
- Node.js and npm installed.
- Java JDK and Maven installed.
- MySQL/PostgreSQL database setup.

### Backend Setup
1. Clone the repository and navigate to the backend folder:
   ```bash
   git clone <repository-url>
   cd backend
   ```
2. Configure the application properties in `src/main/resources/application.properties`:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/blog_db
   spring.datasource.username=<your-username>
   spring.datasource.password=<your-password>
   jwt.secret=<your-secret>
   ```
3. Build and run the application:
   ```bash
   mvn spring-boot:run
   ```

### Frontend Setup
1. Navigate to the frontend folder:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm start
   ```

### Deployment
- Deploy the frontend and backend separately using the services mentioned in the tech stack.

## Future Enhancements
- Push notifications for new blogs.
- Advanced analytics for user engagement.
- AI-powered recommendations for related posts.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Acknowledgments
Special thanks to all open-source libraries and tools used in this project.
