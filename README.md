1) Setting Up the Environment 
Step 1: Import the OpenAI library.
Show the line of code: import openai.
Explain that this allows us to interact with OpenAI’s API.
Step 2: Set the API key.
Show the line: openai.api_key = 'your_api_key_here'.
Explain the importance of the API key for authentication.
2) Defining the Chat Function 
Function Declaration:
Show the chat_with_gpt(prompt) function.
Explain its purpose: to send user input to the API and retrieve a response.
API Call:
Highlight the openai.ChatCompletion.create(...) line.
Explain the parameters:
model: Specify which AI model to use (e.g., gpt-3.5-turbo).
messages: A list containing user messages.
