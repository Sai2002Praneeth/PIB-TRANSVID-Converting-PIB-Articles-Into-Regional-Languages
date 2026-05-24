# PIB TRANSVID – AI-Powered Multilingual Text-to-Video Generation System

Live Demo: https://huggingface.co/spaces/Codeszz/pib-transvid

GitHub Repository: https://github.com/Sai2002Praneeth/PIB-TRANSVID-Converting-PIB-Articles-Into-Regional-Languages

## Overview

PIB TRANSVID is an NLP-powered application that automatically converts PIB press articles into multilingual regional-language videos using web scraping, text summarization, text-to-speech synthesis, and automated video rendering.

The system processes PIB article links, extracts and cleans article content, generates summarized scripts, converts text into regional-language audio, and produces video outputs through an interactive Streamlit-based interface.

## Features

* Automated PIB article scraping and preprocessing
* NLP-based text summarization and script generation
* Multilingual text-to-speech conversion
* Automated audio-video synchronization and rendering
* Interactive Streamlit web application
* Public cloud deployment on Hugging Face Spaces

## Tech Stack

Python, Streamlit, NLP, GTTS, MoviePy, PIL, Pandas, BeautifulSoup, Transformers

## Workflow

1. Input PIB article URL
2. Scrape and clean article content
3. Generate summarized script using NLP
4. Convert summarized text into regional-language speech
5. Render audio and visuals into video output
6. Display generated content through Streamlit interface

## Live Deployment

Hugging Face Spaces:
https://huggingface.co/spaces/Codeszz/pib-transvid

## Installation

```bash
pip install -r requirements.txt
streamlit run streamlit_app.py
```

## Future Improvements

* LLM-based advanced summarization
* Real-time multilingual translation
* Improved video templates and animations
* Cloud storage integration
* Export and download optimization
