cmd输入：mysql [-h 127.0.0.1] [-P 3306] -u root -p  通过cmd启动mysql  
[]可省略  
mysql语句不区分大小写  
或者mySQL command line client启动  

show databases; 展示可用数据库  
use xx(database);   选择数据库  
select database();  查询当前所使用的数据库

show tables 查询数据库中的表  
SELECT * FROM table_name;   看表

CREATE TABLE [IF NOT EXISTS] table_name (  
  column_name1 column_type， [comment 'xx']  
  column_name2 column_type， [comment 'xx']  
  column_name3 column_type  
  ) [comment 'xx'];

desc tableName; 查看表结构  