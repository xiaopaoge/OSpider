# OSpider v2.0.0(last release)
OSpider专注于矢量地理数据获取和预处理，目前可以快速完整地获取城市及其内部的百度POI
欢迎加入OSpider用户群QQ:939504570，发送邮件到1159331173@qq.com与开发者联系

1	当前版本功能（v2.0.0）
爬取指定区域的百度POI数据，并将坐标转化为WGS84

2	升级说明
#20191229  v2.0.0
①增添了UI界面,程序运行状态提示更加人性化
②重构核心代码
③自动记忆上一次输入的参数
④新增用户群，开辟交流新渠道

#20180731  v1.0.1
①修复了中文路径闪退bug
②修复了部分POI由于属性结构问题而无法爬取造成闪退的bug

#20180725 v1.0.0
②突破指定区域爬取poi数量小于400个限制，支持单区域1w+POI爬取；
③绕过了区域中存在多个行政区时只返回一个行政区POI的潜在反爬虫机制；
④爬取poi的同时，实现bd09坐标到wgs84坐标的转换；
⑤使用配置文件property.ini控制爬取参数；

3 升级计划
-使POI具备所属类别在内的详细信息 v2.0.1
-抓取时，准许依照类型 v2.0.1
-优化坐标获取插件 v2.0.2
-提供独立坐标转换插件 v2.1.0
-提供一键转shp功能 v2.2.0
-构建key池，多线程，进一步优化程序，提升运行速度 v2.3.0
-开放批处理功能 v2.4.0
-集成按行政区抓取方法 v2.5.0
-提供高德POI爬取功能 v2.6.0
-提供独立的地址解析功能 v2.7.0
-全面整合OSpider，预留其他矢量地理数据下载接口 v3.0.0
-提供矢量行政边界下载功能 v3.1.0
-提供路网下载功能 v3.2.0
-提供水域下载功能 v3.3.0
-提供绿地下载功能 v3.4.0
