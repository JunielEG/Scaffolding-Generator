# Scaffolding Generator

Collection of CLI tools for scaffolding projects in different languages.
Each tool follows the same philosophy: minimal setup, consistent structure,
and no dependencies beyond the language's own toolchain.

## Tools

| Tool       | Language | Status |
|------------|----------|--------|
| cpp-cli    | C++      | stable |
| ...        | ...      | ...    |

Each tool lives in its own folder and has its own README with usage details.

## Requirements

Each tool lists its own requirements. In general:
- Windows (PowerShell 5+)
- The language's compiler or runtime installed and on PATH

## Installation

Clone the repo and add the tool folder you want to your system PATH.

```bash
git clone https://github.com/JunielEG/Scaffolding-Generator.git
```

Then add the specific tool folder (e.g. cpp-cli/) to your PATH.
See each tool's README for the exact folder to add.

## Contributing

New tools are welcome. Each one should:
- Live in its own folder at the root
- Include a README following the same structure as the existing ones
- Work standalone without depending on other tools in this repo
      