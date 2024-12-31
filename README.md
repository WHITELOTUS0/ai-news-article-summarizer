# AI NEWS SUMMARIZER

In today's fast-paced world, it's essential to stay updated with the latest news and information. However, going through multiple news articles can be time-consuming. To help you save time and get a quick overview of the important points, I developed a News Articles Summarizer application using **ChatGPT** and **LangChain**.

The Summarizer also provides summaries in different languages, French being our exemplary case. This showcases the potential of the tool to cater to a diverse, global audience.

## Instructions

Before you start, obtain your `OpenAI API` key from the OpenAI website. You need to have an account and be granted access to the API. After logging in, navigate to the API keys section and copy your API key.

You can either run this application locally or in Google Colab (head straight to the notebook). To run it locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/WHITELOTUS0/ai-news-article-summarizer.git
    ```

2. Create a new environment and activate the virtual environment:
    ```bash
    python -m venv venv
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Set your `OPENAI_API_KEY` as an environment variable. You can do this by creating a `.env` file in the root directory of the project and adding the following line:
    ```env
    OPENAI_API_KEY=your_openai_api_key
    ```

5. Follow the instructions in the notebook to install additional packages:
    ```bash
    pip install -qU langchain-openai
    pip install -qU langchain-community
    pip install -q newspaper3k python-dotenv
    pip install -q lxml_html_clean
    ```

6. Run the notebook to start summarizing news articles.