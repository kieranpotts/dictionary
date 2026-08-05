# Dictionary

Custom spelling dictionary word lists (`en-US`, `en-GB`) used by the
[Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
VS Code extension. Consumers symlink or reference these files directly
from `cSpell.customDictionaries` settings — see `README.md` for the
exact settings and symlink commands for Windows/WSL.

## Tech stack

- Plain-text word lists (one word per line), consumed by the Code Spell
  Checker VS Code extension.

## Project structure

- **`src/en-US.txt`** \
  American English custom dictionary.

- **`src/en-GB.txt`** \
  British English custom dictionary.

## References

- **[TS-9: Version Control](https://raw.githubusercontent.com/kieranpotts/standards/refs/heads/latest/dev/src/009/AGENTS.md)**
