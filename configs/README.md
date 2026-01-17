# 配置目录说明

该目录用于集中管理各类组件配置，来源于原 `conf/` 目录的拆分与归档。

## 原始路径映射

| 原始路径 | 新路径 |
| --- | --- |
| `conf/node3_nginx/` | `configs/nginx/` |
| `conf/node1_redis/` | `configs/redis/` |
| `conf/node2_tomcat/` | `configs/tomcat/` |
| `conf/node1_crontab.txt` | `configs/cron/node1_crontab.txt` |

## 目录用途

- `nginx/`：Nginx（反向代理）配置。
- `mysql/`：MySQL（数据库）配置（按需补充）。
- `redis/`：Redis（缓存）配置。
- `tomcat/`：Tomcat（应用容器）配置。
- `cron/`：计划任务（Crontab）配置。
