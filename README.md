# AI Video Generator - HeyGen Integration

A minimal AI video generation web application that transforms text prompts into engaging videos using the HeyGen API.

## 🚀 Features

- **Simple Interface**: Clean HTML/CSS/JS frontend
- **AI-Powered**: Uses HeyGen API for video generation
- **Real-time Status**: Polling-based status updates
- **Responsive Design**: Works on desktop and mobile
- **Prompt Engineering**: Automatically enhances user prompts
- **Error Handling**: Graceful fallbacks and error messages
- **Vercel Ready**: Optimized for Vercel deployment

## 🛠 Tech Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Backend**: Node.js with Vercel serverless functions
- **API**: HeyGen AI Video Generation
- **Deployment**: Vercel

## 📁 Project Structure

```
├── api/
│   └── generate-video.js    # Serverless API endpoint
├── index.html               # Frontend interface
├── package.json             # Dependencies
├── vercel.json             # Vercel configuration
├── .env.example            # Environment variables template
└── README.md               # This file
```

## 🔧 Setup Instructions

### 1. Clone and Install

```bash
# Clone the repository
git clone <your-repo-url>
cd ai-video-generator

# Install dependencies
npm install
```

### 2. Environment Configuration

```bash
# Copy environment template
cp .env.example .env

# Add your HeyGen API key
echo "HEYGEN_API_KEY=NDRmYTAxNGZkMjNlNGEzZDlkMmY4NGM3NzUzNTQ3MDctMTc1NjAxMDE3OQ==" > .env
```

### 3. Local Development

```bash
# Install Vercel CLI globally