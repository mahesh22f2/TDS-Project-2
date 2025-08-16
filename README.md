⚡ Data Analyst Agent

AI-powered data companion for instant insights & visualizations.

📌 Overview

Upload your dataset + questions → get AI-driven summaries, charts, and reports.
Supports CSV, Excel, JSON, Parquet, TXT.

✨ Features

🤖 AI insights (Google Generative AI)

📊 Visuals with Seaborn & Matplotlib

🌍 Web scraping support

🔄 Batch question processing

⚡ Fast & beginner-friendly

🚀 Quick Start
git clone https://github.com/your-username/data-analyst-agent.git
cd data-analyst-agent
pip install -r requirements.txt


Create .env file:

GEMINI_API_KEY=your_google_api_key
LLM_TIMEOUT_SECONDS=240


Run app:

python -m uvicorn app:app --reload


Open: http://localhost:8000

🧑‍💻 Usage

Write queries in a .txt file

Upload dataset + queries

Get instant insights & charts

🛠 Tech Stack

FastAPI · LangChain · Google Generative AI · Pandas · NumPy · Seaborn · Matplotlib

📜 License

MIT — free for personal & commercial use.
