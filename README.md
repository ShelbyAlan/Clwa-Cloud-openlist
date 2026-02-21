# OpenList v4.1.0 部署指南

> **爪哇云：[claw.cloud](https://claw.cloud)**

<table width="100%">
  <thead>
    <tr>
      <th width="33.3%">基础配置</th>
      <th width="33.3%">环境变量</th>
      <th width="33.3%">存储配置</th>
    </tr>
  </thead>
  <tbody>
    <tr valign="top">
      <td>
        <b>镜像名称</b><br>
        <code>openlistteam/openlist:v4.1.0</code><br><br>
        <b>端口</b><br>
        <code>5244</code><br><br>
        <b>CPU / 内存</b><br>
        <code>0.5 Core</code> / <code>512 Mi</code>
      </td>
      <td>
        <code>PUID=0</code><br>
        <code>PGID=0</code><br>
        <code>UMASK=022</code>
      </td>
      <td>
        <b>挂载路径</b><br>
        <code>/opt/openlist/data</code><br><br>
        <b>容量大小</b><br>
        <code>1G</code>
      </td>
    </tr>
  </tbody>
</table>
