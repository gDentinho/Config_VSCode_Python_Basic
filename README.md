# Config_VSCode_Python_Basic
Minha configuração basica do VSCode para Python

Configuraçoes basica do VSCode para python. 
1. copiar arquivo "sttings.json" e substituir o arquivo original
2. instalar as extensões:
	- Python (Microsoft)
	- Code Runner (Jun Han)
	- Om themes 
	- Material Icon Theme

3. arquivo settings.json
   {
    "workbench.startupEditor": "none",
    "editor.fontSize": 16,
    "explorer.compactFolders": false,
    "code-runner.runInTerminal": true,
    "code-runner.clearPreviousOutput": true,
    "code-runner.executorMap": {
        "python": "cls ; python -u",
    },
    "code-runner.ignoreSelection": true,
    "workbench.colorTheme": "OM Theme (Default Dracula Italic)",
    "workbench.iconTheme": "material-icon-theme",
    "python.defaultInterpreterPath": "python"
}
