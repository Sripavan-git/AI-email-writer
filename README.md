# AI-Powered Email Generator

An AI-powered email generator that creates professional email responses based on user input. This full-stack project utilizes **React** for the frontend, **Spring Boot** for the backend, and **Google's Gemini API** for AI-generated email replies.

## 🚀 Features

- Accepts user input for email text and desired tone
- Uses **Gemini API** to generate a natural, professional reply
- Simple **React frontend** for user interaction
- **Spring Boot backend** to process requests and call the AI model
- Fully functional **REST API** for AI email generation

## 🛠 Tech Stack

### Frontend:

- React
- Axios (for API calls)
- Tailwind CSS (for styling)

### Backend:

- Spring Boot
- WebClient (for API calls)
- Jackson (for JSON parsing)

### AI Integration:

- Google's **Gemini API**

## 🔧 Setup & Installation

### Prerequisites

- Node.js & npm
- Java 17+
- Spring Boot

### Backend Setup

```bash
# Clone the repository
git clone https://github.com/yourusername/ai-email-generator.git
cd ai-email-generator/backend

# Set up environment variables
export GEMINI_API_KEY=your_api_key
export GEMINI_API_URL=https://gemini-api-url

# Build and run the backend
./mvnw spring-boot:run

```

### Frontend Setup

```bash
cd ../frontend

# Install dependencies
npm install

# Run the frontend
npm start

```
