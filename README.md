

## 🐍 GitHub Contribution Graph Commit Pattern Generator + Snake Animation

This repository auto-generates commit activity using a coordinate system to simulate shapes on your GitHub contribution graph. It also uses github workflow to render your contribution activity as an animated Snake 🐍.

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/iamsiddharthdas/iamsiddharthdas/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/iamsiddharthdas/iamsiddharthdas/output/github-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/iamsiddharthdas/iamsiddharthdas/output/github-snake.svg" align="center"/>
</picture>

<br>

## 📈 What This Repo Does

1. **🧱 Simulates GitHub Contributions:**
   - Uses a grid of `[x, y]` coordinates to represent weeks and days.
   - Commits are made using backdated timestamps (via `--date`) for visual patterns on your contributions calendar.

2. **🐍 Animates Contributions:**
   - A GitHub Actions workflow generates SVG + GIF snake animations based on your contribution graph. 
   - Outputs both light and dark themes (including ocean palette variations).





