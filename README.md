# a2a-mcp-llm-lab
Multi-Agent AI Assistant Framework using LLM + A2A (Agent-to-Agent) + MCP (Model Context Protocol)
a2a-mcp-llm-lab/
├── agent_c.py        # Central coordinator (A2A Client)
├── agent_a.py        # HR agent (A2A Server + MCP Client)
├── agent_b.py        # Support agent (A2A Server + MCP Client)
├── mcp_server_a.py   # Tool A (e.g., Slack Mock)
├── mcp_server_b.py   # Tool B (e.g., Weather Mock)
└── shared/
    └── protocol.py   # A2A/MCP protocol definition
