* **从哪里获取 pyuic5**

   解决方法：见 http://blog.csdn.net/u011728480/article/details/53423036
   
              该脚本是在 Debian 9 上安装 python3-pyqt5 时引入的，放在 
            
                  /usr/lib/python3/dist-packages/PyQt5/uic/pyuic.py
            
              在 Bash 中设置别名即可：
            
                  alias pyuic5="python3 -m PyQt5.uic.pyuic"

* **从哪里获取 Qt5 版本的 Qt Designer**

   解决方法：见 http://blog.csdn.net/z_lit0/article/details/51524518
   
              Debian 9 中有 qt4-designer，但是没有 qt5-designer
              
                   apt install qttools5-dev-tools
                   
              在终端输入
              
                   designer  (桌面环境下竟然要从终端启动 UI 设计工具。。。)
                   
              /usr/bin/designer 是一个符号链接，指向 /usr/bin/qtchooser (Wrapper to select between Qt development binary versions)
    
    
    
 
 
 
