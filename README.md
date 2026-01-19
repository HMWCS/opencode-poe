# OpenCode + Poe (OpenAI-Compatible)

This configuration enables OpenCode to work with Poe's OpenAI-compatible API.

## Supported Models

Here are several models that work well with OpenCode, in no particular order (non-exhaustive):
* GPT 5.2
* Claude Opus 4.5
* Claude Sonnet 4.5
* Minimax M2.1
* Gemini 3 Pro

## Setup

1) Install (pnpm global)  
- `pnpm add -g opencode-ai`

2) Set key  
- macOS: add `export AGENT_API_KEY="YOUR_POE_KEY"` to `~/.zshrc`  
- Windows (PowerShell): `setx AGENT_API_KEY "YOUR_POE_KEY"`

3) Config path  
- macOS: `~/.config/opencode/opencode.json`  
- Windows: `%USERPROFILE%\.config\opencode\opencode.json`

4) Run  
- `opencode`  
- `/models` to switch models

## References
- [OpenCode Models Documentation](https://opencode.ai/docs/models/)
- [Poe OpenAI-Compatible API](https://creator.poe.com/docs/external-applications/openai-compatible-api)
