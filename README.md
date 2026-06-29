
👗 AI Fashion Sales Assistant
An AI-powered virtual sales assistant for fashion and clothing brands that automates customer interactions across WhatsApp and Instagram. The assistant helps customers discover products, recommends outfits using AI, answers frequently asked questions, collects orders, and provides a seamless shopping experience 24/7.

🚀 Features
🤖 AI-Powered Conversations
Natural conversations using Google Gemini AI
Understands English and Urdu
Context-aware responses
Personalized product recommendations
🛍️ Product Recommendation
Recommends clothing based on customer preferences

Suggests products by:

Category
Budget
Color
Size
Style
Occasion
💬 WhatsApp Automation
Automatic customer replies
Product inquiry handling
Order collection
Customer support
📷 Instagram DM Automation
Responds to Instagram direct messages
Handles product inquiries
Shares product recommendations
Collects customer information
📦 Order Collection
Customer details
Shipping address
Selected products
Quantity
Order summary
📊 Admin Dashboard
View all conversations
Manage products
Track customer orders
Monitor AI interactions
View analytics
🌐 Multilingual Support
English
Urdu
🛠 Tech Stack
Frontend
React.js
Tailwind CSS
Backend
Node.js
Express.js
Database
MongoDB
Mongoose
AI
Google Gemini 1.5 Flash
Automation (Optional)
n8n
📁 Project Structure
AI-Fashion-Sales-Assistant/
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   ├── services/
│   ├── config/
│   └── server.js
│
├── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   ├── services/
│   └── App.js
│
├── docs/
│
├── README.md
└── .env
📦 Installation
Clone Repository
git clone https://github.com/aizaamin131-cpu/fashion-ai-assistant.git
cd AI-Fashion-Sales-Assistant
Backend Setup
cd backend
Install dependencies

npm install
Start development server

npm run dev
Frontend Setup
cd frontend
Install dependencies

npm install
Run the application

npm start
n8n Setup (Optional)
Run n8n using Docker

```docker run -d --name n8n -p 5678:5678 n8nio/n8n

---

# Environment Variables

Create a `.env` file inside the backend folder.

```env
PORT=5000

MONGO_URI=mongodb://127.0.0.1:27017/ai-fashion-db

GEMINI_API_KEY=your_gemini_api_key
AI Workflow
Customer sends a message.
Backend receives the request.
Gemini AI processes the query.
Product database is searched.
AI generates a personalized response.
Customer receives the reply.
Order details are stored in MongoDB.
Future Enhancements
AI Outfit Recommendations
Voice Message Support
Image-Based Product Search
Live Inventory Checking
Human Agent Handoff
Order Tracking
Customer Purchase History
Sales Analytics Dashboard
Multi-Brand Support
Website Chat Widget
Team Roles
Role	Responsibility
Database Designer	Database schema and MongoDB
Backend Developer	APIs and business logic
AI Developer	Gemini AI integration
Prompt Engineer	AI prompts and response optimization
WhatsApp Specialist	WhatsApp automation
Instagram Specialist	Instagram DM automation
Frontend Developer	Admin dashboard and UI
Tester & Documentation	Testing, bug fixing, and documentation
License
This project is developed as part of the CodeCelix AI Internship Program for educational and demonstration purposes.
