## 问题

已知POI，求解视频中POI的位置


## 流程

1. POI经纬度转笛卡尔坐标系
GeodeticToCartesian

2. 设置three中对应camera和POI的信息， 通过three获得相应矩阵

3. 展示POI