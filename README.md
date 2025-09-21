# TravelGenie AI Agent

TravelGenie is an AI-powered travel planning agent that interacts through Telegram to create personalized trip itineraries based on user input. It leverages n8n automation workflows, OpenAI GPT-4 language models, and Telegram Bot APIs to deliver interactive, real-time travel recommendations.

## Features

- Conversational trip planner agent integrated with Telegram.
- AI-powered itinerary generation using GPT-4 mini-model.
- Memory buffer for context-aware conversations.
- Sends travel plans and responses directly through Telegram messages.
- Built on n8n automation platform using custom AI agent nodes.

## Architecture

- **Telegram Trigger:** Listens for travel requests from the Telegram user.
- **AI Agent:** Processes input and generates trip itineraries using OpenAI GPT-4.
- **Memory Buffer:** Maintains conversational context for better interaction.
- **Telegram Send Message:** Delivers generated itineraries and replies back to the user.

## Getting Started

### Prerequisites

- n8n automation platform installed and running.
- Telegram bot token and chat configurations.
- OpenAI API key with GPT-4 access.
- Internet access for API communications.

### Installation
git clone https://github.com/Akhilesh-yadav680/TravelGenie.git
cd TravelGenie

2. Import the provided `TravelGenie.json` workflow file into your n8n instance.

3. Configure credentials for:
- Telegram API
- OpenAI GPT-4 API

4. Deploy the n8n workflow and start your Telegram bot.

## Usage

- Send a travel request message to the Telegram bot.
- TravelGenie will process your input and generate an itinerary.
- The bot responds with the planned trip details directly in Telegram.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests for enhancements and bug fixes.

## License

This project is licensed under the MIT License.

## Contact

For support or questions, contact [your-email@example.com].


1. Clone this repository:

