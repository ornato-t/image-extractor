Create venv
```bash
python -m venv .venv  
```

Activate venv with
```bash
.\.venv\Scripts\activate
```

In case of Windows permissions errors, use this and rerun
```powershell
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
```
Check whether pip is working
```bash
python -m ensurepip --upgrade 
```

Install dependencies
```bash
pip install -r requirements.txt
```
