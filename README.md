# cookiecutter-hypermodern-python

<!-- badges-begin -->

[![Status][status badge]][status badge]
[![Python Version][python version badge]][github page]
[![License][license badge]][license]<br>
[![Read the documentation][readthedocs badge]][readthedocs page]
[![Tests][github actions badge]][github actions page]
[![pre-commit enabled][pre-commit badge]][pre-commit project]
[![Black codestyle][black badge]][black project]
[![Contributor Covenant][contributor covenant badge]][code of conduct]

[black badge]: https://img.shields.io/badge/code%20style-black-000000.svg
[black project]: https://github.com/psf/black
[code of conduct]: https://github.com/welworx/cookiecutter-hypermodern-python/blob/main/CODE_OF_CONDUCT.md
[contributor covenant badge]: https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg
[github actions badge]: https://github.com/welworx/cookiecutter-hypermodern-python/workflows/Tests/badge.svg
[github actions page]: https://github.com/welworx/cookiecutter-hypermodern-python/actions?workflow=Tests
[github page]: https://github.com/welworx/cookiecutter-hypermodern-python
[license badge]: https://img.shields.io/github/license/welworx/cookiecutter-hypermodern-python
[license]: https://opensource.org/licenses/MIT
[pre-commit badge]: https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white
[pre-commit project]: https://pre-commit.com/
[python version badge]: https://img.shields.io/pypi/pyversions/cookiecutter-hypermodern-python-instance
[readthedocs badge]: https://img.shields.io/readthedocs/cookiecutter-hypermodern-python/latest.svg?label=Read%20the%20Docs
[readthedocs page]: https://cookiecutter-hypermodern-python.readthedocs.io/
[status badge]: https://badgen.net/badge/status/alpha/d8624d

<!-- badges-end -->

[Cookiecutter] template for a Python package based on the
[Hypermodern Python] article series.

✨📚✨ [Read the full documentation][readthedocs page]

[cookiecutter]: https://github.com/audreyr/cookiecutter
[hypermodern python]: https://medium.com/@cjolowicz/hypermodern-python-d44485d9d769

## Usage

### pipx for macos
```console
brew install pipx
pipx ensurepath
````
### prepare environment:

```console
pipx install cookiecutter
pipx install poetry
pipx install nox
pipx inject nox nox-poetry
```

Keep everything up to date:

```console
pipx upgrade cookiecutter
pipx upgrade --include-injected nox
poetry self update
```

### Latest version

```console
cookiecutter gh:welworx/cookiecutter-hypermodern-python
```

### Specific tagged version:

```console
cookiecutter gh:welworx/cookiecutter-hypermodern-python --checkout=2022.6.3
```

## Features

<!-- features-begin -->

- Packaging and dependency management with [Poetry]
- Test automation with [Nox]
- Linting with [pre-commit] and [Flake8]
- Continuous integration with [GitHub Actions]
- Documentation with [Sphinx], [MyST], and [Read the Docs] using the [furo] theme
- Automated uploads to [PyPI] and [TestPyPI]
- Automated release notes with [Release Drafter]
- Automated dependency updates with [Dependabot]
- Code formatting with [Black] and [Prettier]
- Import sorting with [isort]
- Testing with [pytest]
- Code coverage with [Coverage.py]
- Coverage reporting with [Codecov]
- Command-line interface with [Click]
- Static type-checking with [mypy]
- Runtime type-checking with [Typeguard]
- Automated Python syntax upgrades with [pyupgrade]
- Security audit with [Bandit] and [Safety]
- Check documentation examples with [xdoctest]
- Generate API documentation with [autodoc] and [napoleon]
- Generate command-line reference with [sphinx-click]
- Manage project labels with [GitHub Labeler]

The template supports Python 3.9, 3.10, 3.11 and 3.12.

[autodoc]: https://www.sphinx-doc.org/en/master/usage/extensions/autodoc.html
[bandit]: https://github.com/PyCQA/bandit
[black]: https://github.com/psf/black
[click]: https://click.palletsprojects.com/
[codecov]: https://codecov.io/
[coverage.py]: https://coverage.readthedocs.io/
[dependabot]: https://github.com/dependabot/dependabot-core
[flake8]: http://flake8.pycqa.org
[furo]: https://pradyunsg.me/furo/
[github actions]: https://github.com/features/actions
[github labeler]: https://github.com/marketplace/actions/github-labeler
[isort]: https://pycqa.github.io/isort/
[mypy]: http://mypy-lang.org/
[myst]: https://myst-parser.readthedocs.io/
[napoleon]: https://www.sphinx-doc.org/en/master/usage/extensions/napoleon.html
[nox]: https://nox.thea.codes/
[poetry]: https://python-poetry.org/
[pre-commit]: https://pre-commit.com/
[prettier]: https://prettier.io/
[pypi]: https://pypi.org/
[pytest]: https://docs.pytest.org/en/latest/
[pyupgrade]: https://github.com/asottile/pyupgrade
[read the docs]: https://readthedocs.org/
[release drafter]: https://github.com/release-drafter/release-drafter
[safety]: https://github.com/pyupio/safety
[sphinx]: http://www.sphinx-doc.org/
[sphinx-click]: https://sphinx-click.readthedocs.io/
[testpypi]: https://test.pypi.org/
[typeguard]: https://github.com/agronholm/typeguard
[xdoctest]: https://github.com/Erotemic/xdoctest

<!-- features-end -->
