## LangChain Summarizer: Text Summarization from YouTube & Websites

This repository contains a web application that summarizes text from YouTube videos and web pages using **LangChain** **Framework**. The app is designed for efficient information retrieval and summarization, allowing users to input URLs for YouTube videos or websites and receive concise summaries of the content. The summarization pipeline is powered by LangChain’s summarization tools, Groq API for chat-based interaction, and LangChain's document loaders for flexible content handling.

## Overview
This project enables users to quickly summarize content from web pages or YouTube videos by entering URLs into the application. Using LangChain’s advanced natural language processing tools and Groq API, the app retrieves and processes content into a summarized form, making it easy to understand lengthy videos or articles in a fraction of the time. The interface is built with Streamlit for a smooth, interactive user experience.

## Features
- Summarize YouTube Videos: Input a YouTube video URL to receive a summary of the video's content.
- Summarize Web Pages: Input a URL of any website to get a concise summary of the article or web content.
- Interactive Chat with Groq API: Integrates the Groq API for additional chat-based interaction and customization.
- User-Friendly Interface: Built with Streamlit, providing an intuitive web interface for easy interaction.
- Flexible Content Loading: Utilizes YoutubeLoader and UnstructuredURLLoader from LangChain to handle various content formats seamlessly.

## Summarizing Content:
- Open the application in your web browser (usually at http://localhost:8501).
- Enter a YouTube video URL or a website URL in the provided input field.
- Click the Summarize button to generate a concise summary of the content.

## Example Workflow:
- Launch the app and enter a URL of a YouTube video or article.
- The app will load the content, summarize it using **LangChain**, and display the output.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
