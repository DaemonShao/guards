# guards
主机入侵检测系统(HIDS)

### 项目进度
1. 2018/1/7 :完成文件监控方面（暂时只是单线程监控文件夹及其子文件中的文件）
2. 2018/1/8 :完成多进程监控主机文件夹及其子文件夹中的文件，采用一个进程监控一个文件夹的方式。<br/>
   2018/1/8 :初步增加配置文件功能，采用yaml格式作为配置文件<br>
   2018/1/8 :加入watchdog模块监控目标目录下的文件变化
   
---
### 系统所需软件
1. python-devel开发包
```shell
#ubuntu环境
sudo apt-get install python3.5-dev

#centos环境
yum install -y python3.5-devel
```