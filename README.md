# OpenList v4.1.0 部署指南

适用于 Claw Cloud Run

| 字段 | 值 | 字段 | 值 |
|:---|:---|:---|:---|
| Image Name | `openlistteam/openlist:v4.1.0` | Type | `EmptyDir` |
| Port | `5244` | Mount Path | `/opt/openlist/data` |
| CPU | 0.5 Core | Size | `1Gi` |
| Memory | 512 Mi | | |

| 环境变量 |
|:---|
| `PUID=0`<br>`PGID=0`<br>`UMASK=022` |
