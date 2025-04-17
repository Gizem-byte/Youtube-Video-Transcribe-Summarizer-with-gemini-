# YouTube Video Summarizer with Gemini AI 🚀

[![Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://your-app.streamlit.app/)
[![Python](https://img.shields.io/badge/Python-3.12%2B-blue)](https://python.org)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

An AI-powered tool that converts YouTube video transcripts into concise summaries using Google's Gemini Pro model.


## Features ✨
- 🔑 API-based transcript extraction
- 🤖 Gemini Pro AI summarization
- 🖼️ Automatic video thumbnail display
- 🚦 Error handling for invalid URLs
- 🔒 Secure API key management

### **Coming Soon**  
🛠️ Next Priority Features:
- Video length detection ⏱️  
- Summary length customization (50/100/250 words)  
- Multi-language support 🇪🇸🇫🇷🇩🇪  

### **Future Ideas**  
💡 Long-Term Goals:
- Chrome extension 🧩  
- Mobile app version 📱  
- Speaker identification in transcripts 🗣️  

## Installation 📦

### Prerequisites
- Python 3.12+
- Google API Key

### Quick Start
```bash
git clone https://github.com/yourusername/youtube-summarizer.git
pip install -r requirements.txt
```

## Configuration ⚙️
1. Create `.env` file:
```env
GOOGLE_API_KEY=your_actual_key_here
```

## Usage 🖥️
```bash
streamlit run app.py
```
1. Enter YouTube URL (e.g., `https://youtu.be/VIDEO_ID`)
2. Click "Get Detailed Notes"
3. View AI-generated summary


## Troubleshooting 🔧
| Error | Solution |
|-------|----------|
| API Key Invalid | Verify `.env` file format |
| No Transcript | Use videos with CC/subtitles |
| Rate Limits | Wait 60s between requests |


## License 📄
MIT License - See [LICENSE](LICENSE) for details

---

**Note**: This project is not affiliated with YouTube or Google LLC.