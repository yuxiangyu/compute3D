

3.1 һ�����ã� 
��cmd������ִ���������£�

PotreeConverter.exe e:/data/sichuan1.las -o E:\data\potree_converted\pointclouds\���� -p page1 -l 5 -gc color -3dtiles --overwrite

ʹ��classification.json�ļ���������ɫ
PotreeConverter.exe e:/data/strip_1.laz -o E:/data/potree_converted -p page4 -l 5 -gc classification -3dtiles
ʹ��intensityֵ��������ɫ
PotreeConverter.exe e:/data/las/avon.laz -o E:/data/potree_converted -p page2 -l 5 -gc intensity -3dtiles
ʹ�ø̸߳�������ɫ
PotreeConverter.exe e:/data/strip_1.laz -o E:/data/potree_converted -p page3 -l 5 -gc height -3dtiles

3.2 ����������

���ȵ���
PotreeConverter2.exe e:/data/sichuan1.las -o E:/data/potree_converted/pointclouds/���� -p page1 -l 5 -gc color -3dtiles
Ȼ�����
python.exe potree23dtiles.py --src E:/data/potree_converted/pointclouds/����/pointclouds/page1 --outdir E:/data/potree_converted/pointclouds/����/pointclouds/3dtiles




