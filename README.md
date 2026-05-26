# ADK Learning Tools

A hands-on codelab notebook for learning Google Agent Development Kit (ADK) concepts through practical examples.

This repository contains a single notebook:

- `ADK_Learning_tools.ipynb`

## What’s included

This notebook teaches how to build AI agents using Google ADK and demonstrates:

- **Part 0: Setup & Authentication**
  - Install required Python packages
  - Configure Google Cloud project settings
  - Authenticate and prepare Vertex AI for ADK usage

- **Part 1: Day Trip Genie**
  - Build a simple planning agent with `gemini-2.5-flash`
  - Use Google Search as a built-in tool
  - Generate budget-aware itineraries in markdown format

- **Part 2: Supercharging Agents with Custom Tools**
  - Create a custom function tool for live weather data
  - Build an agent-as-a-tool architecture with specialist agents
  - Orchestrate multi-agent delegation using `AgentTool`

- **Part 3: Agent Memory Demonstration**
  - Create a session-aware adaptive trip planner
  - Show the difference between using a single session vs separate sessions
  - Demonstrate how memory enables multi-turn conversational behavior

## Prerequisites

- Python environment with Jupyter or Colab support
- Google Cloud project with Vertex AI enabled
- Access to the Google ADK and Google Generative AI libraries

## Getting started

1. Open `ADK_Learning_tools.ipynb` in Jupyter Lab, Jupyter Notebook, or Google Colab.
2. Install dependencies and authenticate your environment.
3. Set your Google Cloud project values in the notebook:

```python
PROJECT_ID = "YOUR_PROJECT_ID"
LOCATION = "us-central1"
```

4. Run the notebook cells sequentially to:
   - create agents
   - define tools
   - execute example sessions
   - observe memory behavior across multi-turn conversations

## Notes

- This notebook is designed as an interactive learning resource rather than a production project.
- Custom tools and session management examples illustrate key ADK patterns for real-world agent systems.

## Author

Created by Qingyue (Annie) Wang, Developer Advocate and AI Engineer at Google.

Contact:

- LinkedIn: https://www.linkedin.com/in/anniewangtech/
- Twitter/X: https://twitter.com/anniewangtech
- Email: anniewangtech0510@Gmail.com
