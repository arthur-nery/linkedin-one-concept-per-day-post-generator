# Changelog

All notable changes to this project will be documented in this file.

This repository follows a simple versioning model:

```text
v1.0 -> v1.1 -> v1.2 -> ...
```

Each version should represent a meaningful improvement to the prompt workflow.

---

## [v1.1] - 2026-07-02

### Added

- Added Python 1 Per Day as the main current focus.
- Added a progression cycle for daily posts and quinzenal megaproject posts.
- Added Megaproject mode for Day 15, Day 30, Day 45, Day 60, and similar milestones.
- Added rules to keep Megaproject posts simple, honest, beginner-friendly, and portfolio-focused.
- Added rules for explaining the real pain behind the project and its simple MVP.
- Added rules for citing limitations and future improvements without exaggeration.
- Added a complementary indication/inspiration module before generating the final post.
- Added the standard command: `LinkedIn Formatter, execute`.

### Changed

- Shifted the prompt focus from a general Ruby/Python LinkedIn post generator to a Python 1 Per Day formatter.
- Improved the distinction between normal daily posts and special project posts.
- Improved GitHub link handling for both daily exercises and Megaprojects.
- Updated the current prompt file to `prompt/linkedin-formatter-python-1-per-day-v1.1.md`.

---

## [v1.0] - 2026-07-02

### Added

- Initial version of the LinkedIn daily post generator prompt.
- Support for Ruby and Python learning progress posts.
- Fixed narrative structure for public learning posts.
- Rules for notebook photos, Nano screenshots, Termux outputs, loose explanations, and GitHub file links.
- Rule to ask for the GitHub file link before generating the post when the link is missing.
- Rule to avoid including full code inside the LinkedIn post.
- Rule to focus each post on only one main concept.
- Hashtag structure with up to 6 hashtags.
- Style rules for simple, honest, beginner-friendly writing.

### Notes

This version is based on the initial working prompt used to generate daily LinkedIn posts for the programming learning progression.

---

## Planned

### v1.2

Potential improvements:

- Add support for banner-generation handoff.
- Add clearer rules for visual post assets.
- Add example inputs and outputs for daily posts.
- Add example inputs and outputs for Megaproject posts.
- Add testing scenarios for common cases.
