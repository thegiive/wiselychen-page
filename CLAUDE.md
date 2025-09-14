# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is "wiselychen-page" - an AI consultant personal website designed to be deployed via GitHub Pages. The site will showcase AI consulting services, expertise, and professional portfolio.

## Project Structure

Currently minimal with only:
- README.md - Basic project documentation
- .git/ - Git version control

## GitHub Pages Deployment

This site is intended for GitHub Pages deployment, which supports:
- Static HTML/CSS/JS files
- Jekyll static site generator (Ruby-based)
- Custom domains and HTTPS
- Automatic builds from main branch

## Development Approach

For GitHub Pages, consider these common approaches:
1. **Static HTML/CSS/JS** - Direct deployment of static files
2. **Jekyll** - GitHub's native static site generator with Markdown support
3. **Modern static generators** - Using GitHub Actions for build/deploy (Next.js, Nuxt, etc.)

## AI Consultant Website Features

Typical sections for an AI consultant website:
- Professional introduction and expertise
- Services offered (AI strategy, implementation, training)
- Case studies and portfolio
- Contact information and consultation booking
- Blog/insights on AI trends
- Testimonials and credentials

## Notes

- GitHub Pages serves from the root directory or /docs folder
- Custom domains can be configured via CNAME file
- Site will be publicly accessible once deployed
- Consider responsive design for mobile/desktop viewing