# Zypharion Clients

**Zypharion Clients** is the central repository for organizing and maintaining all projects, tools, source code, configurations, assets, documentation, and releases created under Zypharion Studios.

The repository is designed as a long-term project library. It is not limited to one application or platform: new projects can be added at any time, existing projects can be updated, and every project should have a clear place in the folder structure.

## Main Categories

### Discord
Everything related to Discord:
- Discord bots and their source code
- Bot dashboards, websites, and APIs
- Server setups, configurations, and templates
- Embeds, icons, banners, and other assets
- Documentation, installation guides, and changelogs

### Minecraft
Everything related to Minecraft:
- Mods and mod source code
- Clients, tools, and utilities
- Configurations and resource packs
- Server-related projects and plugins
- Build files, release notes, and documentation

### Roblox
Everything related to Roblox:
- Roblox game projects
- Luau scripts and modules
- UI systems and assets
- Studio tools and reusable systems
- Project documentation and releases

### Web Development
Websites, web applications, dashboards, APIs, frontend and backend projects.

### AI Projects
AI tools, agents, experiments, integrations, and related source code.

### Other
Any project that does not fit into the categories above. This folder keeps the repository open to future platforms and ideas.

### Shared
Reusable assets, templates, libraries, and documentation that are used by multiple projects.

## Repository Structure

```text
zypharion-clients/
├── Discord/
│   ├── Bots/
│   ├── Dashboards/
│   ├── Servers/
│   ├── Assets/
│   └── Documentation/
├── Minecraft/
│   ├── Mods/
│   ├── Clients/
│   ├── Tools/
│   ├── Resource-Packs/
│   ├── Configs/
│   └── Servers/
├── Roblox/
│   ├── Games/
│   ├── Scripts/
│   ├── Assets/
│   ├── Tools/
│   └── Documentation/
├── Web-Development/
│   ├── Websites/
│   ├── Dashboards/
│   └── APIs/
├── AI-Projects/
│   ├── Agents/
│   ├── Tools/
│   └── Experiments/
├── Shared/
│   ├── Assets/
│   ├── Templates/
│   └── Libraries/
└── Other/
    ├── Projects/
    └── Experiments/
```

## Adding a Project

1. Choose the category that best matches the project.
2. Create a clearly named folder for the project.
3. Keep source code, configuration, assets, and documentation organized inside that project folder.
4. Add a project-level `README.md` explaining what the project does, its requirements, and how to use or build it.
5. Update the relevant documentation when making important changes.

If a project does not fit an existing category, place it in **Other** or create a new top-level category when it becomes useful.

## Naming and Organization

- Use clear, descriptive folder and file names.
- Keep each project independent and avoid mixing unrelated projects.
- Include version numbers in release artifacts where appropriate.
- Keep build output separate from source code.
- Add a changelog or release notes for projects with regular updates.

## Security

Never commit passwords, API keys, bot tokens, private keys, personal data, or other secrets. Store secrets in local environment files such as `.env`, and make sure those files are excluded through `.gitignore`. Provide an `.env.example` containing placeholder values when a project needs environment variables.

## Purpose

This repository is the central home for the Zypharion Studios ecosystem: Discord, Minecraft, Roblox, web development, AI projects, shared resources, and future creations.

**One organization. One repository. All Zypharion projects, clearly organized.**
