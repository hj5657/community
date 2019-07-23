## 天星社区

## 资料
[Spring 文档](https://spring.io/guides)

[Spring Web](https://spring.io/guides/gs/serving-web-content/)

[es](https://elasticsearch.cn/explore)

[Github deploy key](https://developer.github.com/v3/guides/managing-deploy-keys/#deploy-keys)

[Bootstrap](https://v3.bootcss.com/getting-started/)

[Github OAuth](https://developer.github.com/apps/building-oauth-apps/creating-an-oauth-app/)

[Spring](https://docs.spring.io/spring-boot/docs/current/reference/html/boot-features-sql.html#boot-features-embedded-database-support)

[菜鸟教程](https://www.runoob.com/mysql/mysql-insert-query.html)
## 工具
[Git](https://git-scm.com/downloads)

[Visual Paradigm](https://www.visual-paradigm.com/cn/)

[Flyway](https://flywaydb.org/getstarted/firststeps/maven)

## 脚本
```sql
create table USER
(
	ID int auto_increment primary key not null ,
	ACCOUNT_ID VARCHAR(100),
	NAME VARCHAR(50),
	TOKEN CHAR(36),
	GMT_CREATE BIGINT,
	GMT_MODIFIED BIGINT
);

```

```
mvn flyway:migrate
mvn -Dmybatis.generator.overwrite=true mybatis-generator:generate
```