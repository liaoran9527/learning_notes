# sql知识

SELECT t.TABLE_NAME,t.TABLE_COMMENT,c.COLUMN_NAME,c.COLUMN_TYPE,c.COLUMN_COMMENT FROM information_schema.TABLES t,INFORMATION_SCHEMA.Columns c WHERE c.TABLE_NAME=t.TABLE_NAME AND t.`TABLE_SCHEMA`='db_ocean'
SELECT t.TABLE_NAME,t.TABLE_COMMENT FROM information_schema.TABLES t WHERE t.`TABLE_SCHEMA`='db_ocean'

# hive知识
条件删除表中的数据
ALTER TABLE cwfx.zta_wid_asset_ip_equatt drop PARTITION (dt= '2022-04-12',tag='equatt')

下载jar包/查询pom依赖
http://findjar.com/
https://mvnrepository.com/
