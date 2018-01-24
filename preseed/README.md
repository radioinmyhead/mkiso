ubuntu可以帮你生成一个自定义的preseed文件
首先安装debconf-utils
之后:
debconf-get-selections --installer
可以得到当前机器preseed文件，不过，不建议直接用这个文件，而是将官方的preseed例子做修改
这个文件是原料库
