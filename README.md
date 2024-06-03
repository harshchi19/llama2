**Llama 2 Chatbot**
---

## Overview

This project implements a conversational chatbot powered by the Llama 2 language model. Users can interact with the chatbot by providing prompts, and the chatbot generates responses based on the input. The chatbot utilizes the Replicate API for model inference.

---

## Features

- **Real-time Conversations**: Engage in natural and fluid conversations with the chatbot.
- **Model Selection**: Choose from multiple Llama 2 models, including Llama2-7B, Llama2-13B, and Llama2-70B.
- **Customization**: Adjust parameters such as temperature, top_p, and max_length to tailor the chatbot's responses.
- **Chat History**: View and clear chat history for better organization and user experience.
- **Streamlit Integration**: The chatbot is implemented as a Streamlit web application for easy deployment and usage.

---

## Usage

1. **Provide Replicate API Token**: Enter your Replicate API token in the provided input field.
2. **Select Model and Parameters**: Choose a Llama 2 model and adjust parameters like temperature, top_p, and max_length.
3. **Interact with the Chatbot**: Enter prompts in the chat input field to engage with the chatbot.
4. **View and Clear Chat History**: Chat history is displayed in the interface, and you can clear it using the provided button.

---

## Deployment

To deploy the Llama 2 Chatbot locally, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies listed in the `requirements.txt` file.
3. Set up your Replicate API token as an environment variable.
4. Run the Streamlit app using the command `streamlit run app.py`.
5. Access the chatbot interface in your web browser.

---

## Credits

This project utilizes the following technologies and resources:

- **Llama 2 Model**: Powered by the Llama 2 language model.
- **Replicate API**: Used for model inference and responses.
- **Streamlit**: Provides the web application framework for the chatbot interface.
---

## License

This project is licensed under the [MIT License](LICENSE).

