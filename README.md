# Basic Dynamic AI Chatbot

## Introduction

This project showcases a dynamic AI chatbot, known as the Sassy Chatbot. It can emulate different personas, maintain conversation history, and provide coherent responses. The chatbot is powered by OpenAI's GPT-3.5 Turbo model and is designed to interact with users through text-based conversations.

## Getting Started

To run the Sassy Chatbot, follow these steps:

### Prerequisites

- Python (3.7 or higher)
- [OpenAI Python package](https://pypi.org/project/openai/)
- [Python-dotenv package](https://pypi.org/project/python-dotenv/)

### Installation

1. Clone this repository to your local machine.

```bash
git clone https://github.com/yourusername/sassy-chatbot.git
cd sassy-chatbot
```

2. Install the required dependencies using pip.

```bash
pip install -r requirements.txt
```

3. Create a `.env` file in the project directory and add your OpenAI API key.

```env
# Copy this file as .env and replace placeholders with your values
OPENAI_API_KEY='your_api_key_here'
```

### Usage

Run the chatbot by executing the Jupyter notebook `basic_chatbot.ipynb`. You can interact with the chatbot within the notebook.

### Example Environment Variables

An `example.env` file is provided to show the format of the `.env` file without containing actual sensitive data. You can copy this file as `.env` and replace placeholders with your API key.

```env
# Copy this file as .env and replace placeholders with your values
OPENAI_API_KEY='your_api_key_here'
```

## Persona Switching

The chatbot supports different personas, including a sassy assistant, an angry assistant, and a thoughtful assistant. You can customize the persona by modifying the system message in the code.

## Chatbot Conversations

The chatbot can engage in various conversations. Example conversations and responses are included in the Jupyter notebook.

## Important Note

- The `.env` file containing sensitive information (API key) should be kept private and should not be shared publicly. Ensure it is listed in your `.gitignore` file to prevent accidental uploads to your repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to explore, modify, and enhance the Sassy Chatbot for your own projects!
