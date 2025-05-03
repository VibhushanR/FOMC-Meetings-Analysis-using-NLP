# 🧠 FOMC Meetings Analysis Using NLP

## 📌 Business Problem
Federal Open Market Committee (FOMC) meeting minutes are dense, formal documents crucial for interpreting the U.S. Federal Reserve’s monetary policy. However, manually analyzing them is time-consuming and limits real-time insight. Investors, analysts, and institutions need fast, automated ways to extract sentiment, themes, and shifts in policy tone. This project uses Natural Language Processing (NLP) to bridge that gap and uncover actionable insights from FOMC communications.

## 🗃️ Dataset Overview
- **Corpus 1:** 26 FOMC meeting minutes (Jan 2022 – Mar 2025)  
- **Corpus 2:** ~19,000 Guardian news articles on the U.S. economy (same period)

Each document was cleaned, labeled by date, and analyzed for:
- Sentiment
- Word frequency
- Topic modeling (LDA)
- Text complexity
- Co-occurrence networks

## 🔍 Key Analyses

### 🧾 Sentiment Analysis
- **FOMC Minutes:** Neutral to mildly positive tone (~0.1 average compound score)  
  → Reflects formal, cautious communication style  
- **Guardian Media:** Broad sentiment spread, often extreme  
  → Reflects emotional and polarized framing in public discourse

### 🧠 Topic Modeling (LDA)
**FOMC Topics:**  
- Inflation, interest rates, Fed operations, risk assessment, international markets  

**Media Topics:**  
- Russia–Ukraine war, political leaders (Trump, Biden, Sunak), climate, UK economy

### 📊 Text & Vocabulary Complexity
- **FOMC:** ~4,859 words/doc; high n-gram frequency and repetition  
- **Guardian:** ~13.5 words/doc (avg); diverse vocabulary, headline-focused

### 🔗 Co-occurrence Network
- Dense linkages in FOMC texts show consistency in terminology and policy themes
- Absence of clusters → Unified communication style across years

## 🔄 Tools Used
- **Orange Data Mining** – Corpus viewer, sentiment widget, topic modeling, visualization
- **Python (optional)** – For advanced text preprocessing or modeling
- **Guardian API** – For media data extraction

## 🚀 Strategic Recommendations
- **Real-Time Sentiment Monitoring:** Track public and market response to policy releases
- **Plain-Language Summaries:** Bridge the gap between institutional language and public understanding
- **Media Topic Watch:** Use NLP on media to catch rising concerns (e.g., inflation, unemployment)
- **Align Narratives:** Compare policy tone with media coverage to detect misinterpretations
