# OS Setup
Automate the setup of my operating system


## TODO
- Add Logitech G-Hub (for mouse)


## Windows (2020-03-20)
1. Uninstall unnecessary apps
1. Install Chocolatey (chocolatey.org/install)
1. Install the following apps via choco:

        choco install googlechrome -y
        choco install jetbrainstoolbox -y
        choco install 7zip.install -y
        choco install flutter -y
        choco install git.install -y
        choco install nodejs.install -y
        choco install python3 -y
        
1. Install JetBrains IDEs:
    1. Sign into JetBrains Toolbox
    1. IntelliJ IDEA Ultimate
    1. PyCharm Professional
    1. WebStorm
    1. Android Studio
1. Install Logitech G Hub (https://www.logitechg.com/en-us/innovation/g-hub.html)
1. Update File Explorer:
    - Go to 'View' > Options > View, and set the following values:
        - Check 'Show hidden files, folders, and drives'
        - Uncheck 'Hide extensions for known file types'
1. Copy dot files to home directory:
    - .aliases
    - .gitconfig
    - .ssh
    - .vimrc
