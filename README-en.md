<p align="center">
  <img src="./assets/logo.svg" alt="docs-en-mi-idioma" width="160" height="160">
</p>

# docs-en-mi-idioma

> Spanish translations of technical documentation for the Spanish-speaking developer
> community.

A personal, community-driven project to make open-source library documentation accessible in Spanish; for developers at every level, everywhere.

## Table of Contents

- [Why Translating Documentation Matters](#why-translating-documentation-matters)
- [Workflow](#workflow)
- [Packages Being Translated](#packages-being-translated)
- [Translated Packages](#translated-packages)
- [How to Contribute](#how-to-contribute)
- [Support the Project](#support-the-project)

---

## Why Translating Documentation Matters

English is the default language of open source. Most libraries, frameworks, and developer tools publish their documentation exclusively in English; which works fine if you're fluent, but creates a real obstacle for the millions of developers who aren't.

This is not a minor inconvenience. Developers who struggle with documentation learn more slowly, make avoidable mistakes, and are often excluded from technical conversations that shape projects they depend on. In Latin America alone, there is a large and growing developer community with limited access to documentation in their own language.

Translating technical docs is one of the most direct ways to address this:

- It lowers the barrier to technical knowledge for non-English speakers.
- It strengthens developer ecosystems in Latin America and the broader Spanish-speaking world.
- It makes open source genuinely inclusive; for beginners, experienced engineers, and companies alike.
- It sends a clear signal: quality resources should not require fluency in a second
  language.

This project exists to make that happen, one library at a time.

---

## Workflow

The process is straightforward and repeatable:

1. **Fork** the original package repository.
2. **AI-assisted translation** (Anthropic's Claude AI is currently being used) as a starting point.
3. **Manual review** to ensure technical accuracy, natural tone, and consistent terminology throughout.
4. **Pull Request** to the original repository with the proposed translation.

AI speeds up the first pass; human review is always the final step.

---

## Packages Being Translated

| Package | Status | PR | Notes |
|---------|--------|----|-------|
| [ansible-runner](https://github.com/ansible/ansible-runner) | In Progress | TBD | — |
| [bandit](https://github.com/PyCQA/bandit) | In Progress | TBD | — |
| [black](https://github.com/psf/black) | In Progress | TBD | — |
| [cookiecutter](https://github.com/cookiecutter/cookiecutter) | In Progress | TBD | — |
| [cookiecutter-django](https://github.com/cookiecutter/cookiecutter-django) | In Progress | TBD | — |
| [django-debug-toolbar](https://github.com/django-commons/django-debug-toolbar) | In Progress | TBD | — |
| [django-simple-history](https://github.com/django-commons/django-simple-history) | In Progress | TBD | — |
| [django-storages](https://github.com/jschneier/django-storages) | In Progress | TBD | — |
| [flake8](https://github.com/PyCQA/flake8) | In Progress | TBD | — |
| [freezegun](https://github.com/spulec/freezegun) | Waiting for review | https://github.com/spulec/freezegun/pull/552 | — |
| [isort](https://github.com/PyCQA/isort) | In Progress | TBD | — |
| [ruff](https://github.com/astral-sh/ruff) | In Progress | TBD | — |

---

## Translated Packages

| Package | Status | PR | Notes |
|---------|--------|----|-------|
| [complexipy](https://github.com/rohaquinlop/complexipy) | merged | https://github.com/rohaquinlop/complexipy/pull/147 | — |
| [responses](https://github.com/getsentry/responses) | merged | https://github.com/getsentry/responses/pull/790 | — |


---

## How to Contribute

This project is open to everyone: seasoned OSS contributors, developers just getting started, teams inside companies, or anyone who wants to help make documentation more accessible.

**To get involved:**

1. Open a [GitHub issue](https://github.com/jlariza/docs-en-mi-idioma/issues) to propose a package, ask a question, or report a problem.
2. **Comment** on existing pull requests. Package developers often don't prioritize translations and tend to ignore these types of pull requests. Your comment demonstrates that the pull request is necessary and encourages them to review it and eventually merge it. 
2. If you want to translate a package, comment on the relevant issue so we can coordinate.
3. When they exist, follow the original repository's contribution guidelines.
4. Prioritize **clarity and natural tone** over literal translation.

**Translation principles:**

- Neutral Spanish with a LatAm-friendly preference.
- Keep technical terms in English when no clear, established equivalent exists (e.g., *commit*, *branch*, *render*, *hook*).
- Be consistent with terminology throughout the document.

All contributors will be credited in this repository.

---

## Support the Project

This project is maintained voluntarily. If you find it useful and want to support it, you can do so through:

- **GitHub Sponsors:** [github.com/sponsors/jlariza](https://github.com/sponsors/jlariza) *(coming soon)*
- [![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/G2G31XJAU4)

No obligation, no pressure — but always appreciated.

---

License: [MIT](./LICENSE)
