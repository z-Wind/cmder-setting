# cmder-setting 
    1. solve duplicate Chinese word
        setting -> Main -> Main console font -> Cancel Monospace

    2. change open directory
        setting -> Startup -> Tasks -> {cmd}
        cmd /k "%ConEmuDir%\..\init.bat"  -new_console:d:"D:\HD\backup\Knowledge\GitHub"
        detail command in ConEmu document (-new_console)

    3. add cmder path to Enviroment variable Path

# git-setting
    1. gitconfig
    [core]
        quotepath = false
    [gui]
        encoding = utf-8
    [i18n]
        commitencoding = utf-8
        logoutputencoding = utf-8
    
    2. 
    git config --global user.name "John Doe"
    git config --global user.email johndoe@example.com
