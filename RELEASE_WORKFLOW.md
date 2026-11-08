# 🔄 Release & Version Tracking Workflow

Use this operational protocol when updating the prompt architecture, adding capabilities, or bumping the semantic version string (e.g., to `v1.1.0`).

## Step 1: Update the Metadata Files
Before running Git commands, update the version identifiers in your source files:
1. Open `skill.md` and modify the frontmatter header block:
   ```yaml
   version: "1.1.0"
   ```
2. Open `README.md` and log your changes in a brief `## Changelog` section at the bottom.

## Step 2: Terminal Deployment Commands
Run these sequential commands in your Windows Command Prompt to commit your updates and create an official, immutable release tag on GitHub:

```cmd
:: 1. Stage all tracking configuration and file changes
git add .

:: 2. Commit the feature update with clear intent
git commit -m "feat: release version 1.1.0 with updated logic constraints"

:: 3. Create a lightweight local semantic version tag
git tag v1.1.0

:: 4. Push your code update branch up live
git push origin main

:: 5. Push the version tag cleanly to your GitHub releases timeline
git push origin v1.1.0
```

## 🏷️ Semantic Versioning Rules for AI Skills
- **Patch (1.0.X)**: Minor sentence adjustments, fixing spelling typos, or changing phrasing variables without modifying prompt rules.
- **Minor (1.X.0)**: Adding an entirely new mode (e.g., adding a "Parent-Only Consultation Mode") or injecting new local translation options.
- **Major (X.0.0)**: Complete structural architecture overhauls or deep changes to core safety bounds and system capabilities.
