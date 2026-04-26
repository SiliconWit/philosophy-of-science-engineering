---
title: "Philosophy of Science and Engineering - Collaboration Guide"
description: "Contributing guide for Philosophy of Science and Engineering course content"
tableOfContents: true
sidebar:
  order: 999
---

# Philosophy of Science and Engineering

![Build](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Contributors Welcome](https://img.shields.io/badge/contributors-welcome-orange)

**Read this course at:** [https://siliconwit.com/education/philosophy-of-science-engineering/](https://siliconwit.com/education/philosophy-of-science-engineering/)

Nine lessons on what makes something scientific, how knowledge evolves, the limits of models, engineering ethics, and the relationship between technology and society. Grounded in real engineering examples.

## Lessons

| # | Title |
|---|-------|
| 1 | What Makes Something Scientific? |
| 2 | The Scientific Method in Engineering Practice |
| 3 | Falsifiability: Testing to Fail |
| 4 | Paradigm Shifts: How Engineering Knowledge Evolves |
| 5 | Models, Maps, and Reality |
| 6 | Uncertainty and the Limits of Knowledge |
| 7 | Ethics and Responsibility in Engineering |
| 8 | Technology, Society, and Unintended Consequences |
| 9 | Thinking Like a Scientist-Engineer |

## How to Contribute

All commands below work on Linux, macOS, and Windows (using Git Bash, PowerShell, or Command Prompt with Git installed).

### For Team Members (with push access)

**First time setup (clone the repo once):**

```bash
git clone https://github.com/SiliconWit/philosophy-of-science-engineering.git
cd philosophy-of-science-engineering
```

**Every time you start working:**

```bash
git pull origin main
```

Always pull before making changes. This avoids conflicts with other contributors.

**After making your changes:**

```bash
git add .
git commit -m "Brief description of what you changed"
git push origin main
```

**If you get a push error** (someone pushed before you):

```bash
git pull origin main
```

Git will merge the changes automatically in most cases. If there is a conflict, Git will mark the conflicting lines in the file. Open the file, choose which version to keep, then:

```bash
git add .
git commit -m "Resolve merge conflict"
git push origin main
```

**Tips to avoid conflicts:**

- Always `git pull origin main` before you start working
- Push your changes as soon as you are done, do not hold onto uncommitted work for long
- Coordinate with other contributors so two people are not editing the same file at the same time

### For External Contributors (without push access)

1. Fork the repository: [SiliconWit/philosophy-of-science-engineering](https://github.com/SiliconWit/philosophy-of-science-engineering)
2. Clone your fork:
   ```bash
   git clone https://github.com/YOUR-USERNAME/philosophy-of-science-engineering.git
   cd philosophy-of-science-engineering
   ```
3. Make your changes and commit:
   ```bash
   git add .
   git commit -m "Brief description of what you changed"
   git push origin main
   ```
4. Open a Pull Request against `main` on the original repository
5. Describe what you changed and why in the PR description

## Content Standards

- `.mdx` format, no BionicText, no emojis, no em dashes
- Real engineering case studies and examples
- Accessible tone, practical takeaways

## License

[MIT License](LICENSE)
