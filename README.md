# Github AI Models

## '.env' file

[generate-token](https://github.com/settings/tokens)

```
GITHUB_TOKEN="..."
```

## Manage Conda ENV

### Create

```
conda env create -n gh-ai-models-env -f ./env.yml
```

### Activate
```
conda activate gh-ai-models-env
```

### Update

```
conda env update -n gh-ai-models-env -f ./env.yml
```

### Remove

```
conda env remove --n gh-ai-models-env
```

## Execute

```
python src/main.py
```

## Links

[github](https://github.com/Diegoomal)

[tutorial](https://github.com/marketplace/models/azureml-meta/Meta-Llama-3-1-8B-Instruct)