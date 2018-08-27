# springboot-mybatis-basic

## 开发版本 dev-2.0

## [Change Log](change_log.md)


## 结果

```java
2018-08-27 14:09:35.175 DEBUG 50560 --- [nio-8080-exec-1] e.m.demo1.mapper.TestMapper.selectOne    : ==>  Preparing: select * from TEST where id = ? 
2018-08-27 14:09:35.195 DEBUG 50560 --- [nio-8080-exec-1] e.m.demo1.mapper.TestMapper.selectOne    : ==> Parameters: 1(Integer)
2018-08-27 14:09:35.205  INFO 50560 --- [nio-8080-exec-1] p6spy                                    : #1535350175205 | took 9ms | statement | connection 0|select * from TEST where id = ?
select * from TEST where id = 1;
2018-08-27 14:09:35.214  INFO 50560 --- [nio-8080-exec-1] p6spy                                    : #1535350175214 | took 8ms | resultset | connection 0|select * from TEST where id = ?
select * from TEST where id = 1;
2018-08-27 14:09:35.250  INFO 50560 --- [nio-8080-exec-1] p6spy                                    : #1535350175250 | took 0ms | resultset | connection -1|select * from TEST where id = ?
ID = 1, NAME = tom;
2018-08-27 14:09:35.250 DEBUG 50560 --- [nio-8080-exec-1] e.m.demo1.mapper.TestMapper.selectOne    : <==      Total: 1
```

## LICENSE

![](LICENSE.png)