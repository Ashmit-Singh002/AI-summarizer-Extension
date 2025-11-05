# 🧠 AI Article Summarizer Chrome Extension

A simple yet powerful **Chrome Extension** that uses **Google Gemini API** to summarize online articles in a clean, concise format — right from your browser tab!

---

## 🚀 Features
- 📰 Extracts article text directly from the active web page  
- 🤖 Generates short, medium, or detailed summaries using **Gemini AI**  
- 🔒 Stores API key securely using `chrome.storage.sync`  
- ⚙️ Easy-to-use popup interface  
- 🌐 Works on most websites and blogs

---

## 🧩 Tech Stack
- **HTML, CSS, JavaScript**
- **Manifest V3**
- **Google Gemini API**
- **Chrome Storage API**

---

## 🧠 How It Works
1. The user clicks the extension icon on any web page.  
2. The **content script** extracts article text from the current tab.  
3. The **popup** lets the user choose a summary length or style.  
4. The text is sent securely to **Gemini API**, which returns a summarized version.  
5. The summary is displayed instantly in the popup UI.

---## 🔐 API Key Management
- Your **Gemini API key** is stored securely using `chrome.storage.sync`.  
- This ensures it is **not hardcoded** or visible in your source code.  
- You can set it from the popup UI or through developer tools (optional).

---

## 🧭 Setup Instructions

### 1. Get a Gemini API Key
- Visit [Google AI Studio](https://aistudio.google.com/app/apikey)  
- Create or copy your **Gemini API Key**

### 2. Clone the Repository
```bash
git clone https://github.com/your-username/ai-article-summarizer-extension.git
cd ai-article-summarizer-extension
