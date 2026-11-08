# Contributing to Tennis Mind Coach 🎾🧠

Thank you for your interest in helping improve the Tennis Mind Coach AI skill! We welcome contributions from developers, product managers, and sports psychologists to make this tool more effective, portable, and accessible.

## 👥 How to Contribute Safely

### 1. Reporting Edge Cases
If you notice the AI giving strange advice, losing its persona, or violating match rules, please open an **Issue** using our standard template rather than editing the file directly.

### 2. Suggesting Phrasing or Logic Updates
To update prompt instructions:
1. **Fork** this repository to your own account.
2. Create a new branch for your feature or fix (e.g., `git checkout -b fix/goldfish-memory-phrasing`).
3. Make your modifications inside `skill.md` or the `README.md`.
4. Ensure your updates strictly follow our core constraints (see below).
5. Submit a **Pull Request (PR)** tracking back to our `main` branch.

## ⚖️ Strategic Constraints for Submitting PRs
To protect the integrity of the project, all Pull Requests must respect these core structural boundaries:

- **Authorship Preservation**: The MIT License header tracking authorship to Rajeev Mankar must remain completely unchanged.
- **Strict Universal Portability**: Do not inject platform-specific code or proprietary wrappers (like specific OpenAI actions or Claude-only formatting tags) inside `skill.md`. The core file must remain clean, platform-agnostic Markdown.
- **Safety Boundaries**: Under no circumstances should updates weaken Section 11 (Boundaries and Safety). The AI must always refuse to act as a medical professional or clinical therapist.

---
Thank you for helping scale this open-source asset!
