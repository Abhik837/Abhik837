<a href="">
  <img height=175 align="center" src="https://github-readme-stats.vercel.app/api?username=Abhik837&hide=issues&show_icons=true&theme=synthwave" />
</a>
<a href="">
  <img height=175 align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Abhik837&show_icons=true&layout=compact&theme=synthwave" />
</a>
<h1></h1>
<div>
  <img height=125 align="center" src="https://images.credly.com/size/680x680/images/00634f82-b07f-4bbd-a6bb-53de397fc3a6/image.png" />
</div>
<h1></h1>
<div>
<p>Contact: abhiraam.kandula@gmail.com</p>
<p>CTFtime: https://ctftime.org/team/380405</p>
<p>Credly: https://www.credly.com/users/abhiraam-kandula/badges#credly</p>
</div>

# Abhik837

[![Followers](https://img.shields.io/github/followers/Abhik837?label=Followers&style=social)](https://github.com/Abhik837)
[![Repositories](https://img.shields.io/github/repo-size/Abhik837/Abhik837)](https://github.com/Abhik837/Abhik837)
[![Last Commit](https://img.shields.io/github/last-commit/Abhik837/Abhik837)](https://github.com/Abhik837/Abhik837)

<!--
  NOTE:
  The dynamic GitHub "cards" previously used (via vercel / github-readme-stats) can be unavailable
  when the service is paused or rate-limited. To avoid broken images in viewers that block or when
  external services pause deployments, this README references cached/local images.
  Place prepared images in .github/images/ as described below, or restore the live endpoints if desired.
-->

<!-- Local/cached stats (recommended to commit these image files into the repo under .github/images/) -->
<p align="center">
  <a href="https://github.com/Abhik837">
    <img alt="GitHub stats (cached)" src=".github/images/github-stats.svg" height="175" />
  </a>
  <a href="https://github.com/Abhik837">
    <img alt="Top languages (cached)" src=".github/images/top-langs.svg" height="175" />
  </a>
</p>

<!-- Credly badge: recommended to store locally to avoid hotlinking issues -->
<p align="center">
  <img alt="Credly badge" src=".github/images/credly.png" height="125" />
</p>

## About me

- Contact: abhiraam.kandula@gmail.com
- CTFtime: https://ctftime.org/team/380405
- Credly: https://www.credly.com/users/abhiraam-kandula/badges#credly

---

## Why the change?
The previous README used the Vercel-hosted github-readme-stats endpoints. Those endpoints can be paused or rate-limited (resulting in broken images). To make the README reliable across viewers (GitHub web, local editors, and plugins), I recommend committing static/cached images into the repository and referencing them locally.

## How to generate and keep the cached images
Option A — Quick one-off (manual)
1. Open the live endpoints in your browser (or curl) and save the returned SVG/PNG:
   - https://github-readme-stats.vercel.app/api?username=Abhik837&hide=issues&show_icons=true&theme=synthwave
   - https://github-readme-stats.vercel.app/api/top-langs/?username=Abhik837&layout=compact&theme=synthwave
   - Download your Credly image and save it as .github/images/credly.png
2. Commit the files to .github/images/ and push.

Option B — Periodic automatic refresh (recommended)
- Create a small GitHub Actions workflow that:
  - curls the live SVG endpoints
  - commits them into .github/images/
  - runs on a schedule (e.g., daily or weekly)
This keeps images up to date while avoiding runtime dependencies in viewers that block external content.

Example curl commands (run locally or in an action):
curl -L "https://github-readme-stats.vercel.app/api?username=Abhik837&hide=issues&show_icons=true&theme=synthwave" -o .github/images/github-stats.svg
curl -L "https://github-readme-stats.vercel.app/api/top-langs/?username=Abhik837&layout=compact&theme=synthwave" -o .github/images/top-langs.svg

If you want, I can:
- create the GitHub Actions workflow file that fetches and commits these images on a schedule, and/or
- prepare and push the initial .github/images/* files for you.
