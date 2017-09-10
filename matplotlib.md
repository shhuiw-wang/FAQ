* **freetype cannot be found by build**

  在 Debian 9.1.0 通过 pip 安装 matplotlib 时总是失败，即便已经安装了 libfreetype6 和 libfreetype6-dev
  ```
          freetype: no  [The C/C++ header for freetype2 (ft2build.h)
                        could not be found.  You may need to install the
                        development package.]
  ```
  解决方法：见 https://github.com/matplotlib/matplotlib/issues/3029/
           安装 pkg-config 即可 
                        `# apt install pkg-config`
 
  
