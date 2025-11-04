🧠 Smart Email Assistant

An AI-powered email automation system built with Spring Boot and Spring AI, designed to generate context-aware and tone-specific email responses.
This project demonstrates backend development, API integration, and the use of AI frameworks in enterprise applications.

🚀 Features

Generates intelligent, personalized email replies using Spring AI.

Implements RESTful APIs for request handling and response generation.

Accepts JSON payloads and tested via Postman.

Supports tone control (e.g., friendly, formal, neutral).

Built following Spring MVC architecture with Dependency Injection.

🧩 Tech Stack
Category	Technologies
Backend	Java, Spring Boot, Spring AI
API Testing	Postman
Build Tool	Maven
Architecture	Spring MVC
Version Control	Git, GitHub
⚙️ How to Run Locally

Clone the repository:

git clone https://github.com/NagullaSivaNandini/Smart-Email-Assistant.git


Navigate to the Spring Boot app:

cd Smart-Email-Assistant/spring-ai-demo


Run the project:

mvn spring-boot:run


Test the API in Postman:

POST http://localhost:8080/api/email/generate


Example payload:

{
  "emailContent": "Hello, thank you for contacting us.",
  "tone": "friendly"
}

💡 Learning Highlights

Applied Java and Spring Boot concepts to build scalable RESTful APIs.

Integrated AI capabilities using Spring AI for dynamic response generation.

Strengthened understanding of SDLC, OOP, and modular backend design.
