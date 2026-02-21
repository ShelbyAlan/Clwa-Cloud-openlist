# OpenList v4.1.0 部署指南

*适用于 Claw Cloud Run*

| 基础配置 | 环境变量 | 存储配置 |
| :--- | :--- | :--- |
| **Image Name**: `openlistteam/openlist:v4.1.0` | `PUID=0` | **Type**: `EmptyDir` |
| **Port**: `5244` | `PGID=0` | **Mount Path**: `/opt/openlist/data` |
| **CPU**: 0.5 Core | `UMASK=022` | **Size**: `1Gi` |
| **Memory**: 512 Mi | | |
