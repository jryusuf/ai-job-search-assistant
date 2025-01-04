# ai-job-search-assistant

[![Release](https://img.shields.io/github/v/release/jryusuf/ai-job-search-assistant)](https://img.shields.io/github/v/release/jryusuf/ai-job-search-assistant)
[![Build status](https://img.shields.io/github/actions/workflow/status/jryusuf/ai-job-search-assistant/main.yml?branch=main)](https://github.com/jryusuf/ai-job-search-assistant/actions/workflows/main.yml?query=branch%3Amain)
[![codecov](https://codecov.io/gh/jryusuf/ai-job-search-assistant/branch/main/graph/badge.svg)](https://codecov.io/gh/jryusuf/ai-job-search-assistant)
[![Commit activity](https://img.shields.io/github/commit-activity/m/jryusuf/ai-job-search-assistant)](https://img.shields.io/github/commit-activity/m/jryusuf/ai-job-search-assistant)
[![License](https://img.shields.io/github/license/jryusuf/ai-job-search-assistant)](https://img.shields.io/github/license/jryusuf/ai-job-search-assistant)

This is a project helps you repetitive tasks during your job search searching, filtering and analyzing job listings with ai and keep track of your applications and give you suggestions based on jobs found in the past

- **Github repository**: <https://github.com/jryusuf/ai-job-search-assistant/>
- **Documentation** <https://jryusuf.github.io/ai-job-search-assistant/>

## Getting started with your project

### 1. Create a New Repository

First, create a repository on GitHub with the same name as this project, and then run the following commands:

```bash
git init -b main
git add .
git commit -m "init commit"
git remote add origin git@github.com:jryusuf/ai-job-search-assistant.git
git push -u origin main
```

### 2. Set Up Your Development Environment

Then, install the environment and the pre-commit hooks with

```bash
make install
```

This will also generate your `uv.lock` file

### 3. Run the pre-commit hooks

Initially, the CI/CD pipeline might be failing due to formatting issues. To resolve those run:

```bash
uv run pre-commit run -a
```

### 4. Commit the changes

Lastly, commit the changes made by the two steps above to your repository.

```bash
git add .
git commit -m 'Fix formatting issues'
git push origin main
```

You are now ready to start development on your project!
The CI/CD pipeline will be triggered when you open a pull request, merge to main, or when you create a new release.

To finalize the set-up for publishing to PyPI, see [here](https://fpgmaas.github.io/cookiecutter-uv/features/publishing/#set-up-for-pypi).
For activating the automatic documentation with MkDocs, see [here](https://fpgmaas.github.io/cookiecutter-uv/features/mkdocs/#enabling-the-documentation-on-github).
To enable the code coverage reports, see [here](https://fpgmaas.github.io/cookiecutter-uv/features/codecov/).

## Releasing a new version



---

Repository initiated with [fpgmaas/cookiecutter-uv](https://github.com/fpgmaas/cookiecutter-uv).
