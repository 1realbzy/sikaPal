<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>sikaPal - Personal Finance Assistant for Africa</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css">
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
        }
        .logo-container {
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 2rem;
        }
        code {
            background-color: #f1f1f1;
            padding: 2px 4px;
            border-radius: 4px;
            font-family: 'Courier New', Courier, monospace;
        }
        pre {
            background-color: #f1f1f1;
            padding: 1rem;
            border-radius: 6px;
            overflow-x: auto;
            margin: 1rem 0;
        }
        .badge {
            display: inline-block;
            margin-right: 5px;
        }
        .feature-card {
            border-left: 4px solid #10b981;
            padding-left: 1rem;
            margin-bottom: 1rem;
        }
        .tech-badge {
            background-color: #e5e7eb;
            color: #4b5563;
            padding: 0.3rem 0.6rem;
            border-radius: 9999px;
            font-size: 0.75rem;
            font-weight: 600;
            display: inline-block;
            margin: 0.25rem;
        }
    </style>
</head>
<body class="bg-white">

    <div class="container mx-auto px-4 py-8">
        <!-- Header -->
        <header class="text-center mb-8">
            <div class="logo-container">
                <h1 class="text-5xl font-bold text-green-600">
                    sika<span class="text-yellow-500">Pal</span>
                </h1>
            </div>
            <p class="text-xl text-gray-600 mt-4">A data-driven personal finance assistant for African markets</p>
            
            <div class="mt-4">
                <span class="badge bg-blue-100 text-blue-800 px-2 py-1 rounded-md">Version 0.1.0</span>
                <span class="badge bg-green-100 text-green-800 px-2 py-1 rounded-md">MIT License</span>
                <span class="badge bg-purple-100 text-purple-800 px-2 py-1 rounded-md">Python</span>
                <span class="badge bg-yellow-100 text-yellow-800 px-2 py-1 rounded-md">Twi Support</span>
            </div>
        </header>

        <!-- Introduction -->
        <section class="mb-10">
            <h2 class="text-2xl font-bold mb-4 text-gray-800 border-b pb-2">📊 Introduction</h2>
            <p class="mb-4">
                <strong>sikaPal</strong> (from Akan word "sika" meaning money) is an intelligent, privacy-focused personal finance platform designed specifically for Africans and emerging market users. It enables financial literacy through smart expense tracking, behavioral insights, and goal-driven recommendations.
            </p>
            <p class="mb-4">
                Unlike conventional finance apps, sikaPal is built with local cultural contexts in mind, offering support for Ghanaian languages (starting with Twi) and focusing on the specific financial challenges and opportunities in African markets.
            </p>
            <div class="bg-yellow-50 border-l-4 border-yellow-400 p-4 my-4">
                <p class="text-yellow-700">
                    <strong>Note:</strong> This project is under active development. We're shipping features fast and iterating based on user feedback.
                </p>
            </div>
        </section>

        <!-- Vision -->
        <section class="mb-10">
            <h2 class="text-2xl font-bold mb-4 text-gray-800 border-b pb-2">🔭 Vision</h2>
            <p class="mb-4">
                Our vision is to create a financial assistant that truly understands the unique challenges of personal finance management in African contexts. sikaPal aims to:
            </p>
            <ul class="list-disc pl-5 mb-4 space-y-2">
                <li>Democratize access to smart financial tools for all Ghanaians, regardless of financial literacy level</li>
                <li>Break language barriers by providing finance tools in local languages</li>
                <li>Utilize AI and data analysis to provide personalized financial guidance</li>
                <li>Help users build better financial habits through insights and actionable recommendations</li>
                <li>Create a privacy-focused alternative to traditional banking apps that often lack deep analytical capabilities</li>
            </ul>
        </section>

        <!-- Features -->
        <section class="mb-10">
            <h2 class="text-2xl font-bold mb-4 text-gray-800 border-b pb-2">✨ Core Features</h2>
            
            <div class="feature-card">
                <h3 class="text-xl font-semibold text-green-700">Expense Tracker</h3>
                <p>Input transactions manually, upload CSV files, parse bank SMS messages, or connect through APIs. All transactions are automatically categorized and labeled.</p>
            </div>
            
            <div class="feature-card">
                <h3 class="text-xl font-semibold text-green-700">Budget Assistant</h3>
                <p>Set financial goals, provide income information, and receive auto-suggested budgets. Get alerts when approaching budget limits or overspending.</p>
            </div>
            
            <div class="feature-card">
                <h3 class="text-xl font-semibold text-green-700">Insight Generator</h3>
                <p>Receive AI-generated summaries of your financial behavior on a weekly and monthly basis. Understand spending patterns and identify areas for improvement.</p>
            </div>
            
            <div class="feature-card">
                <h3 class="text-xl font-semibold text-green-700">Goal Tracker</h3>
                <p>Set and visualize short- and long-term savings goals. Get feedback on progress and adaptive suggestions to help you reach your targets.</p>
            </div>
            
            <div class="feature-card">
                <h3 class="text-xl font-semibold text-green-700">Chatbot Interface</h3>
                <p>Ask questions about your finances in natural language and get instant answers. For example: "How much did I spend on transport this month?"</p>
            </div>
            
            <div class="feature-card">
                <h3 class="text-xl font-semibold text-green-700">Local Language Support</h3>
                <p>Interact with sikaPal in Twi (starting language) with plans to expand to other Ghanaian and African languages. Powered by GhanaNLP translation technology.</p>
            </div>
        </section>

        <!-- Tech Stack -->
        <section class="mb-10">
            <h2 class="text-2xl font-bold mb-4 text-gray-800 border-b pb-2">🛠️ Technology Stack</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-4">
                <div>
                    <h3 class="text-xl font-semibold mb-2 text-gray-700">Backend</h3>
                    <div>
                        <span class="tech-badge">Python</span>
                        <span class="tech-badge">FastAPI</span>
                        <span class="tech-badge">SQLite (dev)</span>
                        <span class="tech-badge">PostgreSQL (prod)</span>
                        <span class="tech-badge">LangChain</span>
                    </div>
                </div>
                
                <div>
                    <h3 class="text-xl font-semibold mb-2 text-gray-700">AI & NLP</h3>
                    <div>
                        <span class="tech-badge">OpenAI GPT-4</span>
                        <span class="tech-badge">LlamaIndex</span>
                        <span class="tech-badge">GhanaNLP</span>
                        <span class="tech-badge">ABENA (Twi BERT)</span>
                        <span class="tech-badge">Kasa (Translation)</span>
                    </div>
                </div>
                
                <div>
                    <h3 class="text-xl font-semibold mb-2 text-gray-700">Frontend</h3>
                    <div>
                        <span class="tech-badge">Streamlit</span>
                        <span class="tech-badge">React (future)</span>
                        <span class="tech-badge">Plotly</span>
                        <span class="tech-badge">Matplotlib</span>
                    </div>
                </div>
                
                <div>
                    <h3 class="text-xl font-semibold mb-2 text-gray-700">DevOps</h3>
                    <div>
                        <span class="tech-badge">Git</span>
                        <span class="tech-badge">GitHub</span>
                        <span class="tech-badge">Loguru</span>
                        <span class="tech-badge">Docker (future)</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- Project Structure -->
        <section class="mb-10">
            <h2 class="text-2xl font-bold mb-4 text-gray-800 border-b pb-2">📁 Project Structure</h2>
            <pre><code>sikapal/
