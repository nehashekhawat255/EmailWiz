# EmailWiz
**EmailWiz** is an intelligent email reply assistant that uses AI to generate personalized, contextual email responses. Available as both a Chrome extension and a web application, EmailWiz helps you craft professional replies effortlessly.

## 🚀 Features

### Chrome Extension
- **One-Click AI Reply**: Adds an "AI Reply" button directly in your email interface
- **Contextual Understanding**: Analyzes the entire email thread for personalized responses
- **Seamless Integration**: Works directly within your existing email workflow
- **Automatic Population**: Generated reply appears instantly in your compose window

### Web Application
- **Email Analysis**: Paste any email content to generate appropriate replies
- **Tone Customization**: Choose from multiple response tones:
  - 🎯 **Professional** (default)
  - 😊 **Friendly**
  - 💬 **Casual**
- **One-Click Copy**: Copy generated replies directly to clipboard
- **Clean Interface**: Built with Material-UI for intuitive user experience

## 🛠️ Technology Stack

### Backend
- **Java Spring Boot**: Robust REST API architecture
- **Google Gemini API**: Advanced AI-powered email generation
- **RESTful Services**: Clean API endpoints for seamless integration

### Frontend (Web App)
- **Vite**: Fast build tool and development server
- **Material-UI**: Modern, responsive component library
- **React**: Dynamic user interface

### Chrome Extension
- **Manifest V3**: Latest Chrome extension standards
- **Content Scripts**: Direct integration with email interfaces
- **Background Service**: Efficient API communication

## 📦 Installation

### Chrome Extension
1. Clone the repository
2. Load the extension in Chrome developer mode
3. Navigate to any email and look for the "AI Reply" button

### Web Application
1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. Access the application at `http://localhost:5173`

### Backend Setup
1. Clone the repository
2. Configure your Gemini API key in application properties
3. Run the Spring Boot application:
   ```bash
   ./mvnw spring-boot:run
   ```

## 🔧 Configuration

### API Key Setup
Add your Google Gemini API key to the backend configuration:
```properties
gemini.api.key=your_api_key_here
```

## 🎯 Use Cases

- **Business Communications**: Professional responses for work emails
- **Customer Support**: Consistent, helpful replies to customer inquiries
- **Personal Correspondence**: Friendly responses to personal emails
- **Time Management**: Quick replies when you're short on time
- **Language Assistance**: Help with crafting well-structured responses

## 🔐 Privacy & Security

- No email content is stored permanently
- All processing happens through secure API calls
- Your data is processed only for reply generation
- No personal information is retained after processing

---

**Made with ❤️ by Neha Kanwar**

*Transform your email experience with AI-powered replies!*
