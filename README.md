| DevOps |
|--------|
| [![Build Status](https://travis-ci.org/marshallmcdonnell/example-docker-codecov-ci.svg?branch=master)](https://travis-ci.org/marshallmcdonnell/example-docker-codecov-ci) |
| [![codecov](https://codecov.io/gh/marshallmcdonnell/example-docker-codecov-ci/branch/master/graph/badge.svg)](https://codecov.io/gh/marshallmcdonnell/example-docker-codecov-ci)   |

# example-docker-codecov-ci
Sandbox for setting up docker for CI and codecov with Python

The example app is used from: http://luisquintanilla.me/2018/02/18/testing-deploying-python-projects-travisci/

## To run test
Run the following:
```
docker build -t app-test -f docker/Dockerfile.test . && docker run -t app-test pytest
```
