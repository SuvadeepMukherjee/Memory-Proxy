## Remove .DS_Store files if accidentally added

- First add `.DS_Store` to git ignore so that .DS_Store does not get pushed to github
- If not accidentally added .DS_Store to .gitignore remove all .DS_Store files with `find . -name ".DS_Store" -type f -delete` from the root of your project . This will find all .DS_Store files and delete them 💥