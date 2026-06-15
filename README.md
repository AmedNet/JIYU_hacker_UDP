### 安装依赖

```bash
pip install customtkinter
```

### 打包为exe

> 需要先安装 `pyinstaller `

```bash
pip install pyinstaller 
```
> 打包
```bash
pyinstaller  --onefile  -w -i .\logo.ico  .\UDP_Attack.py
```