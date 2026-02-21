# OpenList v4.1.0 部署指南

适用于Claw Cloud Run 
## 镜像信息

| 项目 | 值 |
|:---|:---|
| 镜像名称 | `openlistteam/openlist:v4.1.0` |


## 基础配置

| 字段 | 值 |
|:---|:---|
| Image Name | `openlistteam/openlist:v4.1.0` |
| Port | `5244` |
| CPU | 0.5 Core |
| Memory | 512 Mi |

## 环境变量

| 变量名 | 值 | 说明 |
|:---|:---|:---|
| PUID | `0` | 
| PGID | `0` | 
| UMASK | `022` | 

## 存储配置

| 字段 | 值 |
|:---|:---|
| Type | `EmptyDir` |
| Mount Path | `/opt/openlist/data` |
| Size | `1Gi` |

