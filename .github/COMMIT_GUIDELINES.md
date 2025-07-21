# 📦 Commit Guidelines

To ensure a clean, readable, and meaningful project history, LaraSQ Kit follows the [Conventional Commits](https://www.conventionalcommits.org/) specification. Please read and follow these guidelines for every commit.

---

## Why Conventional Commits?

- 📖 **Readable History:** Makes it easy to understand what and why changes were made.
- 🚦 **Automated Releases:** Enables semantic versioning and changelog generation.
- 🔍 **Easier Collaboration:** Helps reviewers and contributors quickly scan for relevant changes.

---

## Commit Message Format

Each commit message **must** be structured as follows:

```text
<type>(optional-scope): short, imperative summary

[optional body]

[optional footer(s)]
```

- **type**: The kind of change (see valid types below)
- **scope**: (Optional) The section or module affected (e.g., `auth`, `api`, `docs`)
- **summary**: A concise, imperative description (max 72 characters)
- **body**: (Optional) More detailed explanation, wrapped at 100 chars
- **footer**: (Optional) For breaking changes or issue references

---

## Valid Commit Types

- `feat`:     ✨ A new feature
- `fix`:      🐛 A bug fix
- `docs`:     📝 Documentation only changes
- `style`:    🎨 Code style (formatting, missing semi colons, etc.)
- `refactor`: 🔨 Code change that neither fixes a bug nor adds a feature
- `test`:     🧪 Adding or correcting tests
- `chore`:    🔧 Maintenance tasks (build, deps, etc.)

---

## Examples

```bash
feat(auth): add Google login option

fix(api): handle null responses in user endpoint

refactor(user): simplify user creation logic

docs(readme): update setup instructions

style(ui): format button component code

test(settings): add tests for password update

chore(deps): update React to v18
```

---

## Best Practices

- Use the **imperative mood**: "fix bug" not "fixed bug" or "fixes bug"
- Keep the summary short and descriptive (max 72 chars)
- Use the body to explain **why** a change was made, if not obvious
- Reference issues in the footer (e.g., `Closes #123`)
- For breaking changes, add a footer: `BREAKING CHANGE: ...`

---

## Resources

- [Conventional Commits](https://www.conventionalcommits.org/)
- [Semantic Release](https://semantic-release.gitbook.io/semantic-release/)

Thank you for helping keep our history clean and meaningful! 🙏 
