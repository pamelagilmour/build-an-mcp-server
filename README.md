# Build an MCP Server

From Model Context Protocol (MCP) docs at https://modelcontextprotocol.io/docs/develop/build-server


## Objective: Build a simple MCP weather server and connect it to a host, Claude for Desktop.

I followed the docs accordingly:

Set up environment

Build the server

Test server with Claude for Desktop


## What's happening under the hood

User asks Claude for Desktop a question about the weather.

The client/Claude for Desktop sends user's question to the Claude API/LLM.

Claude API/LLM analyzes the question and available tools then decides what to use.

Claude API/LLM tells the client to call the MCP tool.

The client/Claude for Desktop calls/uses the selected tool with the MCP server.

The response is sent back to Claude API/LLM.

Claude API/LLM forms a natural language response.

The response is rendered on the interface.


## Next, build a client!

+-+-+-+-+-+-+-+-+-+

### Notes, quoted from the docs

```
Servers can connect to any client. We’ve chosen Claude for Desktop here for simplicity, but we also have guides on building your own client as well as a list of other clients here.
```

https://modelcontextprotocol.io/docs/develop/build-client

https://modelcontextprotocol.io/clients

### Core MCP Concepts

Model Context Servers can provide three main types of capabilities:

Resources, file like data that is read by clients
Tools, functions that are called by the LLM
Prompts, pre written templates that help users accomplish specific tasks

 