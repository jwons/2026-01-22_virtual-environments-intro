# Comparison of Conda and UV

```
conda create -n test_env -c conda-forge -y python=3.12 jupyterlab pandas=2.2.3
```

```
uv venv test_env --python 3.12
uv pip install jupyterlab pandas==2.2.3 --python test_env
```