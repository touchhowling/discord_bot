# Discord Bot

This Discord bot is designed to create an interactive chat experience using OpenAI's GPT-3.5 language model. It can be used to generate responses based on the conversation history within a specific channel. The bot utilizes the Discord.py library for interacting with the Discord API and the OpenAI Python library for making API requests to the GPT-3.5 model.

## Prerequisites

To run this bot, you need to have the following:

- Python 3.7 or above
- `discord.py` library installed (`pip install discord.py`)
- OpenAI Python library installed (`pip install openai`)

Additionally, you need to set up the following environment variables:

- `OPENAI_API_KEY`: Your OpenAI API key
- `SECRET_KEY`: Your Discord bot token

## Usage

1. Clone the repository or download the provided code files.

2. Open the Python file and replace the placeholder values for `OPENAI_API_KEY` and `SECRET_KEY` with your respective API key and bot token.

3. In the `on_message` method, the variable `file` is used to load different chat files based on user input. You can modify this section to fit your requirements or remove it altogether if you don't need it.

4. Create chat text files (e.g., `chat1.txt`, `chat2.txt`, `chat3.txt`) and populate them with conversation history that you want the bot to consider during the generation of responses.

5. Run the Python script. The bot will log in to Discord using the provided token and start listening for messages.

6. In your Discord server, mention the bot to trigger a response. The bot will consider the conversation history from the chat files and generate a response using the GPT-3.5 model. The response will be sent back to the channel where the mention occurred.

**Note:** Keep in mind the limitations and rate limits of the OpenAI API to avoid any unexpected issues or excessive usage.

## Additional Notes

- The bot uses the `text-davinci-003` model from OpenAI for generating responses. You can explore and experiment with other models provided by OpenAI if desired.

- Be cautious when handling sensitive or private information within the chat history, as the bot will consider the entire conversation during response generation.

- Feel free to customize the bot further according to your specific needs and preferences.

## License

This project is licensed under the [MIT License](LICENSE).

---

Enjoy using the Discord bot and have fun interacting with the GPT-3.5 language model! If you have any questions or need assistance, feel free to reach out.

Best regards,
Dev Saran Sujan
