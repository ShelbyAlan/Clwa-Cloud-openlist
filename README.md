# OpenList v4.1.0 部署指南

适用于 Claw Cloud Run

| 字段 | 值 |
|:---|:---|
| Image Name | `openlistteam/openlist:v4.1.0` |
| Port | `5244` |
| CPU | 0.5 Core |
| Memory | 512 Mi |

| 环境变量 |
|:---|
| `PUID=0`<br>`PGID=0`<br>`UMASK=022` |

| 存储配置 | 值 |
|:---|:---|
| Type | `EmptyDir` |
| Mount Path | `/opt/openlist/data` |
| Size | `1Gi` |
