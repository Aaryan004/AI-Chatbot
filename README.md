# Conversational Q&A Chatbot

This project implements a conversational Q&A chatbot using Streamlit and LangChain. The chatbot uses OpenAI's language models to generate responses.

## Features

- Interactive chat interface using Streamlit
- Integration with OpenAI's language models
- Customizable system message to set the chatbot's persona
- Persistent conversation history within a session

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/conversational-qa-chatbot.git
   cd conversational-qa-chatbot
   ```

2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

3. Set up your OpenAI API key:
   - Create a `.env` file in the project root
   - Add your OpenAI API key: `OPENAI_API_KEY=your_api_key_here`

## Usage

1. Run the Streamlit app:
   ```
   streamlit run app.py
   ```

2. Open your web browser and go to the URL provided by Streamlit (usually `http://localhost:8501`)

3. Start chatting with the AI assistant!

## Project Structure

- `app.py`: Main Streamlit application
- `langchain.ipynb`: Jupyter notebook with examples of using LangChain
- `requirements.txt`: List of Python dependencies

## Customization

You can customize the chatbot's persona by modifying the `SystemMessage` in `app.py`:

```python
SystemMessage(content="You are a comedian AI assistant")
```

## Dependencies

- langchain
- openai
- huggingface_hub
- python-dotenv
- streamlit

## License

This project is open-source and available under the [MIT License](LICENSE).

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
