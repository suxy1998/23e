
   
##  请根据上述要求，完成以下问题：

 **（1）**计算有效问卷率；

 **（2）__选择合适的指标，说明效问卷的回答时长及其分布。

 __（3）__新生成两个变量，一为*province*（省份），一为*city*（省会城市或地级市，），此部分信息均在*ip*一列中可以找到。统计各省份、各城市有多少被试参与调查。

+ 注：当然，*ip*显示云南丽江，不一定被试为丽江市区（城市户口），也可能是丽江农村（农村户口）。所以这里的城市，只宜理解为行政管辖上的归属地所属，而不能体现城乡差别。

+ 提示：建议使用Hadley的stringr及lubridate这两个包进行字段处理和时间处理的相关操作。
