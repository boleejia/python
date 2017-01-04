# python

how to install pymc

然后pymc官方教程中推荐了Anaconda，如获至宝啊，下载Anaconda-2.1.0-Windows-x86_64.zip安装， 然后切换到/Anaconda/Anaconda 2.1.0 (64-bit)/Scripts，运行
conda install -c https://conda.binstar.org/pymc pymc
看结果！！！！！！ 居然找不到pymc这个包。
不甘心，去https://conda.binstar.org/pymc看资料，恍然大悟，windows上居然只有32位，没有64的编译版。
天啦………………………………
于是，下载Anaconda-2.1.0-Windows-x86.zip，安装 再次切换到/Anaconda/Anaconda 2.1.0 (32-bit)/Scripts 运行：
conda install -c https://conda.binstar.org/pymc pymc 顺利安装完成，然后执行试试看
import pymc
pymc.test()
终于没有返回错误了。
天啦，太折腾了。
接下来，在pycharm中，更改一下interpreter，希望可以用了吧。
 ----------------------------------------------------------------------------
其他：乘此机会，了解了一下Anaconda，发现这东西虽然很大，但是非常时候我这类不喜欢折腾的人，推荐。
