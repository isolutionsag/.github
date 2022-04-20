# [isolutions AG](https://www.isolutions.ch/)

> Your partner for digital transformation

## About

Founded in 1999, isolutions accompanies companies into the digital future as the largest, dedicated Microsoft one-stop shop in Switzerland.

#weshapethefuture

## Status and Roadmap of GitHub PoC

- [x] Define guidelines how GitHub should be used in isolutions
  - [x] Document guidelines in GitHub organization profile
- [x] Document status and roadmap in GitHub organization profile
- [ ] Acquire GitHub enterprise licenses
- [ ] Clean up repositories in GitHub organization `isolutionsag`
- [ ] Connect GitHub organization `isolutionsag` with isolutions Azure Tenant (AAD)
- [ ] Internal communication about:
  - [ ] Changes in GitHub organization `isolutionsag`
  - [ ] GitHub guidelines
- [ ] Activate team synchronization
- [ ] Connect GitHub organization `isolutionsag` to Azure DevOps
- [ ] Pilot projects
  - [ ] GitHub only
  - [ ] GitHub & Azure DevOps

## Guidelines

### Policies

- Repositories are private by default
- Public repositories must have a LICENSE file (see [No License | Choose a License](https://choosealicense.com/no-permission/))

### Conventions

- Repository naming conventions
  - No whitespaces
  - No underlines
- Repository conventions
  - Private by default - only public, if there is a real need
  - Initialize with README and .gitignore at least
  - Protect main branch, so that it's not deletable
- GIT conventions
  - General: TBD
  - Branch naming conventions
    - main (required)
    - develop
    - Features: feature/ISSUE_NBR-DESCRIPTION
    - Hotfixes: hotfix/ISSUE_NBR-HOTFIX
    - Releases: release/[v]VERSIONNUMBER (use semantic versioning)
  - Issues
    - Use issues for task tracking
  - Project
    - Use projects, if your project consists of multiple repositories

## Useful resources

- [github-guide-to-organizations.pdf](https://resources.github.com/downloads/github-guide-to-organizations.pdf)
- [Organizations and teams - GitHub Docs](https://docs.github.com/en/organizations)
- [GitHub Enterprise guides - GitHub Docs](https://docs.github.com/en/enterprise-cloud@latest/admin/guides)
