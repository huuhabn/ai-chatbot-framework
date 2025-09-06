AI Chatbot self-hosted, DIY Chatbot building platform built in Python. With this tool, it’s easy to create Natural Language conversational scenarios with no coding efforts whatsoever. 
The smooth UI makes it effortless to create and train conversations to the bot. AI Chatbot can live on any channel of your choice (such as Messenger, Slack etc.).

With this project you can create an AI powered chatbot in no time.  Read the [documentation](docs/README.md) to get started.

![](docs/screenshots/admin_chat_screenshot.png)

## Features
- Fully Self-Hosted
- Low-Code, DIY Admin Dashboard for Bot Development
- Multi-turn Conversations
- API request fulfilment (Tool Calling)
- Persistent Memory & Context Management
- Advanced Natural Language Understanding (NLU)
  - Spacy Word Embeddings
  - Intent Recognition (ML)
  - Entity Extraction (ML)
  - Zero shot NLU using Large Language Models (LLMs)
- Knowledge Base & FAQ answering using RAG (in development)
- Conversation Logs
- Channel Integrations
  - Web via REST API/Chat Snippet
  - Facebook Messenger
  - Slack (coming soon)
  - WhatsApp via Twilio (coming soon)

### Documentation

Check out our [documentation](docs/README.md) to get started.

### Tech Stack

 - Python / FastAPI / Pydantic: Backend API, request handling, data validation.
 - MongoDB / Motor: Database for conversations, async access.
 - React / NextJS: Chatbox admin UI.
 - scikit-learn / Tensorflow / Keras: Machine learning / deep learning for intent classification & responses.
 - Spacy / python-crfsuite: NLP tasks (tokenization, NER, entity extraction).
 - Docker / docker-compose / Kubernetes / Helm: (Containerization, deployment, scaling, orchestration.)


<hr></hr>
