# LangGraph Studio RAG Project

This project implements advanced document processing and reactive agent systems using LangChain and LangGraph Studio.

## Project Goals

### 1. Multi-Modal RAG System
Build a Retrieval-Augmented Generation (RAG) system that can process and analyze:

- PDF documents

This system will enable:
- PDF text extraction and processing
- Efficient document indexing and retrieval
- Contextual question-answering based on the processed documents

### 2. Reactive Agent System
Implement a reactive agent system using LangChain and LangGraph Studio that can:
- Process and respond to events in real-time
- Handle complex workflows through agent collaboration
- Utilize the RAG system for informed decision-making

The reactive agent implementation is based on [LangGraph Studio](https://langchain-ai.github.io/langgraph/concepts/langgraph_studio/), which provides a visual interface for designing and debugging agent workflows.

## Project Structure

```
.
├── examples/         # Example implementations and usage demos
├── notebooks/        # Jupyter notebooks for experimentation and documentation
├── src/             # Source code for the project
└── tests/           # Test suite
```

## Setup

1. Create and activate the virtual environment:
```bash
uv venv langchain
source langchain/bin/activate
```

## Getting Started

### Local Development
1. Create and activate the virtual environment:
```bash
uv venv langchain
source langchain/bin/activate
```

### Google Colab Integration
This project supports development using Google Colab's GPU resources. To use this feature:

1. Create a GitHub repository and push this project to it
2. Authorize Google Colab to connect to GitHub:
   - Go to Google Colab
   - Click on `File / Open notebook`
   - Navigate to the GitHub tab
   - Enter your GitHub username and authorize access

3. Workflow:
   - Develop notebooks locally in VS Code
   - Push changes to GitHub
   - Open notebooks in Google Colab via the GitHub tab
   - Select GPU runtime in Colab for enhanced performance
   - Any changes made in Colab can be committed back to GitHub

For detailed instructions on setting up the Colab integration, see our setup guide in `notebooks/colab_setup.ipynb`.

## Documentation

[To be added: Detailed documentation for both the RAG system and reactive agent]

## Contributing

[To be added: Contribution guidelines]

## License

[To be added: License information]
