# Built-in features for lab-notebook-os

Purpose: scientific computing

1. **prepare study and research files** — run lab-notebook-os-workspace. It creates ~/Documents/lab-notebook-os-workspace/ with Notes, Sources, Assignments folders.
2. **plan a learning session** — run lab-notebook-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/lab-notebook-os-session-plans/.
3. **check study and source readiness** — run lab-notebook-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/lab-notebook-os-workspace features/lab-notebook-os-plan features/lab-notebook-os-check "$HOME/.local/bin/"