├── backend/
│   ├── main.py                 # FastAPI entrypoint
│   ├── models/                 # Budget, Transaction, Goal, User models
│   ├── services/               # BudgetCalc, InsightGen, Categorizer
│   ├── routes/                 # API endpoints
│   ├── utils/                  # Data loaders, loggers, parsers
│   ├── agent/                  # LLM prompt templates + interaction logic
│   └── translation/            # NLP translation services integration
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── synthetic/              # Initial testing data
│
├── notebooks/
│   └── exploratory.ipynb       # EDA, initial modeling
│
├── frontend/
│   └── app.py                  # Streamlit or React entry
│
├── tests/
│   └── test_core.py
│
├── .env.example
├── requirements.txt
├── README.md
└── roadmap.md</code></pre>
        </section>

        <!-- Getting Started -->
        <section class="mb-10">
            <h2 class="text-2xl font-bold mb-4 text-gray-800 border-b pb-2">🚀 Getting Started</h2>
            
            <h3 class="text-xl font-semibold mb-2 text-gray-700">Prerequisites</h3>
            <ul class="list-disc pl-5 mb-4">
                <li>Python 3.9+</li>
                <li>Git</li>
                <li>OpenAI API key (for GPT-4 functionality)</li>
            </ul>
            
            <h3 class="text-xl font-semibold mb-2 text-gray-700">Installation</h3>
            <pre><code># Clone the repository
