# Dory Agent Skills

Agent Skills for Dory, the AI-native SQL workspace for humans and agents.

## Install

Install the Dory skill with the open Agent Skills CLI:

```bash
npx skills add https://github.com/dorylab/skills --skill dory
```

Or use the GitHub shorthand:

```bash
npx skills add dorylab/skills --skill dory
```

## What It Does

The `dory` skill teaches agents when to use Dory, how to use Dory MCP tools, and how to preserve generated SQL, result sets, and findings in an editable Dory Agent Run workspace.

It does not install the Dory CLI or configure MCP automatically. For live database access, connect Dory MCP from the main Dory documentation.

## Skill

- `dory`: Use Dory as an AI-native SQL workspace for database inspection, schema exploration, read-only SQL, Agent Runs, workspace tabs, saved queries, and result preservation.
