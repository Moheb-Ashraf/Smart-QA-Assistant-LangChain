# Smart Q&A Assistant with LangChain

A Smart Agriculture Question-Answering Assistant built as part of a LangChain learning assignment.

## Project Overview

This project demonstrates how to build an AI assistant using LangChain and Google's Gemini model, with tools for agricultural information, weather lookup, and irrigation calculations.

## Features

- **LCEL Chain:** Dynamic prompts for brief and detailed answers.
- **Conversational Memory:** Persistent chat history using file-based storage.
- **Structured Output:** Pydantic schema validation for structured answers.
- **Custom Agent:** An agent that can select and use multiple tools.
- **Farming Guide Search:** Retrieves information from a local text file.
- **Weather Tool:** Fetches current weather data through Open-Meteo.
- **Irrigation Calculator:** Estimates irrigation water volume.

## Technologies

- Python
- LangChain
- Google Gemini API
- Pydantic
- Requests
- Open-Meteo API
- Google Colab

## Project Files

- `assignment.ipynb` — Notebook containing the implementation and tests.
- `farming_guide.txt` — Local agricultural knowledge source.

## How to Run

1. Open `assignment.ipynb` in Google Colab.
2. Install the required dependencies.
3. Configure your Google Gemini API key securely.
4. Run the notebook cells in order.
5. Ensure `farming_guide.txt` is available in the working directory.

## Security

Never commit API keys, passwords, or other secrets to version control. Configure API credentials securely using Colab Secrets or environment variables.

## Disclaimer

Weather information depends on the availability of the external API. Irrigation calculations are mathematical estimates and should not be treated as crop-specific agricultural prescriptions.

## Learning Objectives

This project practices LCEL, prompt engineering, conversational history, structured outputs, and tool-using agents.
