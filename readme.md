# Get started

## Linux

    cd ~/.config/Code/User
    git init .
    git remote add origin https://github.com/bluekeys/vscode-user-settings.git
    wget https://raw.githubusercontent.com/bluekeys/vscode-user-settings/master/.gitignore
    git add .
    git commit -m "..."
    git merge remotes/origin/master --allow-unrelated-histories
    ... Fix merge errors ...
    git add .
    git commit -m "..."
    git push origin master
    

## Windows

Clone this to $env:AppData\Code\User

    git clone https://github.com/bluekeys/vscode-user-settings.git $env:AppData\Code\User
