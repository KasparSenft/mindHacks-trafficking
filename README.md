## Getting Started

### 1. Clone the Repository
```bash
git clone repo_name
cd repo_name
```

### 2. Install UV (if not already installed)
```bash
pip install uv
```

### 3. Create a virtual environment with UV
```bash
uv venv --python 3.12.9
```

### 4. Activate the virtual environment

```bash
source .venv/bin/activate
```

### 5. Install project dependencies
```bash
uv pip install -r requirements.txt
```

### 6.  Install the project in development mode

```bash
uv pip install -e .
```


### 7. Register the environment as a Jupyter kernel

```bash
uv pip install ipykernel

python -m ipykernel install --user --name=hackathon-env --display-name="hackathon-env"
```
---

## Adding new packages

If you need to add new packages:


```bash
# Make sure your virtual environment is activated
source .venv/bin/activate 

# Install the new package
uv pip install package-name
```


Kaspar was here.