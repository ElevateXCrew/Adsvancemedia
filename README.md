# ADSVANCE MEDIA

## 🚀 AI-Powered Sales Chatbot Website

A professional company website with an intelligent AI chatbot that engages visitors, understands their needs, and helps close deals.

## ✨ Features

- **AI Sales Agent**: Groq-powered chatbot that:
  - Engages clients professionally
  - Asks qualifying questions
  - Suggests best services
  - Generates proposals
  - Handles pricing inquiries
  - Maintains conversation context

- **Company Showcase**: Services, portfolio, team, and partners
- **Responsive Design**: Mobile-friendly WhatsApp-style chat widget
- **Fast & Secure**: Optimized performance with privacy-focused approach

## 📁 Project Structure

```
adsvancemedia/
├── index.html              # Main website
├── js/
│   ├── pdf-data.js        # Company knowledge base (EDIT THIS)
│   ├── groq-chatbot.js    # AI chatbot logic
│   ├── script.js          # Website interactions
│   └── performance.js     # Performance optimization
├── css/                   # Stylesheets
├── images/                # Assets
├── .env                   # API key (not in git)
└── README.md             # This file
```

## 🔧 Setup & Configuration

### 1. Update Company Data
Edit `js/pdf-data.js` and paste your company information between the backticks:
```javascript
const PDF_DATA = `
YOUR COMPANY INFO HERE
`;
```

### 2. API Key
Groq API key is already configured in `js/groq-chatbot.js`

### 3. Test Locally
Open `index.html` in browser and test the chatbot

## 🌐 Deployment (Netlify)

### Step 1: Push to GitHub
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin YOUR_GITHUB_REPO_URL
git push -u origin main
```

### Step 2: Deploy on Netlify
1. Go to [Netlify.com](https://netlify.com)
2. Login with GitHub
3. Click "New Project" → Select your repository
4. Click "Deploy"
5. Done! Your site is live 🚀

### Step 3: Environment Variables (Optional)
If you want to use environment variables:
1. Go to Netlify Dashboard → Site Settings → Environment Variables
2. Add: `GROQ_API_KEY` = `your_api_key`
3. Redeploy

## 📞 Contact Information

- **Email**: contact@adsvancemedia.com
- **Phone**: +44 7491 116650 / +44 7401 116650
- **Address**: 12 Windsor View, Dewsbury, WF12 7SS, UK
- **Website**: https://adsvancemedia.netlify.app/

## 🤖 Chatbot Capabilities

The AI chatbot can:
- Answer questions about services, team, and company
- Understand client needs through smart questions
- Suggest appropriate solutions
- Generate professional proposals
- Direct pricing inquiries to the sales team
- Maintain conversation context for natural dialogue

## 📝 Important Notes

- `.env` file is in `.gitignore` (won't be pushed to GitHub)
- API key is embedded in code for simplicity (for production, use environment variables)
- Chatbot gives short, concise answers (2-4 lines)
- For pricing questions, chatbot provides team contact numbers

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **AI**: Groq API (Llama 3.3 70B)
- **Hosting**: Netlify
- **Version Control**: Git/GitHub

## 📄 License

©2026 ADSVANCE MEDIA. All rights reserved.

---

**Made with ❤️ by ADSVANCE MEDIA**
