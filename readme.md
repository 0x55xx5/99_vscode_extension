ps> code --list-extensions > extensions.md
這會將 VSCode 擴展列表放入文件中extensions.md，每行一個名稱。


bash > xargs -n1 code --install-extension < extensions.md