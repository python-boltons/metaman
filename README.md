# metaman

**metadata manager (METAMAN)... Makes use of Python's dynamic nature to inspect a program's internals.**

_project status badges:_

[![CI Workflow](https://github.com/python-boltons/metaman/actions/workflows/ci.yml/badge.svg)](https://github.com/python-boltons/metaman/actions/workflows/ci.yml)
[![Coverage](https://codecov.io/gh/python-boltons/metaman/branch/master/graph/badge.svg)](https://codecov.io/gh/python-boltons/metaman)
[![Documentation Status](https://readthedocs.org/projects/bolton-metaman/badge/?version=latest)](https://bolton-metaman.readthedocs.io/en/latest/?badge=latest)
[![Package Health](https://snyk.io/advisor/python/bolton-metaman/badge.svg)](https://snyk.io/advisor/python/bolton-metaman)

_version badges:_

[![Project Version](https://img.shields.io/pypi/v/bolton-metaman)](https://pypi.org/project/bolton-metaman/)
[![Python Versions](https://img.shields.io/pypi/pyversions/bolton-metaman)](https://pypi.org/project/bolton-metaman/)
[![Cookiecutter: cc-python](https://img.shields.io/static/v1?label=cc-python&message=2022.01.04&color=d4aa00&logo=cookiecutter&logoColor=d4aa00)](https://github.com/python-boltons/cc-python)
[![Docker: pythonboltons/main](https://img.shields.io/static/v1?label=pythonboltons%20%2F%20main&message=2021.12.22&color=8ec4ad&logo=docker&logoColor=8ec4ad)](https://github.com/python-boltons/docker-python)


## Installation 🗹

To install `metaman` using [pip][9], run the following
commands in your terminal:

``` shell
python3 -m pip install --user bolton-metaman  # install metaman
```

If you don't have pip installed, this [Python installation guide][10] can guide
you through the process.

<!-- [[[[[kooky.cog
from pathlib import Path

lines = Path("./docs/design/design.md").read_text().split("\n")
if any(L.strip() for L in lines):
    fixed_lines = [L.replace("(.", "(./docs/design") if L.startswith("![") else L for L in lines]
    print("## Design Diagrams\n")
    print("\n".join(fixed_lines))
]]]]] -->
<!-- [[[[[end]]]]] -->


## Useful Links 🔗

* [API Reference][3]: A developer's reference of the API exposed by this
  project.
* [cc-python][4]: The [cookiecutter][5] that was used to generate this project.
  Changes made to this cookiecutter are periodically synced with this project
  using [cruft][12].
* [CHANGELOG.md][2]: We use this file to document all notable changes made to
  this project.
* [CONTRIBUTING.md][7]: This document contains guidelines for developers
  interested in contributing to this project.
* [Create a New Issue][13]: Create a new GitHub issue for this project.
* [Documentation][1]: This project's full documentation.


[1]: https://bolton-metaman.readthedocs.io/en/latest
[2]: https://github.com/python-boltons/metaman/blob/master/CHANGELOG.md
[3]: https://bolton-metaman.readthedocs.io/en/latest/modules.html
[4]: https://github.com/python-boltons/cc-python
[5]: https://github.com/cookiecutter/cookiecutter
[6]: https://docs.readthedocs.io/en/stable/
[7]: https://github.com/python-boltons/metaman/blob/master/CONTRIBUTING.md
[8]: https://github.com/python-boltons/metaman
[9]: https://pip.pypa.io
[10]: http://docs.python-guide.org/en/latest/starting/installation/
[11]: https://github.com/pypa/pipx
[12]: https://github.com/cruft/cruft
[13]: https://github.com/python-boltons/metaman/issues/new/choose
