# Smart AI Email Assistant - Backend 

The backend engine for the Smart Email Assistant, built with **Spring Boot 3** and **Spring AI**. It leverages Google's **Gemini 1.5 Flash** model to generate context-aware email replies.

##  Tech Stack
* **Language:** Java 21
* **Framework:** Spring Boot 3.4.1
* **AI Integration:** Spring AI (Google Gemini API)
* **Build Tool:** Maven
* **Deployment:** Docker on Render

##  Key Features
* **AI-Powered Generation:** Processes email content and tone to generate professional replies.
* **RESTful API:** Clean endpoints for processing generation requests.
* **Dockerized:** Fully containerized for consistent deployment across environments.
* **CORS Configured:** Securely handles requests from the React frontend and Chrome Extension.

##  Live API
The backend is deployed at: `https://smart-email-assistant-cqb2.onrender.com`

##  Local Setup
1. Clone the repository.
2. Set your Environment Variables:
   - `GEMINI_URL`: Google Gemini API endpoint.
   - `GEMINI_KEY`: Your Google AI Studio API Key.
3. Run `mvn clean install`.
4. Run `java -jar target/email-writer-sb-0.0.1-SNAPSHOT.jar`.
