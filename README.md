

```markdown
NexaBot – WhatsApp GPT Chatbot

Description
NexaBot is an AI-powered WhatsApp chatbot using OpenAI's GPT-3.5 and the WhatsApp Cloud API. It automatically responds to WhatsApp messages with intelligent ChatGPT replies. Built with Node.js and Express for fast, reliable performance.

---

Features
- AI-powered replies using OpenAI GPT-3.5  
- Integration with WhatsApp Cloud API  
- Simple Node.js backend with Express.js  
- Easy to deploy and customize  
- Supports real-time chat on WhatsApp

---

Tech Stack
- Node.js  
- Express.js  
- OpenAI GPT-3.5 API  
- WhatsApp Cloud API  
- axios, dotenv, body-parser

---

Setup & Installation

1. *Clone the repo*
   ```bash
   git clone https://github.com/yourusername/nexabot-whatsapp.git
   cd nexabot-whatsapp
   ```

2. *Install dependencies*
   ```bash
   npm install
   ```

3. *Create `.env` file* and add:
   ```
   OPENAI_API_KEY=your-openai-api-key
   WHATSAPP_TOKEN=your-whatsapp-cloud-api-token
   PHONE_NUMBER_ID=your-whatsapp-phone-number-id
   VERIFY_TOKEN=your-verify-token
   ```

4. *Run the app*
   ```bash
   node app.js
   ```

5. *Expose your local server* (for testing) using ngrok:
   ```bash
   ngrok http 3000
   ```
[31/12, 01:19] Chat Gpt: 6. *Set up webhook* in your Meta Developer Portal with:
   - Webhook URL: `https://your-ngrok-url/webhook`
   - Verify token: same as in `.env`

7. *Start chatting* on WhatsApp — NexaBot will reply!

---

Usage

Send any message to your WhatsApp number connected with the bot, and NexaBot will respond using ChatGPT’s intelligence.

---

License

MIT © Alfred Bentum 

---

Contributing

Feel free to submit issues or pull requests. Contributions are welcome!

---

Contact

Created by [Alfred Bentum] - [bentumalfred2008@gmail.com]
```
