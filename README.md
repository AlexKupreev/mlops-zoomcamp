# mlops-zoomcamp

## Set up dev env (GH codespaces)

* Confirm rebuilding the image (as of `devcontainer.json`)
* `poetry shell`
* `poetry install --with  mlsvc`
* To work with Jupyter notebook, start from installing [Jupyter]() VSCode plugin to devcontainer, then select interpreter (poetry with "mlops-zoomcamp" prefix) and eventually that will allow to select a kernel (this very interpreter).

To check if the container storage is not billed [link](https://docs.github.com/en/codespaces/troubleshooting/troubleshooting-included-usage#storage-usage-for-your-base-dev-container):
```
$ devcontainer-info
```

The output should contain the following output:
```
- Definition ID: universal
- Source code repository: https://github.com/devcontainers/images
```