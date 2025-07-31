# AI-Powered-Applications
This repository contains a series of Jupyter Notebooks demonstrating various AI-powered applications, primarily utilizing OpenAI's models, alongside other tools like Gradio for user interfaces and BeautifulSoup for web scraping. Each notebook focuses on a distinct application, showcasing different facets of AI integration.

## Table of Contents

* [Day 1: Website Summarizer](#day-1-website-summarizer)
* [Day 2: Website Brochure Generator](#day-2-website-brochure-generator)
* [Day 3: Multi-Model AI Assistant](#day-3-multi-model-ai-assistant)
* [Day 4: AI-Powered Search Engine & Website Brochure Maker with Gradio](#day-4-ai-powered-search-engine--website-brochure-maker-with-gradio)
* [Day 5: Conversational AI (Chatbot)](#day-5-conversational-ai-chatbot)
* [Day 6: Airline AI Assistance with Tool Use](#day-6-airline-ai-assistance-with-tool-use)
* [Setup](#setup)
* [Usage](#usage)
* [Contributing](#contributing)
* [License](#license)

---

## Day 1: Website Summarizer

This notebook demonstrates how to create a simple website summarizer using OpenAI's language models. It scrapes content from a given URL and then uses the model to generate a concise summary of the webpage.

**Key Features:**
* Web scraping using `requests` and `BeautifulSoup`.
* Text summarization using OpenAI's API.
* Environment variable loading for API keys.

## Day 2: Website Brochure Generator

Building upon web scraping, this notebook extends the functionality to generate a "website brochure." It extracts content and links from a specified webpage and can be used to create structured information, potentially for marketing or informational purposes.

**Key Features:**
* Advanced web scraping, including link extraction.
* Structured content generation from scraped data.
* Integration with OpenAI for text processing.

## Day 3: Multi-Model AI Assistant

This notebook explores building a helpful AI assistant that can leverage multiple large language models, including OpenAI, Anthropic Claude, and Google Gemini. It showcases how to interact with different API clients and potentially compare their outputs for various tasks.

**Key Features:**
* Integration with OpenAI, Anthropic Claude, and Google Gemini APIs.
* Demonstrates calling different models with a single prompt.
* Focus on comparing model responses (e.g., for joke generation).

## Day 4: AI-Powered Search Engine & Website Brochure Maker with Gradio

This notebook combines the concepts of AI-powered search and website brochure creation, all within an interactive Gradio interface. It allows users to input a query or a website URL and receive generated content or search results, making the tools easily accessible.

**Key Features:**
* AI-powered search capabilities.
* Website content extraction and processing.
* Interactive web interface built with Gradio.
* Utilizes OpenAI for natural language processing tasks.

## Day 5: Conversational AI (Chatbot)

This notebook focuses on creating a conversational AI or chatbot. It demonstrates how to maintain a chat history and generate contextually relevant responses using OpenAI's chat completion API, providing a basic framework for an interactive dialogue system.

**Key Features:**
* Implementation of a simple chatbot.
* Managing conversation history for contextual responses.
* Gradio interface for user interaction.
* Powered by OpenAI's chat models.

## Day 6: Airline AI Assistance with Tool Use

This notebook presents an AI assistant tailored for airline assistance, showcasing the use of "tools" or functions that the AI can call. This includes a demonstration of how the AI can understand a user's intent and then execute a specific function (like `get_ticket_price`) to retrieve information.

**Key Features:**
* AI assistant with specific domain knowledge (airline).
* Demonstrates AI's ability to use custom tools/functions.
* Gradio interface for the assistant.
* Example of fetching ticket prices based on user queries.

---

## Setup

To run these notebooks, you will need to:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    cd your-repo-name
    ```
2.  **Install dependencies:**
    It is recommended to create a virtual environment.
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    pip install -r requirements.txt
    ```
    *(Note: A `requirements.txt` file is not included, but you would typically create one with `pip freeze > requirements.txt` after installing necessary libraries like `openai`, `requests`, `beautifulsoup4`, `gradio`, `python-dotenv`, `anthropic`, and `google-generativeai`.)*

3.  **Set up API Keys:**
    These notebooks require API keys for services like OpenAI, Anthropic, and Google Gemini. Create a `.env` file in the root directory of the repository and add your keys:
    ```
    OPENAI_API_KEY="your_openai_api_key_here"
    ANTHROPIC_API_KEY="your_anthropic_api_key_here" # Required for Day 3
    GOOGLE_API_KEY="your_google_api_key_here"     # Required for Day 3
    ```
    Replace `"your_api_key_here"` with your actual API keys.

## Usage

To run a specific notebook:

1.  Start Jupyter Lab or Jupyter Notebook:
    ```bash
    jupyter lab
    # or
    jupyter notebook
    ```
2.  Navigate to the desired `.ipynb` file and open it.
3.  Run the cells in the notebook.

## Contributing

Feel free to fork this repository, make improvements, and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

[Specify your license here, e.g., MIT, Apache 2.0, etc.]
