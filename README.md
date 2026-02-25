# Claude Skills

A collection of [Claude Code](https://docs.anthropic.com/en/docs/claude-code) skills that enhance the agent with specialized knowledge for frontend development, React, TypeScript, and skill discovery.

## Installation

Clone the repo into your Claude Code skills directory:

```sh
git clone git@github.com:ecoologic/ai-agents.git
ln -s "$(pwd)/ai-agents/skills" ~/.claude/skills
```

Or install individual skills using the [Skills CLI](https://github.com/anthropics/skills):

```sh
npx skills install <skill-name>
```

## Usage

Once installed, skills are automatically available in Claude Code. They activate based on context — for example, `react-best-practices` triggers when reading or writing `.tsx`/`.jsx` files with React imports.

You can also invoke skills explicitly:

- Ask "find a skill for X" to trigger `find-skills`
- Ask to "build a landing page" to trigger `frontend-design`

## Contributing

Contributions are welcome. Feel free to open an issue or submit a pull request.

## License

[MIT](LICENSE)
