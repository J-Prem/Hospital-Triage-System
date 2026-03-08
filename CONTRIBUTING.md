# Contributing to MedLink AI Triage System

Thank you for your interest in contributing! 🎉

## How to Contribute

### 1. Fork & Clone

```bash
git clone https://github.com/YOUR_USERNAME/AI-TRIAGE-SYSTEM.git
cd AI-TRIAGE-SYSTEM
```

### 2. Create a Feature Branch

```bash
git checkout -b feature/your-feature-name
```

### 3. Set Up Your Environment

```bash
cp .env.example .env
# Fill in your Supabase credentials
npm install
npm run dev
```

### 4. Make Your Changes

- Follow the existing folder structure (`components/ComponentName/ComponentName.jsx`)
- Co-locate CSS files with their component
- Keep components focused and reusable

### 5. Commit & Push

```bash
git add .
git commit -m "feat: describe your change"
git push origin feature/your-feature-name
```

### 6. Open a Pull Request

Go to GitHub and open a PR against the `main` branch. Describe what you changed and why.

---

## Code Style

- Use **functional React components** with hooks
- Follow existing CSS naming conventions (BEM-like)
- Keep service/business logic in `src/services/`
- Keep data fetching logic in `src/hooks/`

## Reporting Bugs

Please use the [Bug Report](.github/ISSUE_TEMPLATE/bug_report.md) template when opening issues.

## Questions?

Open a [GitHub Discussion](https://github.com/YOUR_USERNAME/AI-TRIAGE-SYSTEM/discussions) or tag an issue with `question`.
