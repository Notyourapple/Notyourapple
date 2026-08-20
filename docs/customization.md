# 🛠️ GitHub Profile Customization Guide

Welcome to your handcrafted SaaS & futuristic dashboard GitHub Profile repository! This guide provides step-by-step instructions to personalize your profile, configure automated GitHub Actions, and fine-tune assets in minutes.

---

## 🚀 Quick Start Checklist

To use this profile repository as your personal GitHub Profile README:

1. **Create a Special Repository**:
   - Go to GitHub and create a new repository named **exactly** after your GitHub username (`Notyourapple/Notyourapple`).
   - Set the repository to **Public** and initialize it with a README.

2. **Clone & Push**:
   - Clone your repository locally:
     ```bash
     git clone https://github.com/Notyourapple/Notyourapple.git
     ```
   - Copy all files from this project into your repository.
   - Commit and push to `main` branch.

---

## 🎨 Configuration (`README.md`)

At the very top of `README.md`, you will find metadata variables:

```markdown
<!-- 
  PROFILE VARIABLES
  USERNAME       : Notyourapple
  NAME           : Gaurab Dowerah
  TITLE          : Full Stack Developer • AI Engineer • Builder
  LOCATION       : Assam, India
  EMAIL          : contact@gaurabdowerah.dev
  GITHUB         : https://github.com/Notyourapple
-->
```

### Profile Attributes:

| Variable | Current Value | Location |
| :--- | :--- | :--- |
| `USERNAME` | `Notyourapple` | `README.md`, `.github/workflows/` |
| `NAME` | `Gaurab Dowerah` | `README.md`, `assets/banner.svg` |
| `EMAIL` | `contact@gaurabdowerah.dev` | `README.md` |
| `LOCATION` | `Assam, India` | `README.md`, `assets/config-card.svg` |

---

## 🔑 Setting Up GitHub Actions & Secrets

This repository includes automated workflows in `.github/workflows/`:

1. **`snake.yml`**: Generates the contribution grid snake animation SVG on the `output` branch.
2. **`metrics.yml`**: Generates detailed repository and language breakdown statistics.
3. **`update.yml`**: Updates your daily developer quote automatically every night.

### Workflow Permissions Setup:

1. In your GitHub repository, go to **Settings** > **Actions** > **General**.
2. Scroll down to **Workflow permissions**.
3. Select **Read and write permissions**.
4. Check **Allow GitHub Actions to create and approve pull requests**.
5. Click **Save**.

### Optional Secrets Configuration:

- **`METRICS_TOKEN`** (Optional for `metrics.yml`):
  - Go to **GitHub Settings** > **Developer Settings** > **Personal Access Tokens (Tokens classic)**.
  - Generate a new token with `read:user`, `repo` scopes.
  - Copy the token and add it to your repo: **Settings** > **Secrets and variables** > **Actions** > **New repository secret** with key `METRICS_TOKEN`.

---

## 🎨 Customizing SVG Graphics

All raw SVG graphic assets are located in the `assets/` folder:

- **`assets/banner.svg`**: The primary dashboard hero graphic. Contains modern glowing typography, availability badge, pill tags, and embedded `gaurab.config.ts`.
- **`assets/config-card.svg`**: Renders `gaurab.config.ts`. Edit strings inside `<tspan>` tags to change your tech focus, current projects, or fun facts.
- **`assets/avatar-frame.svg`**: SVG avatar frame with orbiting neon glows and status light.
- **`assets/divider.svg`**: Glowing cyber section divider.
- **`assets/footer-wave.svg`**: Footer wave with signature branding.

---

## 🛡️ License & Attribution

This profile template is free and open-source. Build something awesome!
