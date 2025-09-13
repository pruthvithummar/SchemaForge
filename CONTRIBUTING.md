🤝 Contributing to SchemaForge

First off, thanks for taking the time to contribute! 🎉
SchemaForge is an open-source AI-native data infrastructure platform, and community contributions help us move faster.

🛠️ How Can I Contribute?
1. Reporting Bugs 🐛

Check the issues
 to see if it’s already reported.

Open a new issue with:

Clear title and description.

Steps to reproduce.

Expected vs. actual behavior.

Logs, screenshots, or error messages if possible.

2. Suggesting Features 💡

Open a feature request issue
.

Describe your use case and why it matters.

3. Code Contributions 👨‍💻👩‍💻

Fork the repo.

Create a feature branch:

git checkout -b feat/your-feature


Make your changes (ensure code is formatted and tested).

Commit with a clear message:

git commit -m "feat: add schema evolution API"


Push your branch and open a Pull Request (PR).

📐 Code Style

Language: TypeScript (backend, CLI), Next.js + Tailwind (frontend).

Use ESLint + Prettier (configured in repo).

Write clear, typed functions and avoid duplication.

✅ Pull Request Guidelines

Keep PRs focused (1 feature/bug per PR).

Update/add tests for new code.

Update docs (README, examples) if relevant.

PR title should follow Conventional Commits
:

feat:, fix:, docs:, chore:

🧪 Running Locally
# Clone fork
git clone https://github.com/yourusername/schemaforge.git
cd schemaforge

# Start dev environment
docker-compose up --build
