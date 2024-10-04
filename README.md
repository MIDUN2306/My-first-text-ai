

# LangChain Chatbot with Gradio Interface

This project is a conversational AI chatbot built using LangChain and Gradio, powered by OpenAI's GPT-3.5-turbo model. The chatbot maintains context and handles conversations with memory, making it more interactive and responsive.

## Features

- **Memory-based conversation**: Keeps track of chat history using LangChain's `ConversationBufferMemory`.
- **Gradio Interface**: A user-friendly interface for interacting with the chatbot.
- **GPT-3.5-turbo model**: Leverages OpenAI's `gpt-3.5-turbo` for generating responses.
- **Customizable templates**: The chatbot prompt can be tailored via LangChain's `PromptTemplate`.

## Prerequisites

Ensure you have the following installed on your system:

- Python 3.7+
- Gradio: `pip install gradio`
- LangChain: `pip install langchain`
- OpenAI: `pip install openai`
- An OpenAI API key (set as an environment variable `OPENAI_API_KEY`).

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

. Set your OpenAI API key as an environment variable:

   ```bash
   export OPENAI_API_KEY="your-api-key-here"
   ```

## Project Structure

- **`main.py`**: Main script containing the chatbot logic and Gradio interface.
- **`requirements.txt`**: Lists the required Python packages.

## Usage

Run the chatbot application locally:

```bash
python main.py
```

This will launch the Gradio interface where you can interact with the chatbot.

## Example

Here's a basic flow of how the chatbot works:

1. User initiates a conversation through the Gradio chat interface.
2. The chatbot processes the query using the OpenAI GPT-3.5 model, keeping track of the chat history.
3. The chatbot responds with a contextual answer, allowing for a fluid, memory-based conversation.

## Environment Variables

- `OPENAI_API_KEY`: Your OpenAI API key is required for the bot to generate responses. Ensure this is set before running the application.

## Contributing

Feel free to open issues or submit pull requests if you want to contribute to this project.

## License

This project is licensed under the MIT License.

---

Make sure to replace `your-username/your-repo-name` with the actual path for your GitHub repository before uploading it. Also, don't forget to create a `requirements.txt` file to list all your dependencies. 

Here's an example `requirements.txt` content:

```txt
gradio
langchain
openai
```

Let me know if you'd like any further customizations!
