# 🌐 nasim.dev – Configuration Repository

This repository contains all the dynamic **content and configuration** for [nasim.dev](https://nasim.dev), the personal website and public CV of **Nasim Ali**, a full-stack software engineer. The site loads all its data — from text content to project showcases — directly from this repo at runtime using GitHub raw links.

---

## 🔧 Purpose

By seperating configuration from the core app code, this setup:

- Keeps the main website repo clean and focused
- Enables real-time updates without code redeployment
- Supports scalability and reusability across site versions

---

## 📁 Structure

```bash
/data
│
├── about.json         # Bio & About Me section
├── contact.json       # Contact form labels, social links, messages
├── education.json     # Academic history & certifications
├── experience.json    # Work experience timeline
├── projects.json      # Signature projects & open-source work
├── skills.json        # Technical skills with icons/levels
└── textContent.json   # Global strings: headings, nav, hero, footer, etc.
