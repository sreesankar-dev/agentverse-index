# Contributing

Thanks for helping grow the list! Please follow these rules so it stays useful.

## What belongs here

| Part | Qualifies if it... |
| --- | --- |
| **Agent Skills** | Has a `SKILL.md` (or ships as a Claude Code plugin) that an existing agent can install. |
| **Agent Frameworks** | Is an open-source library for building agents, not a hosted-only product. |
| **Voice Agents** | Runs a real-time voice conversation end to end, not just speech-to-text or text-to-speech. |
| **MCP Servers** | Implements the Model Context Protocol and can be self-hosted. |

Everything must be **public, open source and actively maintained**. Archived or abandoned repos will be removed.

## Adding an entry

1. **Link to the original repo.** Do not copy files into this repo.
2. Add it to the best-fitting section, using this format:

   ```markdown
   - [owner/repo](https://github.com/owner/repo) - One short sentence on what it does. ![stars](https://img.shields.io/github/stars/owner/repo?style=flat)
   ```

3. Keep the description short, factual and free of marketing words ("best", "ultimate").
4. One entry per line. Avoid duplicates; search the README first.
5. If no section fits, propose a new one in your PR.

## Pull request checklist

- [ ] The link works and points to the original author's repo
- [ ] The description is one sentence and ends with a period
- [ ] The entry is in the right section
- [ ] I checked the project does nothing malicious (no hidden network calls, credential grabbing, etc.)

## Removing or fixing entries

Dead link, abandoned repo or wrong description? Open an issue or a PR. Weekly CI also flags broken links.
