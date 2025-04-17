# YouTube Video Summarizer with Gemini AI 🚀

[![Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://your-app.streamlit.app/)
[![Python](https://img.shields.io/badge/Python-3.9%2B-blue)](https://python.org)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

An AI-powered tool that converts YouTube video transcripts into concise summaries using Google's Gemini Pro model.

![Demo](https://via.placeholder.com/800x400.png?text=App+Demo+Preview)

## Features ✨
- 🔑 API-based transcript extraction
- 🤖 Gemini Pro AI summarization
- 🖼️ Automatic video thumbnail display
- 🚦 Error handling for invalid URLs
- 🔒 Secure API key management

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

## API Documentation 📚
```python
# Transcript extraction
def extract_transcript_details(url) -> str

# AI summarization
def generate_gemini_content(text, prompt) -> str
```

## Troubleshooting 🔧
| Error | Solution |
|-------|----------|
| API Key Invalid | Verify `.env` file format |
| No Transcript | Use videos with CC/subtitles |
| Rate Limits | Wait 60s between requests |

## Roadmap 🗺️
- [ ] Multi-language support
- [ ] Summary length control
- [ ] Export options (PDF/TXT)
- [ ] Video preview player

## Support ❤️
[Open an Issue](https://github.com/yourusername/youtube-summarizer/issues) |  
[![Buy Me Coffee](https://img.shields.io/badge/Support-Buy%20Coffee-yellow)](https://buymeacoffee.com)

## License 📄
MIT License - See [LICENSE](LICENSE) for details

---

**Note**: This project is not affiliated with YouTube or Google LLC.
```