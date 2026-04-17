# NexChat — How to Run & Use

## ✅ SIMPLEST WAY (No installation needed)

1. Unzip the `nexchat.zip` file
2. Open the `chatapp` folder
3. Double-click `index.html` — it opens directly in your browser
4. That's it! No server, no npm, no setup required.

---

## 🚀 HOW TO USE

### Step 1 — Create your account
- Click **"Create Account"**
- Pick an emoji avatar and a profile color
- Enter your Display Name, a unique @username, a bio/status, and a password
- Click **"Create Account →"**
- You'll land directly on the chat screen ✅

### Step 2 — Chat with the AI (immediately available)
- **NexChat AI** opens automatically on your first login
- Type anything and the AI will respond
- The AI uses Claude API when online, and has a built-in fallback when offline

### Step 3 — Chat with other users
- To test user-to-user chat, you need **two accounts in the same browser**
- Open the app, create Account A, then logout
- Create Account B
- Now login as Account A → click the **chat icon** (top of sidebar) → search for Account B → start chatting
- Then logout and login as Account B to reply back

> **Why same browser?** This app stores data in your browser's localStorage. Both users must be on the same browser/device for the accounts to "see" each other. For real multi-device chat, a backend server would be needed.

---

## 🗺️ FEATURES

| Feature | How to access |
|---|---|
| Create account | Welcome screen → Create Account |
| Login | Welcome screen → Sign In |
| Quick login | Sign In page → tap any account shown |
| Chat with AI | Tap "NexChat AI" in the sidebar |
| Chat with a user | Click 💬 icon → search and tap a user |
| Edit your profile | Tap your avatar/name in the top-left |
| View contact info | Tap the name/avatar in the chat topbar |
| Clear a chat | Tap the trash icon in the chat topbar |
| Search chats | Use the search bar in the sidebar |
| Filter by Unread / AI | Tap the tabs below the search bar |
| Emoji in messages | Tap the 😊 button next to the input |
| Logout | Tap the → icon in the top-right of the sidebar |

---

## 📁 FILES

```
chatapp/
└── index.html    ← The entire app (single file, self-contained)
```

---

## 🔧 TROUBLESHOOTING

**After login, nothing shows / blank screen?**
→ Make sure you're opening `index.html` from a **browser** (Chrome, Firefox, Edge, Safari), not a text editor.

**localStorage not working?**
→ Don't open from inside a zip file. Extract first, then open.

**AI chatbot not responding intelligently?**
→ The Claude API requires an internet connection. Offline, a built-in response engine handles basic conversation.

**Can't find another user to chat with?**
→ Both accounts must be created in the same browser on the same device. Try: logout → create second account → logout → login as first account → search for second account.
