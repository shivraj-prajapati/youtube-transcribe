# YouTube Transcript to Detailed Notes Converter

This is a Streamlit application that extracts transcripts from YouTube videos and generates a detailed summary using Google's Generative AI (Gemini-Pro). The application summarizes the video transcript in points within 250 words.

## Features

- Extract transcript from a YouTube video
- Summarize the transcript into key points within 250 words
- Display the video thumbnail and detailed notes on the web page

## Installation

### Prerequisites

- Python 3.7 or higher
- Streamlit
- Google Generative AI Python client library (`google-generativeai`)
- YouTube Transcript API (`youtube-transcript-api`)

### Steps

1. **Clone the repository**:

    ```bash
    git clone https://github.com/shivraj-prajapati/youtube-transcribe
    cd youtube-transcript-summarizer
    ```

2. **Create a virtual environment and activate it**:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages**:

    ```bash
    pip install -r requirements.txt
    ```

4. **Set up your Google API key**:

    ```bash
    export GOOGLE_API_KEY='your_google_api_key'
    ```

5. **Run the Streamlit app**:

    ```bash
    streamlit run app.py
    ```

## Usage

1. Enter the YouTube video link in the input field.
2. Click the "Get Detailed Notes" button.
3. Wait for the transcript to be extracted and summarized.
4. View the video thumbnail and detailed notes on the web page.

## File Structure

| File/Directory       | Description                                            |
|----------------------|--------------------------------------------------------|
| `app.py`             | The main Streamlit application script.                |
| `requirements.txt`   | A file listing the required Python packages.          |
| `README.md`          | This file.                                             |


