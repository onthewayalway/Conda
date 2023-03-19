# Conda
主要用于记录Conda的使用方法

conda简单使用：https://www.jianshu.com/p/441f7bd62b41

1. 安装conda
2. 命令 conda config --set show_channel_urls yes 后生成.condarc文件，具体路径为：~/用户名/.condarc
3. 修改.condarc修改源
  channels:
  - defaults
show_channel_urls: true
default_channels:
  - http://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/main
  - http://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/r
  - http://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/msys2
custom_channels:
  conda-forge: http://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  msys2: http://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  bioconda: http://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  menpo: http://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  pytorch: http://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  pytorch-lts: http://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  simpleitk: http://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
4. 其他

conda的安装包可以从该镜像获取：https://mirrors.bfsu.edu.cn/anaconda/archive/

设置python中的环境变量方法：https://able.bio/rhett/how-to-set-and-get-environment-variables-in-python--274rgt5