git clone https://github.com/1realbzy/sikapal.git
cd sikapal

# Create and activate a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Set up environment variables
cp .env.example .env
# Edit .env file with your API keys and configuration

# Initialize the database
python backend/utils/initialize_db.py

# Run the development server
python backend/main.py</code></pre>
        </section>

        <!-- Language Support -->
        <section class="mb-10">
            <h2 class="text-2xl font-bold mb-4 text-gray-800 border-b pb-2">🌍 Language Support</h2>
            
            <p class="mb-4">
                sikaPal is designed with multilingual support in mind, starting with English and Twi (Akan) for the Ghanaian market.
            </p>
            
            <h3 class="text-xl font-semibold mb-2 text-gray-700">Current Implementation</h3>
            <ul class="list-disc pl-5 mb-4">
                <li>Primary interface in English</li>
                <li>Twi translations for core features and financial insights</li>
                <li>Integration with GhanaNLP Translation API</li>
                <li>Offline translation capabilities via Kasa library</li>
            </ul>
            
            <h3 class="text-xl font-semibold mb-2 text-gray-700">Planned Expansion</h3>
            <ul class="list-disc pl-5 mb-4">
                <li>Additional Ghanaian languages (Ga, Ewe, Dagbani)</li>
                <li>Other major African languages based on user demand</li>
                <li>Full localization of all app content and insights</li>
            </ul>
            
            <div class="bg-blue-50 border-l-4 border-blue-400 p-4 my-4">
                <p class="text-blue-700">
                    <strong>Technical Note:</strong> We leverage the GhanaNLP ecosystem, including ABENA (BERT for Twi) and Kasa (translation library) for high-quality language processing.
                </p>
            </div>
        </section>

        <!-- Contributing -->
        <section class="mb-10">
            <h2 class="text-2xl font-bold mb-4 text-gray-800 border-b pb-2">🤝 Contributing</h2>
            
            <p class="mb-4">
                We welcome contributions from developers, financial experts, language specialists, and users! Here's how to get involved:
            </p>
            
            <h3 class="text-xl font-semibold mb-2 text-gray-700">Contribution Process</h3>
            <ol class="list-decimal pl-5 mb-4 space-y-2">
                <li>Fork the repository</li>
                <li>Create a new branch (<code>git checkout -b feature/amazing-feature</code>)</li>
                <li>Make your changes</li>
                <li>Commit your changes (<code>git commit -m 'feat: Add some amazing feature'</code>)</li>
                <li>Push to the branch (<code>git push origin feature/amazing-feature</code>)</li>
                <li>Open a Pull Request</li>
            </ol>
            
            <h3 class="text-xl font-semibold mb-2 text-gray-700">Development Guidelines</h3>
            <ul class="list-disc pl-5 mb-4 space-y-2">
                <li>Follow PEP 8 style guidelines for Python code</li>
                <li>Write unit tests for new features</li>
                <li>Document all functions, classes, and modules</li>
                <li>Use clear, descriptive commit messages</li>
                <li>Keep pull requests focused on single changes</li>
            </ul>
            
            <h3 class="text-xl font-semibold mb-2 text-gray-700">Areas We Need Help With</h3>
            <ul class="list-disc pl-5 mb-4 space-y-2">
                <li>Language translations and culturally-appropriate financial terms</li>
                <li>Financial modeling and analytics</li>
                <li>UI/UX improvements</li>
                <li>Documentation and tutorials</li>
                <li>Testing across different devices and scenarios</li>
            </ul>
        </section>

        <!-- Roadmap -->
        <section class="mb-10">
            <h2 class="text-2xl font-bold mb-4 text-gray-800 border-b pb-2">🗺️ Roadmap</h2>
            
            <h3 class="text-xl font-semibold mb-2 text-gray-700">Phase 1: Foundation (Current)</h3>
            <ul class="list-disc pl-5 mb-4 space-y-2">
                <li>Basic expense tracking and categorization</li>
                <li>Simple budget creation and management</li>
                <li>Initial Twi language support</li>
                <li>Web-based interface with Streamlit</li>
            </ul>
            
            <h3 class="text-xl font-semibold mb-2 text-gray-700">Phase 2: Enhancement</h3>
            <ul class="list-disc pl-5 mb-4 space-y-2">
                <li>Advanced financial insights and recommendations</li>
                <li>SMS parsing for transaction tracking</li>
                <li>Expanded language support</li>
                <li>Improved visualization and reporting</li>
            </ul>
            
            <h3 class="text-xl font-semibold mb-2 text-gray-700">Phase 3: Expansion</h3>
            <ul class="list-disc pl-5 mb-4 space-y-2">
                <li>Bank API integrations</li>
                <li>Mobile application development</li>
                <li>Peer-to-peer payment tracking</li>
                <li>Community features and knowledge sharing</li>
            </ul>
        </section>

        <!-- License -->
        <section class="mb-10">
            <h2 class="text-2xl font-bold mb-4 text-gray-800 border-b pb-2">📝 License</h2>
            <p class="mb-4">
                This project is licensed under the MIT License - see the LICENSE file for details.
            </p>
        </section>

        <!-- Acknowledgements -->
        <section class="mb-10">
            <h2 class="text-2xl font-bold mb-4 text-gray-800 border-b pb-2">🙏 Acknowledgements</h2>
            <ul class="list-disc pl-5 mb-4 space-y-2">
                <li><a href="https://github.com/ghananlp" class="text-blue-600 hover:underline">GhanaNLP</a> - For their groundbreaking work on NLP for Ghanaian languages</li>
                <li><a href="https://github.com/GhanaNLP/ABENA" class="text-blue-600 hover:underline">ABENA</a> - BERT models for Twi language processing</li>
                <li><a href="https://github.com/GhanaNLP/kasa" class="text-blue-600 hover:underline">Kasa</a> - Translation library for Ghanaian languages</li>
                <li>OpenAI - For GPT-4 technology powering our insights</li>
                <li>All our early testers and contributors</li>
            </ul>
        </section>

        <!-- Contact -->
        <section class="mb-10">
            <h2 class="text-2xl font-bold mb-4 text-gray-800 border-b pb-2">📬 Contact</h2>
            <p class="mb-4">
                Have questions or want to get involved? Reach out through:
            </p>
            <ul class="list-disc pl-5 mb-4 space-y-2">
                <li>GitHub Issues: <a href="https://github.com/1realbzy/sikapal/issues" class="text-blue-600 hover:underline">https://github.com/1realbzy/sikapal/issues</a></li>
                <li>Project Discussions: <a href="https://github.com/1realbzy/sikapal/discussions" class="text-blue-600 hover:underline">https://github.com/1realbzy/sikapal/discussions</a></li>
            </ul>
        </section>

        <!-- Footer -->
        <footer class="text-center text-gray-500 text-sm mt-16 pt-4 border-t">
            <p>sikaPal - Smart financial management for everyone</p>
            <p class="mt-2">© 2024 sikaPal Project Contributors</p>
        </footer>
    </div>

</body>
</html>
