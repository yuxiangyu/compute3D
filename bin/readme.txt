

3.1 一步调用： 
在cmd窗口中执行命令如下：

PotreeConverter.exe e:/data/sichuan1.las -o E:\data\potree_converted\pointclouds\点云 -p page1 -l 5 -gc color -3dtiles --overwrite

使用classification.json文件给点云配色
PotreeConverter.exe e:/data/strip_1.laz -o E:/data/potree_converted -p page4 -l 5 -gc classification -3dtiles
使用intensity值给点云配色
PotreeConverter.exe e:/data/las/avon.laz -o E:/data/potree_converted -p page2 -l 5 -gc intensity -3dtiles
使用高程给点云配色
PotreeConverter.exe e:/data/strip_1.laz -o E:/data/potree_converted -p page3 -l 5 -gc height -3dtiles

3.2 分两步调用

首先调用
PotreeConverter2.exe e:/data/sichuan1.las -o E:/data/potree_converted/pointclouds/点云 -p page1 -l 5 -gc color -3dtiles
然后调用
python.exe potree23dtiles.py --src E:/data/potree_converted/pointclouds/点云/pointclouds/page1 --outdir E:/data/potree_converted/pointclouds/点云/pointclouds/3dtiles




