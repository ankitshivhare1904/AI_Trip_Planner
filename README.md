<!-- # Check what all the python version available in the system -->
```uv python list```

<!-- # Install the specific python version -->
```uv python install cpython-3.10.18-windows-x86_64-none```

<!-- # Create Virtual Environement with specific python version -->
```uv venv venv --python cpython-3.10.18-windows-x86_64-none```

<!-- # Create virtual environment with the latest existing package -->
```uv venv```

<!-- # Activate the Environment -->
```.venv\Scripts\activate```

<!-- # Deactivate the exisiting environment -->
```deactivate env```

<!-- # Install the package using uv (Can also do through pip) -->
```uv add langchain```

<!-- # See the install pacakage in the current existing evironment -->
```uv pip list```
