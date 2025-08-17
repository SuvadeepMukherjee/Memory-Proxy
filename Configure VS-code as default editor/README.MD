## Configure vs code as default editor in place of vim 

- From the terminal type the following commands :`git config --global core.editor "code --wait"`

- Open the command palette in vs code with `Command + Shift + P` ➡️ Shell Command Install code command in path 

- If for some reason it fails  with the following error logs : `EACCES: permission denied, unlink 'usr/local/bin/code'` Do the following steps 

  - Uninstall the code command from PATH in VS Code and reinstall it. Open the command palette in VS Code using `cmd + shift + p`. Search `"uninstall 'code'"` and select the first option to uninstall. Once uninstalled, `"install 'code'"` for installing. That should fix it.

   

Resources : 

1. [https://git-scm.com/book/en/v2/Appendix-C%3A-Git-Commands-Setup-and-Config](Official git docs)
2. https://stackoverflow.com/questions/69004740/how-to-fix-vs-code-error-permission-denied-unlink-usr-local-bin-code