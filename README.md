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
[global_config]
  suppress_multiple_term_dialog = True
[keybindings]
[profiles]
  [[default]]
    background_color = "#002b36"
    background_darkness = 0.92
    background_type = transparent
    cursor_color = "#3036ec"
    font = Ubuntu Mono 15
    foreground_color = "#839496"
    show_titlebar = False
    login_shell = True
    custom_command = tmux
    use_system_font = False
[layouts]
  [[default]]
    [[[window0]]]
      type = Window
      parent = ""![在这里插入图片描述](https://img-blog.csdnimg.cn/20200430223930797.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2ZlaW1lbmcxMTY=,size_16,color_FFFFFF,t_70)

    [[[child1]]]
      type = Terminal
      parent = window0
[plugins]
————————————————
版权声明：本文为CSDN博主「大橙员」的原创文章，遵循CC 4.0 BY-SA版权协议，转载请附上原文出处链接及本声明。
原文链接：https://blog.csdn.net/feimeng116/article/details/105849955
