# mybatis_gene
mybatis auto generate table entity.


##  使用方式
- 下载项目，导入到myeclipse 中。
- 项目右键 -> Run as -> Maven generate-sources
看到下面日志表示生成成功了
```log
[INFO] Scanning for projects...
[INFO]                                                                         
[INFO] ------------------------------------------------------------------------
[INFO] Building generator 0.0.1-SNAPSHOT
[INFO] ------------------------------------------------------------------------
[INFO] 
[INFO] --- mybatis-generator-maven-plugin:1.3.2:generate (Generate MyBatis Artifacts) @ generator ---
[INFO] Connecting to the Database
[INFO] Introspecting table mybatis_gene.sys_role
log4j:WARN No appenders could be found for logger (org.mybatis.generator.internal.db.DatabaseIntrospector).
log4j:WARN Please initialize the log4j system properly.
log4j:WARN See http://logging.apache.org/log4j/1.2/faq.html#noconfig for more info.
[INFO] Generating Record class for table sys_role
[INFO] Generating Mapper Interface for table sys_role
[INFO] Generating SQL Map for table sys_role
[INFO] Saving file SysRoleMapper.xml
[INFO] Saving file SysRole.java
[INFO] Saving file SysRoleMapper.java
[WARNING] Existing file F:\gitrepo\mybatis_gene\.\src\main\java\mybatis_gene\entity\SysRole.java was overwritten
[WARNING] Existing file F:\gitrepo\mybatis_gene\.\src\main\java\mybatis_gene\dao\SysRoleMapper.java was overwritten
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time: 0.786s
[INFO] Finished at: Sat Jan 05 19:57:19 GMT+08:00 2019
[INFO] Final Memory: 6M/121M
[INFO] ------------------------------------------------------------------------

```
