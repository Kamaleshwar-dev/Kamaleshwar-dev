# GitHub Profile Setup

## 1. Replace placeholders

In VS Code, press `Ctrl + Shift + H` and replace:

- `YOUR_GITHUB_USERNAME`
- `YOUR_PORTFOLIO_URL`
- `YOUR_LINKEDIN_URL`
- `YOUR_INSTAGRAM_URL`
- `YOUR_DEMO_URL`

## 2. Create the special repository

Create a new **public** GitHub repository whose name exactly matches your GitHub username.

Example:

```text
Username: kamalesh-dev
Repository: kamalesh-dev
```

Enable **Add a README file** only if you are not pushing this package immediately.

## 3. Push from VS Code

```bash
git init
git add .
git commit -m "feat: create professional GitHub profile"
git branch -M main
git remote add origin https://github.com/YOUR_GITHUB_USERNAME/YOUR_GITHUB_USERNAME.git
git push -u origin main
```

## 4. Enable the contribution animation

Open the repository on GitHub:

```text
Settings → Actions → General → Workflow permissions
```

Choose **Read and write permissions**, save it, then open:

```text
Actions → Generate contribution snake → Run workflow
```

After the workflow completes, an `output` branch will contain the SVG.

## 5. Complete profile settings

Use this bio:

```text
Founder @ Zentronix Developers • Full Stack Developer • Building modern Web, Mobile & IoT solutions
```

Suggested profile fields:

- Name: Kamalesh
- Company: Zentronix Developers
- Location: Chennai, India
- Email: zentronixdevelopers@gmail.com
- Website: Your portfolio URL

## 6. Pin your strongest repositories

Pin only polished repositories with:

- A clear README
- Screenshots
- Working live demo where applicable
- Meaningful commit history
- No secrets, API keys or unnecessary files

Recommended initial pins:

1. zentronix-portfolio
2. wedding-rental-platform
3. jewellery-showcase
4. construction-builder
5. agrodose-atm
6. scribemate

## 7. Before publishing

- Remove projects that are not ready
- Verify every link
- Add real screenshots
- Never upload `.env` files, passwords, tokens or client data
- Keep project descriptions honest
