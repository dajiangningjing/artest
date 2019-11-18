## 问题

已知POI，求解视频中POI的位置


## 流程

1. POI经纬度转笛卡尔坐标系
GeodeticToCartesian

    > 米勒投影算法

2. 设置three中对应camera和POI的信息， 通过three获得相应矩阵

3. 展示POI


## SList

S. 世界坐标换算为屏幕坐标

```p.project(camera);```



## Qlist

Q. three.js 模拟云台旋转方式. 物体绕一个固定向量旋转

Q. canvas或webgl生成标签, 记录位置, 编辑修正位置

Q. camera接入web； 云台控制； 云台旋转修正






tomcat apahce 
webroot: http://localhost:8080/threejs/examples/webgl_loader_gltf2.html