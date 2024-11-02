# PIB-TRANSVID-Converting-PIB-Articles-Into-Regional-Languages
This project automates the conversion of PIB press articles into regional language videos by combining web scraping, text summarization, translation, text-to-speech, and video generation. Below are the setup and workflow steps to get started.



INSTALLATION:

1) Set up Text-to-Speech (TTS) Environment:
Begin by installing and configuring the Text-to-Speech library. Ensure TTS functions correctly before proceeding to the Streamlit integration.

2) Set up Streamlit Web Interface:
Configure the Streamlit interface by writing application code (e.g., app.py). The app should allow users to enter text, select languages, and generate spoken output using the TTS system.

3) Install ImageMagick:
For image processing and display within the Streamlit app, install ImageMagick. You can do this by downloading the binaries or using a package manager, depending on your OS.


WORKFLOW:

1) Copy PIB Article Link:
Start by copying the link of the desired article from the PIB website.

2) Scraping:
Paste the link in the Streamlit interface to scrape the article's text content.

3) Cleaning:
After scraping, clean the content to remove unwanted text, ensuring only the article text remains.

4) Text Summarization:
Summarize the cleaned text to produce a concise version of the article.

5) Language Selection & Text-to-Speech Conversion:
Choose a regional language for the text-to-speech conversion, and convert the summarized text into audio into audio.

6) Video Generation:
Generate a video by combining the audio and relevant visuals, creating a regional language video version of the article.
