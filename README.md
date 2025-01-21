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

---

### Contributing
Feel free to suggest additional commands or improvements!
