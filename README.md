# LinkedIn One Concept Per Day Post Generator

A periodically updated prompt repository for generating simple, honest LinkedIn posts from daily Ruby and Python learning progress, using notebook photos, Nano screenshots, Termux outputs, and GitHub file links.

---

## What Is This

**LinkedIn One Concept Per Day Post Generator** is a prompt system designed to transform daily programming study evidence into LinkedIn posts.

It is focused on a public learning routine where each post documents one concept studied per day.

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

- Ruby on Rails;
- Python.

The prompt avoids sounding overly senior, avoids advanced tutorials, and keeps the focus on real learning, simple practice, and consistency.

---

## How It Works

The prompt follows a fixed workflow:

1. Analyze notebook photos.
2. Analyze code screenshots from Nano.
3. Analyze terminal outputs from Termux.
4. Identify the day of the learning progression.
5. Identify the programming language.
6. Identify the main concept of the day.
7. Use the visible code only to understand the exercise.
8. Avoid copying the full code into the post.
9. Ask for the GitHub file link if it was not provided.
10. Generate a ready-to-copy LinkedIn post.

---

## Core Rules

The generated post must:

- use simple and honest language;
- sound like a beginner documenting real progress;
- focus on only one concept per day;
- avoid full code blocks;
- use the GitHub link instead of copying code;
- end with `One step at a time.`;
- use up to 6 hashtags;
- avoid inventing details not visible in the images or explanation.

---

## Versioning

This repository is designed to be updated periodically.

The first version is:

- `v1.0` — initial daily LinkedIn post generator prompt.

Future versions may improve:

- GitHub link handling;
- support for special project days;
- banner generation handoff;
- clearer rules for mega projects;
- better handling of ambiguous images;
- better separation between daily posts and special posts.

---

## Quick Start

Use the prompt file from the `prompt/` folder.

Current version:

```text
prompt/linkedin-one-concept-per-day-post-generator-v1.0.md
```

Send the prompt to ChatGPT or another LLM, then provide:

- photos of the notebook;
- screenshots of the code;
- screenshots of the terminal result;
- a short explanation if needed;
- the GitHub file link.

The model should return a LinkedIn post in Markdown, without including the full code.

---

## Example Use Case

A daily Python post may use:

- a notebook photo explaining `print()`;
- a Nano screenshot showing `dia_01.py`;
- a Termux screenshot showing the result;
- a GitHub link to the file.

The generated post should explain the concept in simple words and present the learning progress without sounding advanced.

---

## Project Status

Current status: **v1.0 active**.

This is the initial version of the prompt and may evolve as the public learning workflow becomes more complete.

---

## Roadmap

Planned improvements:

- Add `v1.1` with special handling for mega project posts.
- Improve banner-generation handoff instructions.
- Add examples for Python and Ruby posts.
- Add tests with real post scenarios.
- Add clearer rules for commit/GitHub link updates.

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
prompt/linkedin-one-concept-per-day-post-generator-v1.0.md
```

---

## Related Repositories

- [`python-1-per-day`](https://github.com/arthur-nery/python-1-per-day)
- [`ruby-1-per-day`](https://github.com/arthur-nery/ruby-1-per-day)
- [`universal-prompt-engine`](https://github.com/arthur-nery/universal-prompt-engine)

---

## Inspiration

This repository follows the same public-learning and versioning logic used in the daily programming progression repositories, but with a different goal: generating LinkedIn posts from real study evidence.
