# my-claude-skills

Personal collection of AI agent skills (SKILL.md format)

Built for my own use; public in case it helps someone.

## Install

```bash
git clone <this repo>
cp -r skills/* ~/.claude/skills/
```

## Examples

```bash
# skills trigger automatically on matching tasks
# or invoke directly: /code-review
```

## What it does

- Versioned like code: review changes in PRs
- Each skill is a folder with a single SKILL.md
- Drop-in compatible with ~/.claude/skills
- YAML frontmatter: name + when-to-use description
- Concrete instructions, output formats and examples

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── dependabot.yml
├── docs/
│   ├── development.md
│   ├── faq.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── skills/
│   ├── code-review/
│   │   └── SKILL.md
│   ├── commit-message/
│   │   └── SKILL.md
│   ├── refactor-plan/
│   │   └── SKILL.md
│   └── test-writer/
│       └── SKILL.md
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── Makefile
└── SECURITY.md
```

## License

MIT. Do whatever you want.
