# Claude Skills

A collection of [Claude Code](https://docs.anthropic.com/en/docs/claude-code) skills that enhance the agent with specialized knowledge for frontend development, React, TypeScript, and skill discovery.

## Skills

### find-skills

Helps discover and install agent skills interactively. Search for skills by keyword, browse categories (Web Dev, Testing, DevOps, etc.), and install them with a single command.

### frontend-design

Create distinctive, production-grade frontend interfaces with high design quality. Covers bold aesthetic directions (minimalist, brutalist, retro-futuristic, etc.), typography, color, motion, and spatial composition — designed to avoid generic AI aesthetics.

### react-best-practices

React patterns for hooks, effects, refs, and component design. Covers when to use (and not use) Effects, dependency management, cleanup patterns, custom hooks, and controlled vs uncontrolled components. Includes a decision tree for choosing the right pattern.

### react-components

Converts [Stitch](https://www.stitch.design/) designs into modular Vite + React components. Handles design retrieval, Tailwind CSS theme mapping, AST-based validation, and modular architecture (separate files for components, hooks, and mock data).

### typescript-advanced-types

Advanced TypeScript type system guidance: generics, conditional types, mapped types, template literal types, utility types, type inference, and type testing. Includes patterns for type-safe event emitters, API clients, builders, and form validation.

## Installation

Clone the repo into your Claude Code skills directory:

```sh
git clone https://github.com/ecoologic/claude-skills.git ~/.claude/skills
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
