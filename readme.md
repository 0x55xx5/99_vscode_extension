ps>code --list-extensions > tmp.md
這會將 VSCode 擴展列表放入文件中extensions.md，每行一個名稱。
解壓tmp.zip
bash>xargs -n1 code --install-extension < tmp.md


![](ext.png)