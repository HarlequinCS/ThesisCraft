# Ultimate Humanizer

Ultimate Humanizer is a Claude Code and OpenCode skill for rewriting AI-sounding prose into clearer, more natural writing.

It is designed for:

- thesis writing
- academic reports
- technical documentation
- general prose cleanup

It preserves meaning, citations, terminology, and argument structure while removing common AI writing tells.

## What it does

- Detects AI writing patterns such as significance inflation, promotional language, filler, and chatbot phrasing
- Preserves citations and technical terms
- Supports Malaysian C1 academic English
- Calibrates to a user sample when one is provided
- Avoids hallucinations and fabricated references

## Installation

### OpenCode

Clone this repository into OpenCode's skills directory:

```bash
mkdir -p ~/.config/opencode/skills
git clone https://github.com/HarlequinCS/ThesisCraft.git ~/.config/opencode/skills/humanizer
```

Or copy just the skill file if you already cloned the repo:

```bash
mkdir -p ~/.config/opencode/skills/humanizer
cp skills/humanizer/SKILL.md ~/.config/opencode/skills/humanizer/SKILL.md
```

### Claude Code

Clone or copy the same skill file into `~/.claude/skills/humanizer/`.

## How to use

### In OpenCode

```text
/humanizer

[paste your text]
```

### In Claude Code

```text
/humanizer

[paste your text]
```

### For file editing

Point the tool at the file you want rewritten, or paste the file contents directly.

## Recommended workflow

1. Paste the text you want rewritten.
2. If you have a sample of your own writing, include it for voice matching.
3. Ask for the final version only if you do not need an audit.
4. Review the output for meaning, citations, and tone.

## Safety and legal notes

- The skill itself is a Markdown prompt. It does not collect data or make network calls.
- You are responsible for checking the final text before publishing.
- Keep citations, quotations, and factual claims exactly where they belong.
- The repository is provided under the MIT License.

## Repository layout

```text
skills/humanizer/SKILL.md
LICENSE
README.md
CONTRIBUTING.md
SECURITY.md
```

## Attribution

This skill is inspired by and compatible with the broader humanizer family, including Blade Humanizer, Aboudjem Humanizer, and Academic Humanizer.
