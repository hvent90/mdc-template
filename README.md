# Rule Set Template - Cursor MDC Explorer 

This template helps you create `.mdc` rule sets for the Cursor MDC Explorer.

## Quick Start

1.  **Fork this Repository.**
2.  **Clone your fork** to your local machine.
3.  **Customize `rules.mdc`:**
    *   Edit the **metadata** (YAML frontmatter at the top). Pay close attention to the `name` field, as this will be used as the basis for the local filename when downloaded.
    *   Write your **MDC rules** below the metadata.
4.  **Update `README.md` (this file in *your* fork):** Describe *your* rule set for other users.
5.  **Commit & Push** your changes to your repository.
6.  **Publish:** Submit your repository URL to the MDC Explorer in Cursor (once available).

## `rules.mdc` File - Key Requirements

This file is essential. It **must**:

*   Be named exactly `rules.mdc`.
*   Be at the **root** of your repository.
*   Start with a YAML metadata block (`---` ... `---`).

### Metadata in `rules.mdc`:

```yaml
---
name: "Your Rule Set Name"           # REQUIRED: Displayed in the Explorer and used as the local filename.
# version: "1.0.0"                   # Optional: e.g., 1.0.0
# description: "What your rules do." # Optional: Brief explanation.
# authorGitHub: "your_username"      # Optional: Your GitHub username.
# tags: ["relevant", "keywords"]     # Optional: Helps discovery in the explorer.
---

# Your .mdc rules go below this line.
```

## Publishing Notes

*   Your repository **must be public**.
*   For detailed `.mdc` syntax, see the official Cursor documentation.
*   Consider adding a `LICENSE` file to your repository.

That's it! Customize `rules.mdc` and this README in your fork.
