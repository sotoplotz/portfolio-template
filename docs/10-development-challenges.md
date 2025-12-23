# Development Challenges & Problem Solving

## Context

During the initial setup of the project, several technical issues occurred
related to tooling, environment configuration, and framework behavior.

## Main Challenges

### 1. Environment and Permissions Issues

- PowerShell execution policy initially blocked npm commands
- Git authentication problems caused failed pushes to GitHub

**Solution**

- Updated PowerShell execution policy
- Cleaned local Git configuration and re-authenticated with GitHub

---

### 2. Framework Misconfiguration

- Previous Astro setup attempts caused inconsistent project structure
- CSS styles were not being applied due to incorrect integration methods

**Solution**

- Full project reset
- Reinstallation of Astro following official documentation
- Decision to rebuild the project step by step with clear commits

---

### 3. Deployment Confusion (GitHub Pages & Jekyll)

- GitHub Pages tried to process Astro files using Jekyll
- Resulted in build errors and failed deployments

**Solution**

- Deployment postponed
- `.nojekyll` file intentionally removed until deployment phase
- Deployment strategy will be documented and applied later

---

## Reflection

Although the setup process was challenging, these issues helped to better
understand:

- How Astro handles assets and builds
- Differences between static site generators
- Importance of clean project structure and incremental development

This experience reinforces professional problem-solving skills.
