# DocuLingo

A free Telegram bot for translating documents (PDF, EPUB, DOCX) while preserving their original structure and formatting.

## Features

- **Multi-format Support**: Translate PDFs, Word documents (DOCX), and EPUBs
- **Structure Preservation**: Maintains original document layout and formatting
- **Multiple Languages**: Support for numerous language pairs
- **User-friendly Interface**: Simple Telegram bot commands and inline buttons
- **Progress Tracking**: Real-time translation progress updates
- **Free to Use**: Built entirely on free and open-source components

## Technology Stack

- **Bot Framework**: python-telegram-bot
- **Document Processing**:
  - PyMuPDF (fitz) for PDF handling
  - python-docx for Word documents
  - ebooklib for EPUB processing
- **Translation**:
  - LibreTranslate (primary, open-source)
  - Argos Translate (offline fallback)
- **Infrastructure**:
  - Free/low-cost hosting
  - SQLite for user preferences
  - File system for temporary storage

## Project Status

🚧 **Under Development** 🚧

## Getting Started

### Prerequisites

- Python 3.8+
- Telegram Bot API token (from BotFather)

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/doculingo.git
cd doculingo

# Set up virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Set up environment variables
cp .env.example .env
# Edit .env with your configuration
