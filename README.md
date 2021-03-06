![OS-test](https://github.com/mjkeng/ci_course/workflows/OS-test/badge.svg)
![Python 3.6-3.9](https://github.com/mjkeng/ci_course/workflows/Python%203.6-3.9/badge.svg)
[![codecov](https://codecov.io/gh/mjkeng/ci_course/branch/main/graph/badge.svg?token=CPERMII8Y2)](https://codecov.io/gh/mjkeng/ci_course)
[![BCH compliance](https://bettercodehub.com/edge/badge/mjkeng/ci_course?branch=main)](https://bettercodehub.com/)
[![Documentation Status](https://readthedocs.org/projects/cicoursenov/badge/?version=latest)](https://cicoursenov.readthedocs.io/en/latest/?badge=latest)

# OxRSE Continuous Integration course

This project contains a small Python project. We are going to use free cloud services to automate:

- unit testing on multiple Python versions
- unit testing on multiple operating systems
- coverage testing
- static analysis
- documentation generation

To make sure all dependencies are installed, we recommend creating a new virtual environment.
From the directory containing this file:

```bash
python3 -m pip install --user virtualenv
python3 -m venv venv
```

Activate the virtual environment:

Linux / macOS:
```bash
source venv/bin/activate
```

Windows cmd.exe:
```bash
venv\Scripts\activate.bat
```

Windows PowerShell:
```bash
venv\Scripts\Activate.ps1
```

Windows using Git Bash:
```bash
source venv\Scripts\activate
```

Upgrade the build tools and install this project:

```bash
pip install --upgrade pip setuptools wheel
pip install -e .[dev,docs]
```
