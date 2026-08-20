# 🛠️ GitHub Profile Customization Guide

Welcome to your new, handcrafted SaaS-style GitHub Profile repository! This guide provides step-by-step instructions to personalize your profile, configure automated GitHub Actions, and fine-tune assets in minutes.

---

## 🚀 Quick Start Checklist

To use this profile repository as your personal GitHub Profile README:

1. **Create a Special Repository**:
   - Go to GitHub and create a new repository named **exactly** after your GitHub username (e.g. `gaurabdowerah/gaurabdowerah`).
   - Set the repository to **Public** and initialize it with a README.

2. **Clone & Push**:
   - Clone your new repository locally:
     ```bash
     git clone https://github.com/YOUR_USERNAME/YOUR_USERNAME.git
     ```
   - Copy all files from this template into your repository.
   - Commit and push to `main` branch.

---

## 🎨 1-Step Configuration (README.md)

At the very top of `README.md`, you will find HTML metadata comments with configurable placeholders:

```markdown
<!-- 
  CONFIGURABLE PROFILE VARIABLES
  USERNAME       : gaurabdowerah
  NAME           : Gaurab Dowerah
  TITLE          : Full Stack Developer & AI Engineer
  LOCATION       : Assam, India
  MUSIC_ALIAS    : DRYM MUSIC
  WEBSITE        : https://gaurabdowerah.dev
  LINKEDIN       : https://linkedin.in/in/gaurabdowerah
  EMAIL          : gaurabdowerah@gmail.com
-->
```

### Simple Find & Replace Table:

| Search Variable | Replace With | Location |
| :--- | :--- | :--- |
| `Notyourapple` | Your GitHub Username | `README.md`, `.github/workflows/` |
| `Xalt3heris` | Your Full Name | `README.md`, `assets/banner.svg` |
| `gaurabdowerah@gmail.com` | Your Email | `README.md` |
| `DRYM MUSIC` | Your Music / Brand Alias | `README.md`, `assets/banner.svg` |

---

## 🔑 Setting Up GitHub Actions & Secrets

This repository includes 3 automated workflows in `.github/workflows/`:

1. **`snake.yml`**: Generates the contribution grid snake animation SVG on an `output` branch.
2. **`metrics.yml`**: Generates detailed repository and language breakdown statistics.
3. **`update.yml`**: Updates your daily developer quote automatically every night.

### Workflow Permissions Setup:

1. In your GitHub repository, go to **Settings** > **Actions** > **General**.
2. Scroll down to **Workflow permissions**.
3. Select **Read and write permissions**.
4. Check **Allow GitHub Actions to create and approve pull requests**.
5. Click **Save**.

### Optional Secrets Configuration:

- **`METRICS_TOKEN`** (Recommended for `metrics.yml`):
  - Go to **GitHub Settings** > **Developer Settings** > **Personal Access Tokens (Tokens classic)**.
  - Generate a new token with `read:user`, `repo` scopes.
  - Copy the token and add it to your repo: **Settings** > **Secrets and variables** > **Actions** > **New repository secret** with key `METRICS_TOKEN`.

- **WakaTime Coding Stats** (Optional for Section 13):
  - Sign up at [WakaTime](https://wakatime.com/).
  - Obtain your WakaTime Secret API Key.
  - Embed your WakaTime badge URL or stats badge in Section 13 of `README.md`.

---

## 🎨 Customizing SVG Graphics

All raw SVG graphic assets are located in the `assets/` folder:

- **`assets/banner.svg`**: The primary hero graphic. You can open this file in any text editor or design app (Figma/VS Code) to edit text lines, gradient colors, or status badges.
- **`assets/config-card.svg`**: Renders `gaurab.config.ts`. Edit strings inside `<tspan>` tags to change your tech focus, current projects, or fun facts.
- **`assets/avatar-frame.svg`**: SVG avatar frame with status light.
- **`assets/divider.svg`**: Glowing section divider.
- **`assets/footer-wave.svg`**: Footer wave with custom signature.

---

## 🎵 Customizing DRYM Music Section

Section 8 is tailored for music producers and creators:

- Replace Spotify, YouTube, and SoundCloud links with your own artist URLs.
- Update release artwork cards and audio preview embeds as desired.

---

## 🛡️ License & Attribution

This profile template is free and open-source. Build something awesome!
