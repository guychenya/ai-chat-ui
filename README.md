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

## 📅 Development Session Notes

### Session: November 20, 2025

#### Completed Features
1. **Modern UI Design**
   - Purple gradient background (135deg, #667eea to #764ba2)
   - Glassmorphism effects with backdrop blur
   - Smooth cubic-bezier animations
   - Rounded corners throughout (20px radius)
   - Floating llama icon animation
   - Hover effects on all interactive elements

2. **Chat History System**
   - Dark sidebar with chat list
   - LocalStorage persistence
   - Click to load previous conversations
   - Active chat highlighting
   - Delete with confirmation dialog
   - Auto-save on message completion

3. **Markdown Support**
   - Integrated marked.js library
   - Real-time markdown rendering for assistant responses
   - Support for bold, italic, lists, code blocks, etc.

4. **Export Functionality**
   - Export dropdown in header
   - Three formats: Markdown (.md), Text (.txt), PDF (.pdf)
   - Uses jsPDF for PDF generation
   - Preserves conversation structure

5. **File Upload**
   - Drag & drop support
   - Click to browse files
   - Accepts: .txt, .md, .json, .csv, .log
   - File badge with remove option
   - Content included in message (hidden from display)

6. **UX Improvements**
   - Typing indicator with bouncing dots
   - Smooth scroll to bottom
   - Input auto-resize
   - Hamburger menu to toggle sidebar
   - Protection against deleting active chats
   - Custom scrollbar styling

#### Technical Details
- **Frontend**: Pure HTML/CSS/JavaScript
- **Libraries**: marked.js (markdown), jsPDF (PDF export)
- **Deployment**: Docker + Nginx Alpine
- **Reverse Proxy**: Traefik
- **Storage**: Browser localStorage
- **API**: Ollama (phi3:mini model)

#### Known Issues & Solutions
- Browser cache: Requires hard refresh (Ctrl+Shift+R) to see updates
- Confirmation dialogs: May be blocked by browser - reset in site settings
- Typing indicators: Fixed with proper removal on response completion

#### Next Steps (Future Enhancements)
- [ ] Multi-model selection
- [ ] Image upload for multimodal models (llava, bakllava)
- [ ] Search within chat history
- [ ] Dark/light theme toggle
- [ ] Conversation sharing via URL
- [ ] Voice input support
- [ ] Code syntax highlighting
- [ ] Copy message button
- [ ] Edit sent messages
- [ ] Regenerate responses

#### Deployment Info
- **Server**: Contabo VPS (157.173.126.133)
- **Container**: cc8oosc000o488sgkw8sw048-165050552109
- **Network**: sgwckgsgg8cgwgckcc8gcosg
- **Coolify**: v4.0.0-beta.442

#### Git Commits Today
- Modern UI with gradients and animations
- Markdown rendering implementation
- Export to MD/TXT/PDF
- Chat history sidebar
- Drag & drop file upload
- Typing indicators
- Delete protection
- Rounded sidebar corners
- Comprehensive README

---

**Session End**: November 20, 2025, 21:09 UTC+2
**Status**: ✅ All features working and deployed
**Next Session**: Week of November 25, 2025
