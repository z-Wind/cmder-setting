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
        autocrlf = false # for window
        quotepath = false
        #whitespace = cr-at-eol # ignore CR
    [gui]
        encoding = utf-8
    [i18n]
        commitencoding = utf-8
        logoutputencoding = utf-8
    
    2. 
    git config --global user.name "John Doe"
    git config --global user.email johndoe@example.com
    
    3. modify init.bat to change clink
    
    4. gitattributes
    # remain all file's line end LF = LF, CRLF = CRLF
    # * text auto change to 
    * -text
    
# vim
    1. vimrc
    " display
    " fileencodings -> fileencoding -convert to-> encoding -> tenc
    " write
    " fileencodings -> fileencoding <-convert to- encoding <- tenc
    
    
    " Sets the character encoding for the file of this buffer.
    set fileencoding=utf-8
    " This is a list of character encodings considered when starting to edit an existing file.
    set fileencodings=ucs-bom,utf-8,big5,cp936,gb18030,euc-jp,euc-kr,latin1
    " Sets the character encoding used inside Vim.
    set encoding=utf8
    " Encoding used for the terminal
    set tenc=utf8
    " hotkey F12 to change display encoding
    map <F12> :set tenc=big5<cr>

    
    