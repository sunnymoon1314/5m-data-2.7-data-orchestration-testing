# dagster_orchestration

Minimal example of pipelines, definition on dagsgter + DBT. In this repo, you find a simple demo of how the pipelines work. Note this is not the best practice since all the code are in a giant monorepo.


# Installation 

```
conda env update -f environment.yml
conda activate elt 
pip install -e ".[dev]"
pip install -r requirements_old.txt
```

If you are using existing `elt` conda environment installed in 2.1 instead, do the following

```
conda activate elt
pip install -e ".[dev]"
pip install -r requirements.txt
```

# Start Dagster 

```
dagster dev
```

# Run pipeline 

In the web UI, you can run any of the pipelines by clicking on materialize. Have fun!