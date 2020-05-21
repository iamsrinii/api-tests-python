[![Board Status](https://dev.azure.com/iamsrinii/dd17fdec-8145-4286-8745-686609200f90/699c1ef9-f1fd-4f70-afc9-3378842c1380/_apis/work/boardbadge/78ea2cdf-7fa2-457b-86cb-d1e4888ebfb8)](https://dev.azure.com/iamsrinii/dd17fdec-8145-4286-8745-686609200f90/_boards/board/t/699c1ef9-f1fd-4f70-afc9-3378842c1380/Microsoft.RequirementCategory)
# api-tests-python

[![CircleCI](https://circleci.com/gh/pishchalnikov/api-tests-python.svg?style=svg)](https://circleci.com/gh/pishchalnikov/api-tests-python)

Examples for API Testing with Python

Requirements:
* python3.8
* virtualenv

Prepare venv:
```bash
$ virtualenv --python=python3.8 venv
$ source venv/bin/activate
```

Install dependencies:
```bash
$ pip install -r requirements.txt
```

Run tests:
```bash
$ pytest tests/
```

Run tests in Docker:
```bash
$ docker build --tag api-tests-python .
$ docker run api-tests-python
```
