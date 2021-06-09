## php开发环境
基于PHP搭建的开发环境

## 配置修改

修改 .env
```shell script
# 改成自己电脑的IP
DOCKER_HOST_IP=改成自己电脑的IP

# 本地php项目的上级目录
APP_CODE_PATH_HOST=本地php项目的上级目录

# 持久卷位置,放在 ~/docker-volume 下
DATA_PATH_HOST=持久卷位置
```

## 其他使用总结

- [基于laradock+phpstorm配置单元测试](http://liuqh.icu/2019/04/01/php/php-docker-dan-yuan-ce-shi/)
- [基于laradock+phpstorm+xdebug开发环境](http://liuqh.icu/2019/03/11/php/php-dockerxdebug/)
- [基于laradock搭建非侵入式性能监控平台](http://liuqh.icu/2021/05/26/php/php-xing-neng-jian-ce/)
