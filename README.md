# Portfolio Website

A modern, interactive portfolio showcasing my projects, skills, and professional information.

## 🛠️ Tech Stack
- **Frontend**: HTML5, CSS3, JavaScript 
- **Deployment**: Vercel/Netlify

## 🌿 Branching Strategy
I follow a modified GitHub Flow to maintain production stability:


### Main Branches
| Branch    | Purpose                     |
|-----------|-----------------------------|
| `main`    | Production (Live site)      |
| `develop` | Staging (Pre-production)    |

### Working Branches
| Prefix     | Use Case                    | Example                |
|------------|-----------------------------|------------------------|
| `feature/` | New features                | `feature/dark-mode`    |
| `fix/`     | Bug fixes                   | `fix/mobile-layout`    |
| `hotfix/`  | Critical production fixes   | `hotfix/404-error`     |

## 💻 Development Commands

```bash```
# Start new feature
- git checkout develop
- git pull origin develop
- git checkout -b feature/feature-name

# After completing work
- git add .
- git commit -m "Add: Feature description"
- git push origin feature/feature-name

# Merge to develop
- git checkout develop
- git merge feature/feature-name
- git push origin develop

# Deploy to production
- git checkout main
- git merge develop
- git push origin main
