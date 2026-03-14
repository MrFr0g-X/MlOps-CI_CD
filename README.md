# Assignment 4 - CI/CD Pipeline

DSAI406 MLOps - Hothifa Hamdan (202201792)

fixing a broken github actions workflow and setting up automated testing for an ML project.

## whats in here
- `.github/workflows/ml-pipeline.yml` - the CI pipeline
- `requirements.txt` - python deps

## pipeline does
1. checkout code
2. setup python 3.10
3. install deps
4. run flake8 linter
5. test torch import
6. upload README as artifact

## green check
![actions](Screenshot%202026-03-15%20001628.png)
