# MCP Server Workbench

This repository contains notebooks and utilities to explore and interact with MCP servers, including a demo chat widget.

The key benefit is that it runs completly on ClearScape Experience without any hazzle of setting up additonal infrastructure.

---

## 🚀 Getting Started

### 1. Get a Free Teradata Environment

1. Visit [ClearScape Analytics Experience](https://clearscape.teradata.com/)
2. Sign up for a **free account** — it includes:

   * A Jupyter Notebook environment
   * A Teradata Vantage database instance

### 2. Clone This Repository

```
git clone https://github.com/martinhillebrand/mcp_server_workbench.git
```

### 3. Get an OpenAI API Key *(optional – only needed for chat widget)*

1. Go to [OpenAI Platform](https://platform.openai.com/)
2. Sign up or log in to your account
3. Navigate to the **API Keys** section
4. Create a new API key
5. Ensure your account has a small balance (≈1 USD is enough)

### 4. Run the Notebooks

Start in order:

1. `00-Setup-demo.ipynb` - follow the pip install instructions closely!
2. `01-explore-MCP-Servers.ipynb` - to run MCP servers
3. `02-chat-with-MCP.ipynb` - to use the tools of the MCP server in an LLM empowered chat interface

---

## 💬 Example Chat

Below is an example of the chat interface output:

![Example Chat](example_chat.png)
