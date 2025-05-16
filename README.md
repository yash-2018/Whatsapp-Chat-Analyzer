# WhatsApp Chat Analyzer

The WhatsApp Chat Analyzer is a Python-based interactive web app that allows users to upload their WhatsApp chat history and gain fun, insightful visualizations of their messaging habits. Whether you want to see who's the most active in the group, track chat frequency over time, or analyze emoji usage — this tool has it all.

---

## Features

- Upload `.txt` WhatsApp chat exports (individual or group)
- Preprocessing to clean and format raw messages
- User-wise message and word count
- Day-wise, month-wise, and hourly activity breakdowns
- Emoji and link sharing statistics
- WordCloud of most frequently used terms
- Activity heatmaps and timeline graphs

---

## Demo

> Run locally on your machine (instructions below) or deploy it on Streamlit Cloud for sharing.
pip install -r requirements.txt

---

## Technologies Used

- **Python**
- **Streamlit** – For building the web UI
- **pandas** – Data manipulation
- **matplotlib**, **seaborn** – Visualizations
- **wordcloud** – Generating word clouds
- **re (regex)** – Parsing chat messages

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yash-2018/Whatsapp-Chat-Analyzer.git
cd Whatsapp-Chat-Analyzer
