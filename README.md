# 1. Ensure you have Python 3.10+ installed. Run the following command to check:
```python3 --version```

If not installed, download Python.
```brew install python```


# 2. Install uv (Universal Virtualenv):
Open your terminal and install uv:
```
pip3 install uv
```

# 3: Install VSCode:

Download and install Visual Studio Code.

# 4. Set Up a Virtual Environment:

Use uv to create and activate a virtual environment:
```
python3 -m venv uv
source uv/bin/activate
```

# 5. Install Browser-Use Library:

Run the following command to install the library:
```
pip install browser-use requests
pip install --upgrade pip
```

# 6. Run
```
uv run browser-use-agent.py
```
