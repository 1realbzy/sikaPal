sikaPal - Personal Finance Assistant for Africa
🔵 Version 0.1.0 | 🟢 MIT License | 🟣 Python | 🟡 Twi Support

A data-driven personal finance assistant for African markets

📊 Introduction

sikaPal (from the Akan word "sika" meaning money) is an intelligent, privacy-focused personal finance platform designed specifically for Africans and emerging market users. It enables financial literacy through smart expense tracking, behavioral insights, and goal-driven recommendations.

Unlike conventional finance apps, sikaPal is built with local cultural contexts in mind. It offers support for Ghanaian languages (starting with Twi) and focuses on the specific financial challenges and opportunities in African markets.

Note: This project is under active development. We’re shipping features fast and iterating based on user feedback.

🛠️ Technology Stack

Backend
Python
FastAPI
SQLite (dev)
PostgreSQL (prod)
LangChain
AI & NLP
Grok 3 (xAI) - Free API for financial insights and natural language processing
LlamaIndex
GhanaNLP
ABENA (Twi BERT)
Kasa (Translation)
Frontend
Streamlit
React (future)
Plotly
Matplotlib
DevOps
Git
GitHub
Loguru
Docker (future)

🚀 Getting Started

Prerequisites
Python 3.9+
Git
xAI API key (for Grok 3 functionality, free with usage quotas)
Installation
bash

Copy
# Clone the repository
git clone https://github.com/1realbzy/sikapal.git
cd sikapal

# Create and activate a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Set up environment variables
cp .env.example .env
# Edit .env file with your xAI API key and configuration

# Initialize the database
python backend/utils/initialize_db.py

# Run the development server
python backend/main.py
🌍 Language Support
sikaPal is designed with multilingual support in mind. It starts with English and Twi (Akan) for the Ghanaian market.

Current Implementation
Primary interface in English.
Twi translations for core features and financial insights.
Integration with GhanaNLP Translation API.
Offline translation capabilities via Kasa library.
Grok 3 powers natural language queries and insights, with Twi support via GhanaNLP integration.
Planned Expansion
Additional Ghanaian languages (Ga, Ewe, Dagbani).
Other major African languages based on user demand.
Full localization of all app content and insights.
Technical Note: We leverage the GhanaNLP ecosystem, including ABENA (BERT for Twi) and Kasa (translation library), alongside Grok 3 for high-quality language processing and financial insights.

🤝 Contributing

We welcome contributions from developers, financial experts, language specialists, and users. Here’s how to get involved:

Contribution Process
Fork the repository.
Create a new branch (git checkout -b feature/amazing-feature).
Make your changes.
Commit your changes (git commit -m 'feat: Add some amazing feature').
Push to the branch (git push origin feature/amazing-feature).
Open a Pull Request.
Development Guidelines
Follow PEP 8 style guidelines for Python code.
Write unit tests for new features.
Document all functions, classes, and modules.
Use clear, descriptive commit messages.
Keep pull requests focused on single changes.
Ensure compatibility with Grok 3 API for AI features.
Areas We Need Help With
Language translations and culturally appropriate financial terms.
Financial modeling and analytics.
UI/UX improvements.
Documentation and tutorials.
Testing across different devices and scenarios.

🙏 Acknowledgements

GhanaNLP - For their groundbreaking work on NLP for Ghanaian languages.
ABENA - BERT models for Twi language processing.
Kasa - Translation library for Ghanaian languages.
xAI - For Grok 3 technology powering our insights.
All our early testers and contributors.

📬 Contact

Have questions or want to get involved? Reach out through:

GitHub Issues: https://github.com/1realbzy/sikapal/issues
Project Discussions: https://github.com/1realbzy/sikapal/discussions
sikaPal - Smart financial management for everyone.

© 2024 sikaPal Project Contributors.
