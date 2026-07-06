# LinkedIn One Concept Per Day Post Generator

A periodically updated prompt repository for generating simple, honest LinkedIn posts from daily programming learning progress, using notebook photos, Nano screenshots, Termux outputs, and GitHub file links.

---

## What Is This

**LinkedIn One Concept Per Day Post Generator** is a prompt system designed to transform daily programming study evidence into LinkedIn posts.

It is focused on a public learning routine where each post documents one programming concept per day, with special milestone posts for simple megaprojects.

The prompt receives inputs such as:

- notebook photos;
- Nano screenshots;
- Termux outputs;
- loose explanations;
- GitHub file links.

Then it generates a simple LinkedIn post that sounds human, beginner-friendly, honest, and aligned with a long-term public portfolio.

---

## Project Objective

The objective of this repository is to document and improve a reusable prompt for creating LinkedIn posts based on daily programming progress.

The current focus is:

- Python;
- GitHub;
- Terminal;
- Linux/Termux;
- learning in public;
- portfolio building.

Ruby on Rails may still be mentioned as part of the broader stack, but the current daily progression focus is **Python 1 Per Day**.

---

## How It Works

The prompt follows a fixed workflow:

1. Analyze notebook photos.
2. Analyze code screenshots from Nano.
3. Analyze terminal outputs from Termux.
4. Identify the day of the learning progression.
5. Identify whether the post is a daily post or a megaproject post.
6. Identify the programming language.
7. Identify the main concept of the day, when it is a normal daily post.
8. Identify the project objective, when it is a megaproject post.
9. Use the visible code only to understand the exercise.
10. Avoid copying the full code into the post.
11. Ask for the GitHub file link if it was not provided.
12. Ask whether there was any inspiration, suggestion, or indication from someone.
13. Ask whether there is a specific observation to include in the final observation field.
14. Generate a ready-to-copy LinkedIn post.

---

## Core Rules

The generated post must:

- use simple and honest language;
- sound like a beginner documenting real progress;
- focus on only one concept for normal daily posts;
- treat megaproject posts as integration milestones, not advanced systems;
- avoid full code blocks;
- use the GitHub link instead of copying code;
- ask the two required pre-publication questions before generating the final post;
- include a short final observation field;
- end with `One step at a time.`;
- use up to 6 hashtags;
- avoid inventing details not visible in the images or explanation.

---

## Progression Cycle

The current cycle is:

```text
Days 1-14  -> daily posts with 1 concept per day
Day 15     -> special megaproject post
Days 16-29 -> daily posts with 1 concept per day
Day 30     -> special megaproject post
Repeat
```

The megaproject is not meant to be a large professional system. It is a simple integration project that connects what was learned so far.

---

## Versioning

This repository is designed to be updated periodically.

Available versions:

- `v1.0` — initial daily LinkedIn post generator prompt.
- `v1.1` — Python 1 Per Day formatter with special megaproject workflow.
- `v1.1.1` — enxuto version of v1.1, reduced to fit an 8k character limit.
- `v1.1.2` — enxuto version with two required questions before generating the final post: inspiration/indication and final observation.

Future versions may improve:

- banner generation handoff;
- clearer rules for visual post assets;
- real examples from published posts;
- testing scenarios for daily posts and megaproject posts;
- GitHub link and commit handling.

---

## Quick Start

Use the latest prompt file from the `prompt/` folder.

Current version:

```text
prompt/linkedin-formatter-python-1-per-day-v1.1.2-enxuto.md
```

Send the prompt to ChatGPT or another LLM, then provide:

- photos of the notebook;
- screenshots of the code;
- screenshots of the terminal result;
- a short explanation if needed;
- the GitHub file link.

The model should ask the two required pre-publication questions before returning the final LinkedIn post in Markdown, without including the full code.

---

## Example Use Cases

A daily Python post may use:

- a notebook photo explaining `print()`;
- a Nano screenshot showing `dia_01.py`;
- a Termux screenshot showing the result;
- a GitHub link to the file.

A megaproject post may use:

- a notebook photo explaining the project idea;
- a Nano screenshot showing the project file;
- Termux screenshots with test runs;
- a GitHub link to the megaproject file.

The generated post should explain the progress in simple words and avoid sounding advanced.

---

## Project Status

Current status: **v1.1.2 active**.

The prompt now supports normal daily posts and special megaproject posts for the Python 1 Per Day progression, with an enxuto version designed for environments with an 8k character limit. The active version also requires two questions before generating the final post: one about inspiration/indication and one about the final observation field.

---

## Roadmap

Planned improvements:

- Add banner-generation handoff instructions.
- Add examples for normal Python posts.
- Add examples for megaproject posts.
- Add tests with real post scenarios.
- Add clearer rules for commit/GitHub link updates.
- Add examples for the final observation field.

---

## Author

Created by **Arthur Nery**.

GitHub: [arthur-nery](https://github.com/arthur-nery)

---

## License

This project is licensed under the MIT License.

See the `LICENSE` file for details.

---

## Main Prompt File

```text
prompt/linkedin-formatter-python-1-per-day-v1.1.2-enxuto.md
```

---

## Previous Versions

```text
prompt/linkedin-one-concept-per-day-post-generator-v1.0.md
prompt/linkedin-formatter-python-1-per-day-v1.1.md
prompt/linkedin-formatter-python-1-per-day-v1.1.1-enxuto.md
```

---

## Related Repositories

- [`python-1-per-day`](https://github.com/arthur-nery/python-1-per-day)
- [`ruby-1-per-day`](https://github.com/arthur-nery/ruby-1-per-day)
- [`universal-prompt-engine`](https://github.com/arthur-nery/universal-prompt-engine)

---

## Inspiration

This repository follows the same public-learning and versioning logic used in the daily programming progression repositories, but with a different goal: generating LinkedIn posts from real study evidence.
