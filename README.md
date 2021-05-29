# Useful_Tool_4_Ubuntu
自动安装git/Terminator/zsh/oh_my_zsh/Typora/ifconfig/minicom等常用工具

## 执行方式
sudo ./Useful_Tool_4_Ubuntu

## 注意事项
执行后系统会自动重启<br>
执行之前请务必保存好其他文件<br>

## Terminator推荐方案
首先：gedit ～/.config/terminator/config<br>
以下是一款流行的配置方案，可自行调整<br>
[global_config]<br>
>suppress_multiple_term_dialog = True<br>

[keybindings]<br>
[profiles]<br>
>  [[default]]<br>
>>    background_color = "#002b36"<br>
>>    background_darkness = 0.92<br>
>>    background_type = transparent<br>
>>    cursor_color = "#3036ec"<br>
>>    font = Ubuntu Mono 15<br>
>>    foreground_color = "#839496"<br>
>>    show_titlebar = False<br>
>>    login_shell = True<br>
>>    custom_command = tmux<br>
>>    use_system_font = False<br>

[layouts]<br>
> [[default]]<br>
>>    [[[window0]]]<br>
>>>    type = Window<br>
>>>    parent = ""<br>
>>    [[[child1]]]<br>
>>>    type = Terminal<br>
>>>   parent = window0<br>

[plugins]<br>
