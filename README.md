# Emo: AI-Powered Assistant & Email Automation 🤖📩

Emo is an intelligent hybrid assistant built with **n8n**. It combines conversational AI with practical automation to bridge the gap between chatting and taking action—specifically, drafting and sending personalized emails via Gmail.

## 🌟 Key Features
* **Conversational AI:** A friendly, responsive chat interface that understands user intent.
* **Smart Emailing:** Automatically drafts and sends emails (appreciation, updates, or greetings) based on chat context.
* **Memory Integration:** Remembers conversation flow to provide a seamless user experience.
* **Professional Logic:** Uses LLMs to ensure every email sent is polished and contextually accurate.

## 🛠️ Technical Tech Stack
* **Workflow Engine:** [n8n](https://n8n.io/)
* **AI Model:** OpenAI (GPT-4o/GPT-5-mini)
* **Memory:** LangChain Window Buffer Memory
* **Email Integration:** Gmail OAuth2 API
* **Nodes Used:** AI Agent, Chat Trigger, Gmail Tool, and Custom Memory.

## 🚀 How it Works
1. **Chat Input:** The user interacts with Emo via the n8n chat interface.
2. **Agent Reasoning:** The AI Agent decides if the user wants to simply chat or needs an email sent.
3. **Action:** If an email is requested, Emo uses the Gmail Tool to send the message directly to the recipient.
4. **Verification:** The system confirms the action back to the user in the chat.

## 📈 Business Use Case
The architecture behind Emo can be scaled for professional environments, such as:
* **Automated Lead Nurturing:** Following up with potential clients immediately after a chat interaction.
* **Customer Support:** Resolving issues via chat and automatically emailing a summary or ticket number to the user.
* **Internal Tools:** A corporate "Assistant" that handles scheduling or internal announcements via simple chat commands.
