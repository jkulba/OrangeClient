# AEM Client 

Built with AstroJs

- With support for React components
- With support for Tailwind CSS

## 🧞 Project Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## Code Quality with Biome

This project uses [Biome](https://biomejs.dev/) for linting and formatting.

### VS Code Extension

Install the official Biome extension for VS Code:
- **Extension ID**: `biomejs.biome`
- Install via VS Code: Search for "Biome" in the Extensions marketplace

### Installation

Install Biome as a dev dependency:

```bash
npm install --save-dev --save-exact @biomejs/biome
```

Initialize Biome configuration:

```bash
npx @biomejs/biome init
```

### Biome Commands (code formatting)

| Command                          | Action                                              |
| :------------------------------- | :-------------------------------------------------- |
| `npx @biomejs/biome check`       | Check for formatting and linting issues             |
| `npx @biomejs/biome check --write` | Check and automatically fix issues                |
| `npx @biomejs/biome format`      | Format code without fixing lint issues              |
| `npx @biomejs/biome format --write` | Format and write changes to files                |
| `npx @biomejs/biome lint`        | Run only linting checks                             |

