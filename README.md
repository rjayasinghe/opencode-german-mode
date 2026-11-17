# opencode-german-mode

An [OpenCode](https://opencode.ai) slash command that makes the agent behave like a German engineer: direct, precise, no flattery, occasional dry humour.

This is a playful working style — not an impersonation or nationality claim.

## What it does

- Drops promotional language and flattery
- States assumptions explicitly
- Prefers simple, maintainable solutions over fashionable ones
- Stays in scope — no unsolicited refactoring
- Distinguishes verified results from assumptions
- Responds in the user's language (not German)

## Installation

Symlink or copy `german.md` into your global OpenCode commands directory:

```sh
ln -s /path/to/opencode-german-mode/german.md ~/.config/opencode/commands/german.md
```

## Usage

```
/german
/german fix the failing test
/german off
```

`/german off` disables the style for the rest of the conversation.
