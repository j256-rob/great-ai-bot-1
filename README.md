 Great AI Bot

 About the Project
Great AI Bot is an intelligent chatbot designed to help users learn about and purchase digital products (eBooks). It automates sales, customer support, and marketing, making the buying experience seamless.
 Features
**Product Introduction:** Introduces available products to users.
**Sales Funnel Guidance:** Helps users through the buying process.
**Product Q&A:** Answers general and detailed product-related questions.
 **Gumroad Integration:** Processes payments automatically.
**Command Handling:** Supports commands like `/help`, `/reset`, `/feedback`, and `/updates`.
**Mood Detection:** Responds based on the user's emotions.
 **User Memory:** Remembers the user's name for a personalized experience.
 Tech Stack
- **Programming Language:** Python 🐍
- **Framework:** Flask (for webhook handling)
- **Bot API:** Telegram Bot API
- **Database:** SQLite / PostgreSQL (Optional)
- **Hosting:** Render

Installation
Clone the Repository**
```bash
git clone https://github.com/j256-rob/great-ai-bot.git
cd great-ai-bot
```
 Install Dependencies**
```bash
pip install -r requirements.txt
```
 Set Up Environment Variables**
Create a `.env` file in the root folder and add:
```ini
BOT_TOKEN=your-telegram-bot-token
GUMROAD_WEBHOOK_SECRET=your-secret-key
OPENAI_API_KEY=your-openai-api-key
```
 Run the Bot Locally**
```bash
python bot.py
```

Deploying on Render
 Push Code to GitHub**
```bash
git add .
git commit -m "Initial commit"
git push origin main
```

 Deploy to Render**
1. Go to [Render.com](https://render.com/)
2. Click **"New Web Service"**
3. Select **"Deploy from GitHub"**
4. Choose **"great-ai-bot"** repository
5. Set environment variables in **Render Dashboard → Environment**
6. Click **"Deploy"**
**Your bot is now live!**

 Next Steps
- [ ] Add AI-driven upselling & cross-selling
- [ ] Integrate WhatsApp & website chat support
- [ ] Implement analytics for user engagement

 Contributing
Pull requests are welcome! Open an issue for suggestions or improvements.

## 📄 License
This project is licensed under the **MIT License**.

---
 **Built with passion by Jagen Robinson** 

