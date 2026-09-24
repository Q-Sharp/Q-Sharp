# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

This is the GitHub **profile README** repository for the user `Q-Sharp` (remote: `github.com/Q-Sharp/Q-Sharp`). GitHub renders `README.md` from a repo named after the account on the profile page at `github.com/Q-Sharp`. Despite the name, it has nothing to do with Microsoft's Q# quantum language.

The only tracked file is `README.md`. There is no build, lint, or test tooling, and no dependencies. Changes are verified by viewing the rendered Markdown on GitHub.

## README structure

The profile is meant to be shown to recruiters and employers, so every claim in it must be backed by the public GitHub record: the profile bio, the user's own repos, and merged PRs in other repos. Don't invent roles, years of experience, employers, or contact details.

- **Intro** restates the GitHub bio ("software architect, C# developer and devops engineer", Germany) and keeps the motto "I <3 simple solutions".
- **Open Source Contributions** is a table of external repos where the user has merged PRs. Each row has a live star badge (`img.shields.io/github/stars/<owner>/<repo>?style=flat-square`) and a summary of the PRs. `gh search prs --author Q-Sharp --merged` lists candidates.
- **Projects** lists the user's own repos, each with a one-line description based on that repo's README.
- **Tech Stack** is grouped under bold category labels (Languages, Frameworks, Cloud & DevOps, Databases & Search, APIs & Tools, Platforms). Within a group, badges sit on consecutive lines so they render inline. Community sites, consumer apps, and privacy/crypto tools were removed deliberately to keep the profile professional.

## Badge conventions

Every badge uses the shields.io static badge format with `style=for-the-badge`:

```markdown
![AltText](https://img.shields.io/badge/<label>-<hexcolor>.svg?style=for-the-badge&logo=<logo>&logoColor=<color>)
```

When you add or edit a badge, follow the shields.io escaping rules the existing badges already use:
- A literal `-` in the label is written as `--` (for example, `XDA--Developers`).
- Spaces are written as `%20` (for example, `Microsoft%20SQL%20Server`).
- `#` in a color is written as `%23` (for example, `%23239120`).
- `logo` takes a Simple Icons slug, such as `c-sharp`, `microsoftazure`, or `githubactions`.
