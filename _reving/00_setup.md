# install locally

### Add the furnace dir in the path of vscode.
This will remove all the unknown packages underlined by Vscode in .py files  

```
# file .vscode/settings.json
{
    "python.analysis.extraPaths": ["${workspaceFolder}/furnace"]
}
```

### Add ./requirements.txt


easydict 

#other not added because already present in local conda env (torch, ...)

### Add .gitignore
__pycache__/
*.onnx
*.pth