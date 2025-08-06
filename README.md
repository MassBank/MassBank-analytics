[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MassBank/MassBank-analytics/HEAD?urlpath=%2Fdoc%2Ftree%2Frecord_grow.ipynb)

# Jupyter notebook to run some analytics

[https://mybinder.org/v2/gh/MassBank/MassBank-analytics/HEAD?urlpath=%2Fdoc%2Ftree%2Frecord_grow.ipynb](https://mybinder.org/v2/gh/MassBank/MassBank-analytics/HEAD?urlpath=%2Fdoc%2Ftree%2Frecord_grow.ipynb)

## running in Docker locally

```
docker run -p 8888:8888 -v $PWD:/home/jovyan/work quay.io/jupyter/scipy-notebook
```

## GitHub fine-grained access token

For the GitHub analytics, you need a file `github_token.txt` with a
fine-grained access token to MassBank-data with the following read-only
permissions:

- Administration (Repository creation, deletion, settings, teams, and collaborators.)
- Commit statuses (Commit statuses.)
- Metadata (Search repositories, list collaborators, and access repository metadata)
