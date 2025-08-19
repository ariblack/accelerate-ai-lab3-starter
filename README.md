# Lab 3: Prototype to Production - Starter Files

Welcome to Lab 3! This is the starter repository where you'll build a production-ready ADK agent step by step.

## 🚀 What You'll Build

In this lab, you'll focus on critical deployment aspects:

1. **Deploy Gemma to Cloud Run with GPU** - Set up a high-performance Gemma model backend
2. **Integrate the Gemma deployment with an ADK agent** - Connect your agent to the GPU-accelerated model
3. **Test with ADK Web interface** - Validate your conversational agent works correctly
4. **Perform load testing** - Observe how both Cloud Run instances auto-scale under load

## 📁 Starter Structure

```
accelerate-ai-lab3-starter/
├── README.md                    # This file
├── pyproject.toml               # Python dependencies (complete)
├── env.template                 # Environment template (complete)
├── server.py                    # FastAPI server (TODO: implement)
├── Dockerfile                   # Container config (TODO: implement)
├── load_test.py                 # Load testing (TODO: implement)
├── production_agent/            # Agent implementation
│   ├── __init__.py             # Package init (complete)
│   └── agent.py                # Agent logic (TODO: implement)
└── ollama-backend/             # Ollama backend
    └── Dockerfile              # Backend container (TODO: implement)
```

## 🎯 Files to Complete

You'll need to implement the following files by following the codelab instructions:

- ✅ `pyproject.toml` - Dependencies (already complete)
- ✅ `env.template` - Environment template (already complete)
- 🚧 `production_agent/agent.py` - ADK agent implementation
- 🚧 `server.py` - FastAPI server with endpoints
- 🚧 `Dockerfile` - Container configuration
- 🚧 `load_test.py` - Load testing script
- 🚧 `ollama-backend/Dockerfile` - Ollama container

## 📚 Getting Started

1. Follow the codelab instructions to implement each TODO section
2. Copy and paste the provided code snippets
3. Deploy Gemma backend to Cloud Run with GPU
4. Deploy ADK agent and test with load testing

## 🔗 Resources

- [Complete Solution](https://github.com/amitkmaraj/accelerate-ai-lab3-complete)
- [Google ADK Documentation](https://cloud.google.com/agent-development-kit)
- [Cloud Run Documentation](https://cloud.google.com/run/docs)

Happy coding! 🎉
