# Python Virtual Environment Commands

## Windows

Create:
```powershell
py -m venv .venv
```

Activate in PowerShell:
```powershell
.venv\Scripts\Activate.ps1
```

Activate in Command Prompt (CMD):
```bat
.venv\Scripts\activate.bat
```

## Linux

Create:
```bash
python3 -m venv .venv
```

Activate:
```bash
source .venv/bin/activate
```

## Install the libraries

```bash
pip install -r requirements.txt
```



## Deactivate (Windows and Linux)

```bash
deactivate
```
