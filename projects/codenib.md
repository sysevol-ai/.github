# CodeNib

CodeNib turns any repository into a searchable Wiki and a reusable context
service for coding agents. It is local-first, open source, and designed so the
same indexed repository can serve people, scripts, and agent integrations.

## Why use it?

CodeNib helps an agent or developer answer questions such as:

- Where is a behavior implemented?
- Which symbols and files depend on it?
- What source evidence supports an answer?

It combines BM25 and dense retrieval with optional structural indexes, then
serves bounded, source-linked results through the Wiki, Python APIs, and MCP.

## Start in 30 seconds

```bash
python -m pip install "codenib[mcp,semantic]==0.2.0"
codenib wiki /path/to/your/repository
```

The Wiki opens locally at `http://localhost:3000`. For an agent-facing MCP
server, build the index and run:

```bash
codenib index /path/to/your/repository
codenib mcp /path/to/your/repository
```

## Learn more

- [Documentation](https://docs.codenib.ai/)
- [Quickstart](https://docs.codenib.ai/quickstart/)
- [MCP server](https://docs.codenib.ai/mcp/)
- [Agent integrations](https://docs.codenib.ai/agent_integrations/)
- [Source repository](https://github.com/sysevol-ai/CodeNib)
- [PyPI](https://pypi.org/project/codenib/)

## Status

CodeNib is an active SysEvol project. See the source repository and release
notes for the current version and supported capabilities.
