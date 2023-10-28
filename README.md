
# YouTube Video Chatbot

A Python chatbot that utilizes YouTube transcripts and OpenAI's GPT-3.5 Turbo model to facilitate discussions and answer questions about YouTube videos.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Example Usage](#example-usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This Python chatbot allows users to interactively discuss and ask questions about YouTube videos by providing the video link and their inquiries. The chatbot leverages YouTube transcripts to understand video content and utilizes the GPT-3.5 Turbo model from OpenAI to provide informative and contextually relevant responses. It serves as a powerful tool for enhancing engagement and learning from YouTube content.

## Features

- Extracts video transcripts from YouTube videos.
- Enables dynamic conversations and questions.
- Utilizes OpenAI's GPT-3.5 Turbo for natural language responses.

## Prerequisites

Before you get started, ensure you have the following prerequisites:

- Python 3.x
- Required Python packages: `openai`, `youtube_transcript_api`
- An OpenAI API key (obtain one from [OpenAI](https://beta.openai.com/signup/))

## Installation

1. Clone the GitHub repository:

   ```bash
   git clone https://github.com/AbhayPancholi/YouTube-Video-Chatbot.git
   ```

2. Install the required Python packages:

   ```bash
   pip install openai youtube_transcript_api
   ```

3. Set up your OpenAI API key:

   - Sign up for an API key at [OpenAI](https://beta.openai.com/signup/).
   - Replace `'your-api-key-here'` in the `openai.api_key` assignment within the `chat_with_model` function with your actual API key.

## Usage

To use the chatbot, follow these steps:

1. Run the chatbot script in your terminal:

   ```bash
   python chatbot.py
   ```

2. Enter the YouTube video link when prompted.

3. Provide questions or comments about the video when prompted. You can have dynamic conversations about the video's content.

4. Type 'exit' to end the chat session.

## Example Usage

Here's an example of how to use the chatbot:

```bash
Enter the link of the video: https://www.youtube.com/watch?v=your-video-id

Enter the questions you want to ask (type 'exit' to end): What's the video about?
```

The chatbot will respond with information about the video content.

## Contributing

Contributions are welcome! If you'd like to improve this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Create a pull request.

## Contact 
Feel free to connect on [LinkedIn](www.linkedin.com/in/abhaypancholi).
