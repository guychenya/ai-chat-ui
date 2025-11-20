# AI Chat UI

A modern, feature-rich chat interface for interacting with AI models via Ollama.

## 🌟 Features

- ✨ **Modern UI** - Beautiful gradient design with smooth animations
- 💬 **Chat History** - Persistent chat storage with sidebar navigation
- 📝 **Markdown Support** - Rich text rendering for assistant responses
- 📥 **Export Options** - Export conversations to Markdown, Text, or PDF
- 📎 **File Upload** - Drag & drop or click to attach text files
- 🎨 **Typing Indicators** - Animated dots while AI is thinking
- 🗑️ **Delete Chats** - Remove individual conversations with confirmation
- 🔒 **Smart Protection** - Prevents deletion during active generation
- 💾 **Auto-save** - Conversations saved to browser localStorage

## 🚀 Live Demo

**URL:** http://cc8oosc000o488sgkw8sw048.157.173.126.133.sslip.io

## 🛠️ Tech Stack

- Pure HTML/CSS/JavaScript
- [Marked.js](https://marked.js.org/) - Markdown parsing
- [jsPDF](https://github.com/parallax/jsPDF) - PDF generation
- Nginx Alpine - Web server
- Docker - Containerization

## 📦 Deployment

Deployed via Coolify on Contabo VPS:
- **Server:** 157.173.126.133
- **API Backend:** Ollama (phi3:mini model)
- **Reverse Proxy:** Traefik

## 🎯 API Configuration

- **API URL:** http://157.173.126.133:8888
- **Endpoint:** /api/chat
- **Model:** phi3:mini

## 📝 Recent Updates

### November 20, 2025
- Added modern gradient UI with animations
- Implemented markdown rendering
- Added export to MD/TXT/PDF
- Created chat history sidebar
- Added drag & drop file upload
- Implemented typing indicators
- Added delete protection during generation
- Added footer attribution

## 👨‍💻 Author

**Guy Chenya**

Made with ❤️ - For Training Purposes Only

## 📄 License

This project is for educational and training purposes.

## 🔮 Future Enhancements

- Multi-model support
- Image upload for multimodal models
- Search within chat history
- Dark/light theme toggle
- Conversation sharing
- Voice input support
