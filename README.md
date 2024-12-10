# Lang2Shell

Lang2Shell is a Python package that allows users to execute shell commands by using natural language inputs. It leverages OpenAI's GPT models to interpret user queries and translates them into executable shell commands, making command-line interfaces more accessible and user-friendly.

---

## Features

- **Natural Language to Shell Commands**: Converts plain English commands like "Create a file named `example.txt`" into precise shell commands (e.g., `touch example.txt`).
- **Cross-Shell Compatibility**: Detects whether the user is in `zsh` or `bash` and generates shell-specific commands.
- **Error Handling and Safety**: Includes confirmation prompts before executing commands to ensure safe operation.
- **Dynamic and Flexible**: Adapts to a wide range of user inputs without requiring pre-defined mappings or rules.

---

## Installation

Lang2Shell can be installed via pip:

```bash
pip install lang2shell
