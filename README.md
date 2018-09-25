# SparkSqlImoocLog
1.对给定的访问日志进行数据清洗，取出所需要的指定列的数据，利用工具类对IP地址和访问时间进行分析；  
2.通过spark sql对数据进行统计，统计每日访问量最高的课程，并将结果写入mysql数据库中；  
3.将项目打成jar包在centos上用spark-submit命令运行在YARN上。  
