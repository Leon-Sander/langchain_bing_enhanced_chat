# Enhancing Langchain Chatbot with Bing Search API

## Overview

In this project, we aim to enhance a chatbot's capabilities by integrating it with the Bing Search API. The chatbot is built using Python and utilizes the Langchain framework for reasoning and decision-making. The Bing Search API is used as a tool to fetch real-time information from the web, making the chatbot more informative and up-to-date.

Here is the link to my YouTube video where I created this repository: [Supercharging Langchain: Use Web Search Results for Your Chatbot](https://www.youtube.com/watch?v=4uo1U_EnYfU&lc=UgyFvQaQPfS_VVOqpMV4AaABAg)

## Features

- **Conversational Agent**: Uses Langchain's conversational agent for reasoning and decision-making.
- **Memory Buffer**: Keeps track of previous interactions for a more coherent conversation.
- **Web Search**: Utilizes Bing Search API to fetch real-time information from the web.
- **Error Handling**: Gracefully handles parsing errors to ensure smooth interaction.

## Limitations

The code only fetches snippets from the web search results, which contain limited information. For full access to websites, one would have to scrape the websites. I have another video and GitHub repository that covers this topic in detail. 

- [Langchain Youtube Summarizer Created and Deployed on AWS in ONE VIDEO](https://www.youtube.com/watch?v=zNcd78ZDqo8&t=747s)
- [GitHub Repository](https://github.com/Leon-Sander/yt_and_article_summarizer)

## How to Use

1. Clone this repository.
2. Install the required packages.
3. Add your Bing Search and OpenAI API key to a `.env` file.
4. Run the chatbot.

## Code Structure

The repository contains a single Python file that includes everything from initializing the agent to making API calls.

- `openai_bing_chat.py`: The main script where everything from initializing the agent to making API calls is defined.