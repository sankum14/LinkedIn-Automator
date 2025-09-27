#h3 LinkedIn News Post Generator with Groq + Colab

This project automates the process of turning the latest Yahoo Finance news into a scroll-stopping LinkedIn post that sounds human, smart, and engaging — not like a robot.

It uses:

BeautifulSoup + Requests → Scrapes trending Yahoo Finance articles.

Groq SDK (Llama-3 70B) → Generates investor-style, interaction-driven LinkedIn posts.

Google Colab → For easy development and deployment.

I’ve personally tested this workflow and reached 100,000+ views on LinkedIn with the generated posts.

🚀 Features

🔎 Scrapes the latest finance news from Yahoo.

✍️ Generates LinkedIn posts with strong hooks, insights, and hashtags.

🤖 Uses Groq’s blazing-fast inference with Llama-3.

🧑‍💻 Fully reproducible in Google Colab.

📂 Project Structure
├── linkedin_news_generator.ipynb   # Main Colab notebook
├── requirements.txt                 # Python dependencies
└── README.md                        # Project documentation

🛠️ Installation & Setup

Clone this repo:

git clone https://github.com/your-username/linkedin-news-generator.git
cd linkedin-news-generator


Install dependencies (in Colab or locally):

pip install requests beautifulsoup4 groq


Set up your Groq API key:

from groq import Groq
client = Groq(api_key="your_api_key_here")

▶️ Usage

Run the notebook in Google Colab.

It will:

Scrape the latest Yahoo Finance article.

Generate a polished LinkedIn post.

Print it in your Colab output.

Example output:

📢 LinkedIn Post:

**Hook:** "Tax reform just got a whole lot more interesting..."

When it comes to the proposed tax bill, one thing is clear: ...
...
#TaxReform #EconomicOutlook #InvestmentStrategies


Copy → Paste → Post on LinkedIn ✅

📊 Results

Generated posts have already reached 100,000+ views on LinkedIn.

Consistently produces professional, human-like insights.
