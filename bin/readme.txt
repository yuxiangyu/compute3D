1,��װpython3.6����3.7(�Ƽ�3.7.3)
2,��װpython���,����python/scriptsĿ¼�·ֱ�ִ��pip install�������£�
pip install numpy
pip install pyproj
pip install glob2

3 ��cmd������ִ���������£�

PotreeConverter.exe C:/data.las -o C:/potree_converted -p pageName

ʹ��classification.json�ļ���������ɫ
PotreeConverter.exe e:/data/strip_1.laz -o E:/data/potree_converted -p page4 -l 10 -gc classification -3dtiles
ʹ��intensityֵ��������ɫ
PotreeConverter.exe e:/data/las/avon.laz -o E:/data/potree_converted -p page2 -l 10 -gc intensity -3dtiles
ʹ�ø̸߳�������ɫ
PotreeConverter.exe e:/data/strip_1.laz -o E:/data/potree_converted -p page3 -l 10 -gc height -3dtiles