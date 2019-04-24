# springboot-mybatis

[github API](https://api.github.com/repos/chywx/springboot-mybatis/releases/latest)

> springboot 整合数据库demo，以便复用，使用了lombok，需要安装对应的插件



## 自动生成测试类

[csdn博客参考](https://blog.csdn.net/jy02268879/article/details/83346701)

## 使用provider注解
> user类

## 测试调用存储过程

> that ok

## 测试邮件发送

> spring-boot-starter-mail

## pageHelger

> 添加`pageHelger`分页插件

## 注解aop
[云栖社区借鉴](https://yq.aliyun.com/articles/576452)

---

> 上传添加github.sql

--- 
## 添加`swagger` API界面

[http://localhost:8081/swagger-ui.html](http://localhost:8081/swagger-ui.html)

## 集成`redis`

> 默认集成了下面这两个
```
@Autowired
private StringRedisTemplate stringRedisTemplate;
@Autowired
private RedisTemplate redisTemplate;
```
> 添加分布式锁
```$xslt
// 对应redis的配置
com.ocean.redis
// 对应redis分布式锁工具类
com.ocean.redis.lock
lock2 https://www.cnblogs.com/liuyang0/p/6744076.html
```
---

## 整合MongoDB

> com.ocean.mongo.MongodbController
> 
> 基本的增删改查

[可以使用异步非阻塞框架webflux](https://github.com/chywx/xfq_study1)



## 整合rabbitmq
> 不是很了解，待研究
> com.ocean.rabbitmq



