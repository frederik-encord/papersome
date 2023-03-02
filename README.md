# Papersome 📜

papersome is a Python package that summarizes arxiv papers using OpenAI.

## Quickstart 🏃‍♂️

1. Create a .env file and set your OpenAI API key: `OPENAI_API_KEY="key-goes-here"`
2. Install the required packages with `pip install -r requirements.txt`
3. Run python `summarize_arxiv.py <arxiv-url>`. For example: `python summarize_arxiv.py https://arxiv.org/abs/1706.03762`

## Project structure 🚀

- `pdfs/`: directory containing downloaded arxiv papers in PDF format
- `summaries/`: directory containing the summaries of the arxiv papers
- `src/papersome/`: package containing the source code
- `summarize_arxiv.py`: script for summarizing arxiv papers with OpenAI
