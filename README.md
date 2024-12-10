## Text Summarization and Content Extraction App

This repository contains a web-based application that extracts and summarizes content from YouTube videos and websites. Built using **Streamlit** and **LangChain**, the app provides concise summaries of long-form content, leveraging advanced AI models for text processing.

---

## Features

- **YouTube Summarization**: Extracts and summarizes transcripts from YouTube videos.
- **Website Summarization**: Summarizes textual content from provided website URLs.
- **AI-Powered**: Uses the Gemma-7b-It model for accurate and coherent summaries.
- **Interactive Interface**: Simple and intuitive UI for seamless user interaction.

---

## Installation

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_directory>
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   streamlit run app.py
   ```

---

## Usage

1. Launch the application using Streamlit.
2. Enter your **Groq API Key** in the sidebar.
3. Provide a valid URL (YouTube video or website) in the input field.
4. Click the "Summarize the Content from YT or Website" button.
5. View the summary in the app interface.

---

## Requirements

- Python 3.8+
- Libraries:
  - `streamlit`
  - `langchain`
  - `langchain-groq`
  - `youtube_transcript_api`
  - `unstructured`
  - Other dependencies in `requirements.txt`

---

## Example Use Case

Input: A YouTube URL of a lecture or a website article.  
Output: A summarized version of the content in about 300 words, highlighting the key points.

---

## Future Enhancements

- Add support for multiple languages.
- Improve summarization for multimedia-rich content.
- Optimize performance for large documents.

---

This project demonstrates the power of AI and natural language processing to distill vast amounts of information into concise, actionable insights. Feel free to contribute and enhance the application!
