# ChatBot-Project

A modern, interactive chatbot application built with cutting-edge web technologies and deployed on Vercel.

## 🌟 Features

- **Real-time Chat Interface** - Seamless conversation experience with instant responses
- **Modern UI/UX** - Clean, intuitive design optimized for user engagement
- **Responsive Design** - Works perfectly across desktop, tablet, and mobile devices
- **Fast Performance** - Optimized loading times and smooth interactions
- **Cloud Deployment** - Hosted on Vercel for reliable, global accessibility

## 🚀 Live Demo

Check out the live application: [https://chat-bot-project-beta.vercel.app/](https://chat-bot-project-beta.vercel.app/)

## 🛠️ Tech Stack

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)


### Technologies Used:

- **Frontend Framework**: React 
- **Styling**: CSS Modules
- **Chatbot Logic**:Custom Implementation
- **Deployment**: Vercel
- **Language**: JavaScript
- **Runtime**: Node.js

## 📋 Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (v14 or higher)
- npm or yarn package manager
- Git

## 🔧 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/chat-bot-project.git
cd chat-bot-project
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Set up environment variables:
Create a `.env.local` file in the root directory and add your configuration:
```env
# Add your environment variables here
# NEXT_PUBLIC_API_KEY=your_api_key_here
# DATABASE_URL=your_database_url
```

4. Run the development server:
```bash
npm run dev
# or
yarn dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## 📁 Project Structure

```
chat-bot-project/
├── public/          # Static files
├── src/
│   ├── components/  # Reusable UI components
│   ├── pages/       # Application pages
│   ├── styles/      # CSS/styling files
│   ├── utils/       # Utility functions
│   └── api/         # API routes and logic
├── .env.local       # Environment variables (not committed)
├── package.json     # Project dependencies
└── README.md        # Project documentation
```

## 🎯 Usage

1. **Starting a Conversation**: Simply type your message in the input field and press Enter or click Send
2. **Chat History**: Previous conversations are displayed in the chat window
3. **Clear Chat**: Use the clear button to reset the conversation
4. **Responsive Controls**: All features work seamlessly across different devices

## 🚢 Deployment

This project is configured for easy deployment on Vercel:

1. Push your code to GitHub
2. Connect your repository to Vercel
3. Configure environment variables in Vercel dashboard
4. Deploy with one click

Or use the Vercel CLI:
```bash
npm install -g vercel
vercel
```

## 🔐 Environment Variables

| Variable | Description | Required |
|----------|-------------|----------|
| `API_KEY` | Your chatbot API key | Yes |
| `DATABASE_URL` | Database connection string | Optional |
| `NODE_ENV` | Environment mode | Yes |


## 📞 Support

For support, email kaduskarprathmesh05@gmail.com or open an issue in the GitHub repository.

---

⭐ Star this repository if you find it helpful!
