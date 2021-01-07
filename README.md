# Wandbox
clone到本地后，首先必须执行 ./install_deps.sh 安装依赖包。

中间可能安装失败，再次执行他会重新开始，可以适量修改install_deps.sh脚本，仅重新安装失败的。依赖包自动下载源码安装，安装在_install目录下。

核心代码在kernel2中，安装步骤也在里面的 README.md 中。



cd /home/qpzhou/sources/wandbox/kennel2/_build/release
make install
