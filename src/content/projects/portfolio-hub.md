---
title: "Portfolio Hub"
description: "A containerized project hub built with Astro, Docker, and Nginx, auto-deployed to AWS via GitHub Actions."
publishDate: 2026-09-23
tags: ["Astro", "Docker", "Nginx", "AWS", "CI/CD"]
githubUrl: "https://github.com/joblomint/my-portfolio"
---

This is my personal project hub — a place to showcase the things I build as I learn full-stack development.

## What It Does

- Serves a fast, static portfolio site built with **Astro**
- Runs inside a **Docker** container for clean, reproducible deployments
- Uses **Nginx** as a reverse proxy with **Let's Encrypt SSL** for HTTPS
- Auto-deploys on every `git push` via **GitHub Actions**
- Hosted on an **AWS EC2** instance

## What I Learned

- Configuring Nginx as a reverse proxy with proper security headers
- Building a multi-stage Dockerfile for static sites
- Using Astro's content collections to power dynamic project pages
- Setting up CI/CD with GitHub Actions and SSH key authentication
- Debugging SSH authentication, base64 encoding, and Nginx routing

## What's Next

- Adding more projects as I build them
- A blog section for write-ups
- Dark/light mode toggle
