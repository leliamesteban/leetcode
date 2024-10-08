# algolearn - Custom Standard Library

Custom implementation of standard library to help learn Data Structures, Algorithms and Leetcode.

## Core Features

- Available on PyPi
- Implement Array
- Implement LinkedList
- Implement HashMap
- Implement Heap
- Implement Stack
- Implement Tree

## Future Features

- Make available on GitHub packages
- Use a build tool instead of running setup.py directly because this method is deprecated
- Upload to PyPi automatically using GitHub Actions
- Host the documentation on Read The Docs
- Generate documentation automatically with Sphinx

## Phases

## Milestones

## User stories

## System requirements

## Installation

```bash
pip3 install algolearn
```

## Usage

```bash
python3 main.py
```

## Testing

```bash
python3 -m unittest -v tests/multiplication_tests.py
```

## Contributing

## Manually publishing to PyPi

```bash
pip3 install twine wheel setuptools
python3 setup.py sdist bdist_wheel
twine check dist/*
twine upload --repository-url https://test.pypi.org/legacy/ dist/*
twine upload dist/*
```

## Generating documentation

```bash
pip3 install sphinx
mkdir docs && cd docs
sphinx-quickstart
make html
```
