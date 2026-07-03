# Changelog

All notable changes to this project will be documented in this file.

This repository follows a simple versioning model:

```text
v1.0 -> v1.1 -> v1.2 -> ...
```

Each version should represent a meaningful improvement to the prompt workflow.

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

### v1.1

Potential improvements:

- Add special handling for mega project posts.
- Add support for banner-generation handoff.
- Add clearer rules for special project days that use more than one concept.
- Add example inputs and outputs.
- Add testing scenarios for common cases.
