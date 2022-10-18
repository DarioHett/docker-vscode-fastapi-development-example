# docker-vscode-fastapi-development-example

This code serves as a runnable example to show,
1. how to integrate vscode with docker, and
2. how to debug a fastapi app.

Docker and `Dev Containers` extension have to be installed. 
Run (`CTRL+SHIFT+P`) `Dev Containers: Reopen in Container`. 
You mount to `/workspace`, next install the Python extension and select the interpreter. 
Finally, focus `main.py` and debug with `F5`. 
Select the default `Python File` suggestion as a debug configuration. 
The app will be available under http://localhost:8000/.
Set breakpoints while the app is running.

For a more involved example, check out https://davidefiocco.github.io/debugging-containers-with-vs-code/.