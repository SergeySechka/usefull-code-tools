# usefull-code-tools
helpfull commands

#to complete delete forever unexpectedly committed file to github
git filter-branch --index-filter 'git rm --cached --ignore-unmatch THE_FILE_NAME' HEAD
