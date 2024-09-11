# {{ cookiecutter.friendly_name }}

[![PyPI](https://img.shields.io/pypi/v/{{cookiecutter.project_name}}.svg)][pypi status]
[![Status](https://img.shields.io/pypi/status/{{cookiecutter.project_name}}.svg)][pypi status]
[![Python Version](https://img.shields.io/pypi/pyversions/{{cookiecutter.project_name}})][pypi status]
[![License](https://img.shields.io/pypi/l/{{cookiecutter.project_name}})][license]

[![Read the documentation at https://{{cookiecutter.project_name}}.readthedocs.io/](https://img.shields.io/readthedocs/{{cookiecutter.project_name}}/latest.svg?label=Read%20the%20Docs)][read the docs]
[![Tests](https://github.com/{{cookiecutter.github_user}}/{{cookiecutter.project_name}}/workflows/Tests/badge.svg)][tests]
[![Codecov](https://codecov.io/gh/{{cookiecutter.github_user}}/{{cookiecutter.project_name}}/branch/main/graph/badge.svg)][codecov]

[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white)][pre-commit]
[![Black](https://img.shields.io/badge/code%20style-black-000000.svg)][black]

[pypi status]: https://pypi.org/project/{{cookiecutter.project_name}}/
[read the docs]: https://{{cookiecutter.project_name}}.readthedocs.io/
[tests]: https://github.com/{{cookiecutter.github_user}}/{{cookiecutter.project_name}}/actions?workflow=Tests
[codecov]: https://app.codecov.io/gh/{{cookiecutter.github_user}}/{{cookiecutter.project_name}}
[pre-commit]: https://github.com/pre-commit/pre-commit
[black]: https://github.com/psf/black

## Features

- TODO

## Requirements

- TODO

## Installation

You can install _{{cookiecutter.friendly_name}}_ via [pip] from [PyPI]:

```console
$ pip install {{cookiecutter.project_name}}
$ poetry add {{cookiecutter.project_name}}
```

## Development setup

- First install .venv from vscode (no pip reqirements)
- `pip install poetry`
- run `poetry update` (to install all poetry manage packages in the newest version)

For updating packages run `poetry update`

- poetry add <package>
- poetry update
- poetry add --dev nox nox-poetry pytest-cov nox-poetry

Poetry can export the dependencies to other formats, for this `poetry self add poetry-plugin-export` is needed.

### Best practice

- Test code with`coverage run -m pytest` or `pytest --cov`
- Check if all formal checks (e.g. linting) are passed with `nox -rs pre-commit`
- Check if all wanted variable types are implemented properly with `nox -rs typeguard`
- Bump version in pyproject.toml
- Always push to branch (otherwise some github workflows will fail!)

## Usage

Please see the [Command-line Reference] for details.

## Contributing

Contributions are very welcome.
To learn more, see the [Contributor Guide].

## License

Distributed under the terms of the [{{cookiecutter.license.replace("-", " ")}} license][license],
_{{cookiecutter.friendly_name}}_ is free and open source software.

## Issues

If you encounter any problems,
please [file an issue] along with a detailed description.

## Credits

This project was generated from [@cjolowicz]'s [Hypermodern Python Cookiecutter] template.

[@cjolowicz]: https://github.com/cjolowicz
[pypi]: https://pypi.org/
[hypermodern python cookiecutter]: https://github.com/cjolowicz/cookiecutter-hypermodern-python
[file an issue]: https://github.com/{{cookiecutter.github_user}}/{{cookiecutter.project_name}}/issues
[pip]: https://pip.pypa.io/

<!-- github-only -->

[license]: https://github.com/{{cookiecutter.github_user}}/{{cookiecutter.project_name}}/blob/main/LICENSE
[contributor guide]: https://github.com/{{cookiecutter.github_user}}/{{cookiecutter.project_name}}/blob/main/CONTRIBUTING.md
[command-line reference]: https://{{cookiecutter.project_name}}.readthedocs.io/en/latest/usage.html
