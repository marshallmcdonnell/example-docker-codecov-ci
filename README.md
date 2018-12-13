# example-docker-codecov-ci
Sandbox for setting up docker for CI and codecov with Python

The example app is used from: http://luisquintanilla.me/2018/02/18/testing-deploying-python-projects-travisci/

## To run test
Run the following:
```
docker build -t app-test -f docker/Dockerfile.test . && docker run -t app-test
```
