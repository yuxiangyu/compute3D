1,安装python3.6或者3.7(推荐3.7.3)
2,安装python组件,即在python/scripts目录下分别执行pip install命令如下：
pip install numpy
pip install pyproj
pip install glob2

3 在cmd窗口中执行命令如下：

PotreeConverter.exe C:/data.las -o C:/potree_converted -p pageName

使用classification.json文件给点云配色
PotreeConverter.exe e:/data/strip_1.laz -o E:/data/potree_converted -p page4 -l 10 -gc classification -3dtiles
使用intensity值给点云配色
PotreeConverter.exe e:/data/las/avon.laz -o E:/data/potree_converted -p page2 -l 10 -gc intensity -3dtiles
使用高程给点云配色
PotreeConverter.exe e:/data/strip_1.laz -o E:/data/potree_converted -p page3 -l 10 -gc height -3dtiles