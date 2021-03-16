前言
======================
常见情况:
	* ORACLE -> ORACLE
	* ORACLE 
# 一、导出数据
## 1.导出工具选择
### 1) 使用Navicat premium15导出

# 二、删除多余部分

# 三、修改格式
ORACLE -> MYSQL
1) decimal(3) -> number(3,0)
2) VARCHAR2 -> VARCHAR
3) to_date('12-01-2021 17:53:51', 'dd-mm-yyyy hh24:mi:ss') -> STR_TO_DATE('2021-01-12 17:32:38', '%Y-%m-%d %H:%i:%s')