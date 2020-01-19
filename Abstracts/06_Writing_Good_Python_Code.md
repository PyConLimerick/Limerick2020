### Submission 16

We love python because of its readability, massive ecosystem, vibrant community etc. and the list goes on. 
However, like other programming languages, it is easy to write cryptic, unmaintainable, and rigid python code. In short an ugly code(I can give an example). Moreover in teams, this problem escalates as different developers have diverse code styles. How to ensure code quality and homogeneity? 
PEP 8 is a style guide of python code. 

We can use “pylint”, which is a source code, bug, and quality checker for python and follows the style recommended by PEP 8(I can give an example on how to use it). In addition to “pylint”, we have several other tools suited for different purposes. “mypy” provides optional static typing, “pydocstyle” checks compliance with Python docstring conventions, “bandit” finds common security issues in Python code, and “black” is a Python code formatter. How to get your team in sync with these tools?

We can use build pipelines and/or pre-commit hooks. A build pipeline is a set of tasks, each of which performs a step in your build process(I can give an example of an Azure DevOps pipeline). Pre-commit hooks are used to inspect the snapshot that’s about to be committed. “pre-commit”( https://pypi.org/project/pre-commit/) is a framework for managing and maintaining multi-language pre-commit hooks. We can easily configure it using a “pre-commit-config.yaml” file(I can give an example of using the above-mentioned tools with pre-commit).
