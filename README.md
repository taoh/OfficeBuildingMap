# OfficeBuildingMap
基于Arcgis的上海写字楼信息展示。

**数据来源**：对房屋租售信息网站[安居客](https://shanghai.anjuke.com/)的上海写字楼页面进行定期爬取和更新。

**地图图层**：通过Arcgis QueryLayer建立数据库与Arcgis图层的桥接，在图层上实时展示数据库中写字楼位置。并将整个服务发布到Arcgis Server上供前端调用。

**前端展示**：通过Arcgis JS获取地图服务并完成写字楼信息数据的展示和交互。

**待实现的功能**：
>* 导出报表
>* 热点图，聚合图
>* 平均：价格+面积
>* 统计功能：饼图，柱状图等
>* 界面美化，控件