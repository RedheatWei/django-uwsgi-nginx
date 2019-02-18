# django-uwsgi-nginx

基于Ubuntu 17:10的Django+uwsgi+nginx源镜像

安装mysql库,Python3等

---

# 使用方法

```bash
~$ git clone HOST
~$ cd django-uwsgi-nginx
~$ docker build -t ubuntu17/django-uwsgi-nginx .
```

> 该镜像在/home/docker/code/app/默认存在一个空项目,使用时删除即可,Django代码仍然也是放置该目录下.
>
> ```
> 注意:静态文件应是Django项目的/static/目录,否则请自行修改.
> ```



