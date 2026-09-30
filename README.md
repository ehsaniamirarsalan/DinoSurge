# DinoSurge

## Jupyter setup (Windows)

```powershell
python -m venv .venv          # use a Python >= 3.12
uv sync --system-certs        # installs deps from uv.lock (needed behind Zscaler)
.\.venv\Scripts\python.exe -m jupyterlab
```

Launch Jupyter with `python -m jupyterlab`; the `jupyter.exe` launcher is blocked by policy on this machine.
In VS Code, pick the `.venv` interpreter as the notebook kernel.
