# ai-ddd-prompts-and-rules
DDD-related prompts and rules to use with your favourite coding assistants

## How to use AI prompts in different tools


| AI Tool           | How to Include Prompts                                                                                                                                                                                                                 |
|-------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Cursor**        | Add prompts as project rules inside the `.cursor/rules/` directory (e.g., `.cursor/rules/cursorrules.mdc`). For detailed guidance, refer to the [official Cursor rule guide](https://docs.cursor.com/context/rules-for-ai#project-rules-recommended). |
| **GitHub Copilot**| Create a `.github/copilot-instructions.md` file in your repository's root directory and add natural language instructions in Markdown format. These instructions will guide Copilot's behavior across your project. More information is available in the [GitHub Copilot documentation](https://docs.github.com/copilot/customizing-copilot/adding-custom-instructions-for-github-copilot). |
| **Junie**         | You can specify your coding style, best practices, and general preferences by specifying the guidelines in `.junie/guidelines.md` file so that Junie will follow these guidelines while generating code. More details available in [junie-guidelines](https://github.com/JetBrains/junie-guidelines) |


## How to contribute

1. Create a sub-folder in `/prompts` or `/rules` with a descriptive name e.g. `aggregate-testing-typescript`

2. Add your rules or prompt file in the sub-folder e.g. `/rules/aggregate-testing-typescript/aggregate-testing-typescript.mdc`

3. Add a `readme.md` contain a description and usage guidelines.
