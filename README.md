# agents

help agents write code for humans

A huge thank you goes out to [CodeAesthetic](https://www.youtube.com/@CodeAesthetic) on Youtube, from which most of these excellent design and architecture decisions were inspired. support him via:

- [youtube](https://www.youtube.com/@CodeAesthetic)
- [codeaesthetic.io](https://codeaesthetic.io): free & paid courses & playgrounds
- [patreon](https://www.patreon.com/codeaesthetic)

# vibe coding speedrun checklist

DOs:
- [ ] DO define an `AGENTS.md` which specifies your high-level system design goals
- [ ] DO remind your agent to explicitly refer to `AGENTS.md` in every prompt before continuing
- [ ] DO break large tasks into small chunks
- [ ] DO be as specific in your expectations as possible
- [ ] DO include both a "macro" goal (broader vision we are working towards) as well as a "micro" goal (this is specifically what I want you to accomplish at this stage)
- [ ] DO A/B test the "micro" goal with various phrasing
- [ ] DO commit to version control in between every prompt in which you have made substantial progress
- [ ] DO have a consistent pre-prompt that describes the progress you have made so far, any MCP tools that are available for use, and any assumptions you have
- [ ] DO keep a record of your prompts in `./prompt_history` committed to version control so that agents can refer back to them
- [ ] DO remind your agents that `./prompt_history` exists, and you can refer to it when necessary
- [ ] DO have agents record incremental progress when you are certain that progress is successful
- [ ] DO use tools like [basic memory](https://github.com/basicmachines-co/basic-memory?tab=readme-ov-file) that allow agents to maintain a running knowledge base
- [ ] DO create templates for common prompt patterns you use repeatedly
- [ ] DO periodically test different models and compare their strengths/weaknesses

DO NOTs:
- [ ] DO NOT approach a large task with a prompt like "migrate this to TypeScript" or "refactor the repo"
- [ ] DO NOT use vague qualifiers like "make it better" or "optimize this" without specific criteria
- [ ] DO NOT expect that a larger context window will fix all your problems
- [ ] DO NOT allow agents to pollute your workspace with noise or any documentation that may be partially incorrect/misleading
- [ ] DO NOT assume agents will remember context or notes/tools/`AGENTS.md` from previous conversations exist without explicitly restating it
 
