# Workflow

1. Activate conda environment

```bash 
conda activate qe-mini-example
```

1. Build the book (*books/*).

```bash
jupyter-book build dsl_python/
```

1. Call `ghp-import` and point it to HTML files (dsl_python/mini_book) 

```bash
ghp-import -n -p -f _build/html
```