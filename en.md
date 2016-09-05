# aw-reporting计算机英语 #

----------
2016/8/29 9:22:31 

1. just a specific(特定) set of accounts # a set of (一系列的)
2.   on the console 控制器（终端）
3. The application will print all the tracing(调试代码) on the console
4. Import（导入项目） the project into Eclipse
5. To（目的为了） import the project into Eclipse, first import the model:
6. Generate（产生） the database schema using Maven(使用maven生成数据库)
7.  The schema creates the whole database assuming that（条件） none of（ 不存在） the tables were created before
8.  We will keep migrating（升级） aw-reporting to the latest AdWords API version. （keep to 迭代到...中）
9.  Since these changes may be scattered(影响很多数据表) around many tables
10.  For better organization and encapsulation（封装）
11.  the project groups the reporting workflow into two parts:(group into 组织成)
12.  Aw-Report-Model for persistence(持久), entities（实体） and the CSV mapping to AdWords information and Aw-Reporting for the logic (API services, downloader and processors)Aw-Report-Model持久性,实体和CSV映射AdWords信息和Aw-Reporting逻辑(API服务,下载器和处理器)。
13.  keep in mind that most of the entity IDs are not available in the reports downloaded from the interface