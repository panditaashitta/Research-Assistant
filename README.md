## 📘 Research Assistant – Spring Boot + Gemini AI
A lightweight and intelligent Research Assistant API built with Spring Boot that integrates with Google Gemini AI to perform powerful text-processing tasks such as:
🔍 Summarizing content
🤖 Generating AI-backed research insights
This project exposes a REST endpoint that accepts user input, sends a structured prompt to Gemini API, and returns clean AI-generated output.

## 🚀 Features
✔ Spring Boot 3 / Java 17+
✔ WebClient for non-blocking HTTP calls
✔ Configurable Gemini API key
✔ Robust JSON parsing using Jackson
✔ Simple and modular Controller + Service design
✔ Clean prompt-based request handling

## ⚙️ Setup & Installation
1. Clone the Repository
git clone https://github.com/your-username/research-assistant.git
cd research-assistant

2. Add Your Gemini API Key
Open:src/main/resources/application.properties
Add:spring.application.name=research-assistant
gemini.api.url=YOUR_API_URL_HERE
gemini.api.key=YOUR_API_KEY_HERE

3. Build the Project
mvn clean install

4. Run the Application
mvn spring-boot:run

The server will start on:
http://localhost:9090

## 🔌API Usage
POST /api/research/process

Send a JSON body like:

{
  "operation": "summarise",
  "content": "Artificial Intelligence is transforming industries..."
}

## 🛠 Tech Stack
Java 17+
Spring Boot 3+
Spring WebFlux
WebClient
Jackson Databind
Maven

## 📄 License
This project is open-source and available under the MIT License.