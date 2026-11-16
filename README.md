# AI Agent Workflows

Practical AI agent workflows built with Claude, Python and MCP.

Each tool in this repo automates a real business task: the kind of work that eats hours every week. They're rebuilt from systems I run day to day, using sample data only.

## Tools

| Tool | What it does | Status |
|---|---|---|
| review-insights | Turns a CSV of customer reviews into themes, complaints and quotable lines | 🚧 In progress |

More tools coming: each lives in its own folder with a README, setup steps and example output.

## How the tools are built
- **Claude API** for reasoning and structured output
- **Tool use / MCP** so agents can act, not just answer
- **Python** for data handling and glue code

## Principles
- **No secrets in code.** API keys live in a local `.env` file, which is git-ignored.
- **Sample data only.** Nothing from real clients or employers.
- **Scoped access.** Agents get only the permissions the task needs.
- **Measured.** Each tool's README notes how long the task took before and after.

## Running a tool
1. Clone the repo and open the tool's folder
2. Create a `.env` file with your `ANTHROPIC_API_KEY`
3. Follow the steps in that tool's README

## About me
I'm Markus, and I build AI workflows that teams actually use.
[GitHub profile](https://github.com/robbertsmarkus) · [LinkedIn](https://www.linkedin.com/in/markusrobberts)
