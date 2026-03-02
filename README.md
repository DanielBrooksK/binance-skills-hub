# Binance Skills Hub

This repository contains Binance’s implementation of skills for interacting with Binance APIs.

Skills are self-contained folders of instructions and metadata that standardize how specific Binance API workflows are executed. Each skill focuses on a defined set of endpoints or use cases.

---

## About This Repository

Each skill lives in its own folder and contains a `SKILL.md` file with YAML frontmatter and structured instructions.

Browse the existing skills to understand patterns and naming conventions before contributing.

---

## Contribution

We welcome contributions.

To add a new skill:

1. **Fork the repository** and create a new branch:

   ```bash
   git checkout -b feature/binance-<skill-name>
   ```

2. **Create a new folder** containing a `SKILL.md` file.

3. **Follow the required format:**

   ```markdown
   ---
   title: Binance <Skill Name>
   description: A clear description of what the skill does and when to use it.
   metadata:
     - version: <Skill Version>
     - author: Binance
   license: MIT
   ---

   # Binance <Skill Name>

   [Add instructions, examples, and guidelines here]
   ```

4. **Open a Pull Request** to `main` for review.
   Once approved, the skill will be merged.

---

## Available Skills

* [Binance Spot](./skills/binance-spot/SKILL.md) – Skill for Spot API endpoints.
