# Intro to Repository Management

![Mergington High School Extracurricular Website](https://github.com/akabyn5/SpaceDogs-GHW-HackingForGood/blob/main/docs/old-submissions/Intro%20to%20Repository%20Management/IMG-20260318-WA0102.jpg?raw=true)

Learn the basics of several GitHub features that help support a collaborative, friendly, and healthy project.

## Overview

**Who is this for?**  
Developers who need to start collaborating with others on a shared repository.

**What you’ll learn**  
The different ways to protect your repository’s content as more people join as collaborators.

**What you’ll build**  
You will prepare Mergington High School’s extracurricular activities website repository so additional teachers can safely collaborate.

## Prerequisites

- [Introduction to GitHub](https://skills.github.com)
- [Communicate using Markdown](https://skills.github.com)
- [Review pull requests](https://skills.github.com)

**Duration**: Less than one hour.

---

## What We Accomplished

In this exercise we successfully:

- Added simple **rulesets** and configuration to restrict repository content
- Communicated procedures to help guide collaborators
- Assigned responsibility of parts of the code to particular collaborators (CODEOWNERS)
- Learned the difference between collaboration in a personal repository vs. an organization repository
- Established ground rules to promote a healthy collaboration environment
- Established a process for managing security updates

![Protected Repository Features](https://github.com/akabyn5/SpaceDogs-GHW-HackingForGood/blob/main/docs/old-submissions/Intro%20to%20Repository%20Management/IMG-20260318-WA0104.jpg?raw=true)

## Repository Protection Features Implemented

### 1. Branch Protection Rules & Rulesets
- Main branch is protected
- Require pull request reviews before merging
- Status checks must pass
- Rulesets prevent force pushes and deletions

### 2. CODEOWNERS
Defined code ownership for different sections of the website:
- `/activities/` → @teacher-sports
- `/clubs/` → @teacher-arts
- `/docs/` → @admin-team

### 3. Security & Collaboration Guidelines

**Contributing Guidelines** (`CONTRIBUTING.md`):
- Always work on feature branches
- Submit descriptive pull requests
- Review process (at least 1 approval required)

**Security Policy**:
- Regular dependency updates via Dependabot
- Security alerts enabled
- Responsible disclosure process

![Healthy Collaboration](https://github.com/akabyn5/SpaceDogs-GHW-HackingForGood/blob/main/docs/old-submissions/Intro%20to%20Repository%20Management/IMG-20260318-WA0112.jpg?raw=true)

## Project Status

✅ Repository is now ready for safe multi-teacher collaboration  
✅ All protection mechanisms are in place  
✅ Documentation and guidelines are published  
✅ Code ownership is clearly defined  
