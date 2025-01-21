# Poetry Commands

## Installation and Initialization
```bash
pip install poetry
poetry init
```

### Optional: Create Virtual Environment Inside Project Folder
```bash
poetry config virtualenvs.in-project true
```

## Managing Dependencies
### Install Dependencies and create virtual environment
```bash
poetry install
```

### Check Virtual Environment Info
```bash
poetry env info
```

## Working with Virtual Environments
### Activate Environment
```bash
poetry shell
```

### Deactivate Environment
```bash
exit
```

## Adding and Removing Packages
### Add a Package
```bash
poetry add 'uvicorn[standard]'
```

### Remove a Package
```bash
poetry remove 'uvicorn[standard]'
```

## Checking Activated Environments
```bash
poetry env list
```

## Other Commands

### Equivalent of pip freeze in Poetry

```bash
poetry show --only main
poetry show --no-dev (Deprecated)
```

### Both development and runtime dependencies
```bash
poetry show
```

### Generate requirements.txt ( pip Compatible )

```bash
poetry export -f requirements.txt --output requirements.txt --without-hashes
```

---

# Important

If you have a requirements.txt file and want to switch to Poetry, you’ll need to install each package individually using Poetry. While automation is possible to streamline this process, it’s essentially a manual workaround.

Poetry manages dependencies through the poetry.lock and pyproject.toml files. Make sure to include both of these files in your version control (e.g., Git) to ensure your environment and dependencies are consistently replicated



### Contributing
Feel free to suggest additional commands or improvements



