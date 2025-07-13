# NexAI – AI Assistant with Login

NexAI is a smart, cartoon-style AI chatbot with a secure email/password login system using Supabase. After logging in, users are redirected to a beautiful chat interface powered by the Groq API (LLaMA 3 model).

---

## 🔐 Features

- Secure sign up & login (email + password)
- Email verification after signup
- Automatic redirect to chatbot after login
- Integrated with Groq AI API (LLaMA 3)
- Fully responsive, modern dark-themed UI
- Uses Material Icons for visual styling

---

## 🧰 Tech Used

- **Frontend**: HTML, CSS, JavaScript
- **Auth**: Supabase (Email/Password)
- **AI Backend**: Groq API (llama3-70b-8192)
- **Icons**: Google Material Icons
- **Hosting**: GitHub Pages (or any static hosting)

---

## 🚀 Getting Started

### 1. Clone This Repository

```bash
git clone https://github.com/your-username/nexai-chatbot.git
cd nexai-chatbot
```

### 2. Setup Supabase

- Create an account at [https://supabase.com](https://supabase.com)
- Create a new project
- Enable **Email Auth** (with password)
- Copy your `supabaseUrl` and `anon` key from Project Settings → API
- Paste them in both `auth.html` and `chat.html` where required:

```js
const supabaseUrl = 'https://your-project.supabase.co';
const supabaseKey = 'your-anon-key';
```

---

### 3. Setup Groq API

- Go to [https://console.groq.com](https://console.groq.com)
- Create a new API key
- Replace in `chat.html`:

```js
const API_KEY = "your_groq_api_key";
```

---

## 📁 Files

```
├── index.html       # Login / Signup Page
├── chat.html        # Chat Interface
├── style.css        # Optional shared styles
├── README.md        # This file
```

---

## 📌 Notes

- After sign-up, the user receives a verification email.
- Once verified, they can log in directly from the same page.
- No need to re-enter via email link every time (only for first verification).

---

## 📜 License

This project is open-source under the MIT License.

---

## 🙌 Author

Created by [@yourname](https://github.com/your-username) – KHUB Project 2025
