# docker-redis

## 项目说明
- 基于docker-compose编排的redis主从配置，支持持久化
- 首先需要在docker环境下创建网络(如果你已创建,替换`docker-compose.yml`的网络配置即可)
## 项目结构

```text
.
├── README.md
├── redis-master
│   ├── conf
│   ├── data
│   └── docker-compose.yml
└── redis-slave
    ├── conf2
    ├── conf3
    ├── data2
    ├── data3
    └── docker-compose.yml
```
