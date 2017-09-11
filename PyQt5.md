* **从哪里获取 pyuic5**

   解决方法：见 http://blog.csdn.net/u011728480/article/details/53423036
   
              该脚本是在 Debian 9 上安装 python3-pyqt5 时引入的，放在 
            
                  /usr/lib/python3/dist-packages/PyQt5/uic/pyuic.py
            
              在 Bash 中设置别名即可：
            
                  alias pyuic5="python3 -m PyQt5.uic.pyuic"

