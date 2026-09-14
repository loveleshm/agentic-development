# Writing helper agent

This is a very simple, single agent setup to help with writing tips.

- **Basic Agent Creation**: How to create your first ADK agent
- **ADK Workflow**: Understanding the agent lifecycle
- **Simple Text Processing**: Basic input/output handling
- **Agent Configuration**: Essential parameters and settings

## What is an ADK Agent?

An ADK agent is a **programmable AI assistant** that can:
- Process user inputs (text, images, etc.)
- Use AI models (like Gemini) to understand and respond
- Perform specific tasks based on your instructions
- Return structured or unstructured responses

Think of it as creating a **smart function** that uses AI to handle complex tasks.

## 🔧 Key Components

### 1. **LlmAgent Class**
The main building block for creating AI agents in ADK:
```python
from google.adk.agents import LlmAgent
```

### 2. **Essential Parameters**
- `name`: Unique identifier for your agent
- `model`: The AI model to use (e.g., "gemini-3-flash-preview")
- `description`: What your agent does
- `instruction`: How your agent should behave

### 3. **Basic Workflow**
1. **Input**: User sends a message
2. **Processing**: Agent uses AI model to understand and respond
3. **Output**: Agent returns a response

## 🚀 Getting Started

1. **Set up your environment**:
   ```bash
   # Get your API key from: https://aistudio.google.com/
   ```

2. **Install dependencies**:
   ```bash
   # Install required packages
   pip install -r requirements.txt
   ```

3. **Run the creative writing agent**:
   ```bash
   # Start the ADK web interface
   adk web
   
   # In the web interface, select: creative_writing_agent
   ```

4. **Test your agent**:
    - Try asking for story ideas: "I want to write a story about a magical forest"
    - Get character help: "Help me create a protagonist for my sci-fi story"
    - Request writing prompts: "Give me a creative writing prompt"
    - Ask for plot advice: "How can I structure my story's climax?"
