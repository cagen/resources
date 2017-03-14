### 行政区划数据

#### 数据源
[中华人民过共和国国家统计局 最新县及县以上行政区划代码（截止2016年7月31日）](http://www.stats.gov.cn/tjsj/tjbz/xzqhdm/201703/t20170310_1471429.html)

#### 数据结构
* 结构：按照省市区逐级嵌套
* 数据：
  * id (Integer): 行政区划代码
  * name (String): 行政区划名称
  * children (Array): 下一级行政区划
* 文件：
  * index.json： 格式化后的数据
  * index.min.json: 压缩为一行的数据
