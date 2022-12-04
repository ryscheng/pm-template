# pm-template

Issue trackers (e.g. GitHub issues, Jira, Shortcut, etc) are incredibly useful project-management tools for any team. However, they are proprietary closed systems, which means:
- **Difficult to customize**: Take it or leave it. As your team grows, your needs evolve. If the tool doesn't satisfy your needs, you are left with trying to migrate.
- **Annoying to transfer**: Migrations are painful. They often require custom scripts and never fully capture all of the metadata from the original system. 
- **Proprietary**: Open source code deserves open source project management. Projects should be able to move as easily as switching their `git remote`.

A nice middle ground is to consider using Notion or Airtable to build a custom process, which easily exports to Markdown or CSV files. Unfortunately, a key aspect of project management is linking (e.g. epics => tasks), which is lost when exporting to CSV.

## Goals

- **Portable**: All of the data should exist in a git repository, like your code. In the future, we can consider using standard content management systems as well.
- **Markdown-first**: Users should be able to use any editor that supports Markdown, from vim to HackMD.
- **Open-source tooling**: Anyone should be able to build visually-rich functionality (like Gantt charts), as a front-ends to the data.

As a first stab towards leveraging existing open-source tooling, this template is designed to integrate easily with personal knowledge systems (e.g. Obsidian, Foam, Dendron). This convention benefits from existing link/graph visualizations. By linking between epics, tasks, and authors, users can use these tools to easily navigate the data structure.

## Workflow

1. Fork this repository
2. Start writing 

TODO: discuss how this works in a Shortcut-like workflow

## Contributing

We welcome contributions! Please follow the guidelines in the pull request template.

## See also

- [pm-tools]()
