# Github Action - Setup Poetry (for Python)

This does the setup process for a [python](https://www.python.org/) [poetry]
(https://python-poetry.org/) project.

It:-
    - checks out the project
    - installs python
    - installs poetry
    - builds the dependency set

This is cached as much as possible.

Currently - first version - the python (3.10.2) and poetry (1.1.12) versions
are nailed down, and the complete depth of the repository is checked out
(this is needed for the release process) - these items may be made more
configurable in the future.
