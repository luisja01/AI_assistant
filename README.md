## AI Virtual Assistant with Web Scraping & Ollama

An experimental project where I built a virtual assistant that:
- **Scrapes** product information from a demo e-commerce site
- **Indexes** results locally for fast lookups
- Uses **Ollama** to generate natural-language answers, informed by relevant product data

### Key Features
- **Automated Web Scraping** with Python & BeautifulSoup  
- **Local Search** (simple keyword or potential embedding-based matching)  
- **Prompt Engineering** to constrain AI responses to the scraped context  
- **Fallbacks** for questions lacking sufficient data

### Usage
1. Run `ollama serve` locally  
2. Execute `python main.py` to start the console-based assistant  
3. Ask questions about products, and watch the AI respond with context-relevant info!

> **Note**: Built for demo/learning; scrape responsibly & follow site ToS.
