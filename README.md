 # NovaBot – Neurofive Solutions Support Assistant

NovaBot is a simple AI-powered support chatbot built using Python and the Anthropic Claude API. It uses a custom system prompt to simulate a professional customer support assistant for Neurofive Solutions.

## Features

* Custom AI support assistant persona (NovaBot)
* Handles software and customer support-related queries
* Politely declines off-topic questions
* Provides professional and concise responses
* Uses Claude API for natural language understanding
* Includes sample test messages for demonstration

## Technologies Used

* Python 3
* Anthropic Claude API
* Custom System Prompt Engineering

## Project Structure

```
chatbot.py
README.md
```

## Installation

1. Clone the repository:

```bash
git clone <your-repository-link>
```

2. Navigate to the project folder:

```bash
cd your-project-folder
```

3. Install the required package:

```bash
pip install anthropic
```

## API Key Setup

Create an Anthropic API key from the Anthropic Console and configure it securely using environment variables.

### Windows

```bash
setx ANTHROPIC_API_KEY "your-api-key"
```

### Mac/Linux

```bash
export ANTHROPIC_API_KEY="your-api-key"
```

> Note: Avoid hardcoding your API key inside the source code before pushing your project to GitHub.

## Running the Project

Run the following command:

```bash
python chatbot.py
```

The chatbot will automatically process the predefined test messages and display the generated responses.

## Test Messages Included

The project includes the following sample queries:

* Password recovery issue.
* Project deployment status.
* Billing and invoice questions.
* An off-topic request (poem about cats).
* Support plan comparison.

These examples demonstrate how NovaBot handles both valid and invalid support requests.

## NovaBot Rules

NovaBot only provides assistance related to Neurofive Solutions, including:

* Account and login issues.
* Billing-related questions.
* Project status inquiries.
* Technical support.
* Product and service-related help.

For unrelated questions, NovaBot politely redirects users back to company support topics.

## Security Note

Before uploading this project to GitHub:

* Remove any hardcoded API keys.
* Store API credentials using environment variables.
* Never expose secret keys in public repositories.

## Future Improvements

* Interactive command-line chat interface.
* Web-based UI using HTML, CSS, and JavaScript.
* Support for conversation history.
* Integration with multiple LLM providers such as OpenAI and Gemini.
* Deployment as a customer support web application.

## License

This project is intended for educational and internship purposes.


