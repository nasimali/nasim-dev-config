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
├── education.json      # Academic history, certifications & highlights
├── experience.json     # Professional roles, descriptions & skills
├── projects.json       # Portfolio projects, categories, links & media
├── skills.json         # Technical skillset with icons and proficiency levels
├── textContent.json    # All static content: nav, hero, about, contact form, footer, etc.
