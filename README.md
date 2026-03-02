# Binance Skills Hub

Binance Skills Hub is an open skills marketplace that gives AI agents native access to crypto: both centralized and decentralized. Search tokens, execute trades, track wallets, monitor signals, and interact with DeFi protocols, all through natural language.

Built by Binance. Built for everyone.

We're not building this just for Binance products. Skills Hub is designed for the entire crypto ecosystem: any agent, any framework, any chain. Whether you're building on LangChain, CrewAI, or your own stack, your agents can plug into crypto with a few lines of config.

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
   git checkout -b feature/<skill-name>
   ```

2. **Create a new folder** containing a `SKILL.md` file.

3. **Follow the required format:**

   ```markdown
   ---
   title: <Skill Name>
   description: A clear description of what the skill does and when to use it.
   metadata:
     - version: <Skill Version>
     - author: <Your Github Username>
   license: MIT
   ---

   # <Skill Name>

   [Add instructions, examples, and guidelines here]
   ```

4. **Open a Pull Request** to `main` for review.
   Once approved, the skill will be merged.
