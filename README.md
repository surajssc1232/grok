# Sir Germaint: Royal AI Chat Assistant 👑🤖

## Project Overview
Sir Germaint is an elegant AI chat application powered by Grok AI, featuring a regal conversational experience with markdown-rich responses.

### 🌟 Features
- Royal AI persona with eloquent communication
- Secure authentication system
- Rate-limited API interactions
- Markdown-formatted responses
- Deployed on Vercel

## 🚀 Technology Stack
- **Backend**: Python, Flask
- **AI Model**: Grok-Beta (X.AI)
- **Deployment**: Vercel
- **Authentication**: Session-based login

## 🔧 Prerequisites
- Python 3.9+
- X.AI API Key
- Vercel Account (optional)

## 🛠 Local Setup

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/sir-germaint.git
cd sir-germaint
```

### 2. Create Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables
Create a `.env` file with:
```
XAI_API_KEY=your_x_ai_api_key
ADMIN_PASSWORD=your_admin_password
```

### 5. Run the Application
```bash
python main.py
```

## 🌐 Deployment

### Vercel Deployment
1. Install Vercel CLI: `npm i -g vercel`
2. Login to Vercel: `vercel login`
3. Deploy: `vercel`

### Environment Variables in Vercel
Set the following in Vercel Project Settings:
- `XAI_API_KEY`
- `ADMIN_PASSWORD`

## 🔒 Security
- Implements session-based authentication
- Rate-limited API calls
- Secure environment variable management

## 🎨 Conversational Style
Sir Germaint speaks in an eloquent, royal English style, using extensive markdown formatting:
- **Bold** for emphasis
- *Italic* for dramatic effect
- ### Headings for structure
- > Quotes and proclamations
- Bullet points for clarity
- `Code blocks` for technical terms

## 🐛 Troubleshooting
- Check Vercel function logs
- Verify API key and quota
- Ensure all environment variables are set

## 📜 License
[GNU]

## 🤝 Contributing
1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## 🌈 Acknowledgements
- Powered by Grok AI
- Built with ❤️ and royal elegance
