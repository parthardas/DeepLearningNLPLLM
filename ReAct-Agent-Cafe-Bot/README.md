# Conversation Order Taking Cafe ChatBot

A Streamlit-based conversational AI application that simulates a cafe order-taking experience using advanced language models.

## 🌟 Features

- Interactive chat interface for placing orders
- Smart order processing and confirmation
- Receipt generation
- Conversation memory management
- Docker support for easy deployment

## 🛠️ Technology Stack

- Python 3.10
- Streamlit
- LangGraph
- Groq
- Pydantic
- Docker

## 📋 Prerequisites

- Python 3.10 or higher
- Docker (optional)
- API keys for:
  - Groq
  - HuggingFace (optional)
  - OpenAI (optional)

## 🚀 Getting Started

### Local Setup

1. Clone the repository:
```bash
git clone <repository-url>
cd ReAct-Agent-Cafe-Bot
```

2. Create and activate a virtual environment:
```bash
python -m venv .venv
.\.venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Create a `.env` file in the project root:
```env
GROQ_API_KEY=your_groq_api_key
HUGGINGFACEHUB_API_TOKEN=your_huggingface_token
OPENAI_API_KEY=your_openai_key
```

5. Run the application:
```bash
streamlit run react-agent-cafe-order-bot.py
```

### Docker Setup

1. Build the Docker image:
```bash
docker build -t react-cafe-bot .
```

2. Run the container:
```bash
docker run -p 8501:8501 react-cafe-bot
```

## 📁 Project Structure

```
ReAct-Agent-Cafe-Bot/
├── react-agent-cafe-order-bot.py  # Main application file
├── requirements.txt                # Python dependencies
├── Dockerfile                     # Docker configuration
├── .env                           # Environment variables (create this)
└── README.md                      # This file
```

## 💡 Usage

1. Open your browser and navigate to `http://localhost:8501`
2. Start a conversation with the chatbot
3. Place your order by following the prompts
4. Confirm your order
5. Receive your order receipt

## 🌐 Environment Variables

- `GROQ_API_KEY`: Your Groq API key
- `HUGGINGFACEHUB_API_TOKEN`: Your HuggingFace API token (optional)
- `OPENAI_API_KEY`: Your OpenAI API key (optional)

## 🐳 Docker Commands

Build the image:
```bash
docker build -t react-cafe-bot .
```

Run the container:
```bash
docker run -p 8501:8501 react-cafe-bot
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b /parthardas/DeepLearningNLPLLM`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin /parthardas/DeepLearningNLPLLM`)
5. Open a Pull Request

## DockerHub location

DockerHub Image: parthardas/react-agent-cafe-order-bot

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👥 Authors

- Partha R Das

## 🙏 Acknowledgments

- Thanks to the Streamlit team for their amazing framework
- Thanks to the LangGraph community for their support