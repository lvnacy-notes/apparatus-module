# Apparatus Module

A general module framework for the LVNACY Obsidian Apparatus. This module serves as a foundation and template for creating specialized modules within an Apparatus Obsidian Vault.

## Overview

The Apparatus Module is designed to be installed in an Apparatus Obsidian Vault as a git submodule. Apparatus Vaults provide templated scaffolding and automated scripts for creating and managing specialized project modules. This repository serves as a blank slate to generate a scaffold.

The Apparatus philosophy is built around modular, compartmentalized project structures. As various module templates, scripts, and tools are completed, this README will be expanded with instructions for each type.

## Why Modules?

The Apparatus uses a **compartmentalization model** for managing different types of content and projects. This approach offers several key benefits:

### Modular Architecture
Each module maintains its own independent git repository and version control history. This separation means you can track changes specific to each module without cluttering the main vault's history.

### Portability
Because modules are self-contained units with their own version control, they can be easily shared, moved, or reused across different Apparatus vaults or even different Obsidian installations. A module that works in one vault will work in another without modification.

### Scalability
The compartmentalization model allows the Apparatus ecosystem to grow. Different module types—for story development, context libraries, image libraries, research databases, and more—can be added independently without affecting existing modules or the core vault structure.

## How to Use This Repository

To create a new project using available module templates:

### First, Install the Module

Select "Use this template" to copy this repository as a new module. Then add your module to your Apparatus Obsidian Vault using git:

```bash
git submodule add https://github.com/lvnacy-notes/apparatus-story-module.git story-module
```

This module is designed to work within the broader Apparatus ecosystem. If installing in a vault that is not specifically an Apparatus Vault, ensure you have the [Templater][templater], [Dataview][dataview], [Folder Note][folder-notes], and [Custom File Explorer Sort][custom-sort] plugins installed and configured in your vault before using the scaffolding templates. You can copy over the necessary Apparatus templates, scripts, and plugins from the [Apparatus Vault Template][apparatus].

### Then, Generate the Module

1. Make sure this README is active in your editor in an Apparatus Vault
2. Use the **Templater** command palette
3. Select `Templater: Open insert template modal`
4. Browse available module scaffolds based on your project type
5. Select the scaffold for the module type you wish to generate

#### Currently available module scaffolds

- **Story Scaffolding** (`story-scaffold`): Generates a complete writing and revision structure for story development. Includes project specification, editorial workflow, and revision phase organization with dashboards to track scene progression through the editorial process. Leverages the **[Longform][longform]** plugin.

**Coming soon:**
- Additional module templates and specialized scaffolding tools
- Enhanced plugin and script support
- Expanded documentation for each module type

Additional module types and templates will be added as they are developed.

## What's Included

In this repository? Absolutely fucking nothing. All of the tooling exists in the Apparatus Vault template. You can create a new blank repo to use as a module and install that, then run the commands. You need only a blank note in the module directory from which to run the scaffold commands. It's that easy.

## Future Development

This README will be expanded as additional module templates, scripts, and plugins are completed. The Apparatus is an evolving system designed to support multiple types of creative and informational projects.

---

For more information about the LVNACY Obsidian Apparatus architecture and philosophy, see the main apparatus documentation in your Apparatus Vault.

<!-- Links -->
[apparatus]: https://github.com/lvnacy-notes/apparatus-vault-template
[custom-sort]: https://github.com/SebastianMC/obsidian-custom-sort
[dataview]: https://github.com/blacksmithgu/obsidian-dataview
[folder-notes]: https://github.com/LostPaul/obsidian-folder-notes
[longform]: https://github.com/kevboh/longform
[templater]: https://github.com/SilentVoid13/Templater