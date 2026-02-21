# OpenList v4.1.0 部署指南

<table width="100%">
  <thead>
    <tr>
      <th width="33.3%">1. 基础配置 (Basic)</th>
      <th width="33.3%">2. 环境变量 (Env)</th>
      <th width="33.3%">3. 存储配置 (Storage)</th>
    </tr>
  </thead>
  <tbody>
    <tr valign="top">
      <td>
        <b>Image:</b><br><code>openlistteam/openlist:v4.1.0</code><br><br>
        <b>Port:</b> <code>5244</code><br>
        <b>CPU:</b> <code>0.5 Core</code><br>
        <b>Mem:</b> <code>512 Mi</code>
      </td>
      <td>
        <code>PUID=0</code><br>
        <code>PGID=0</code><br>
        <code>UMASK=022</code>
      </td>
      <td>
        <b>Type:</b> <code>EmptyDir</code><br>
        <b>Path:</b> <code>/opt/openlist/data</code><br>
        <b>Size:</b> <code>1Gi</code>
      </td>
    </tr>
  </tbody>
</table>
