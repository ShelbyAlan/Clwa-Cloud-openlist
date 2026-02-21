# OpenList v4.1.0 部署指南

<table width="100%">
  <thead>
    <tr>
      <th width="33.3%">1. 基础配置</th>
      <th width="33.3%">2. 环境变量</th>
      <th width="33.3%">3. 存储配置</th>
    </tr>
  </thead>
  <tbody>
    <tr valign="top">
      <td>
        <b>Image Name</b><br>
        <code>openlistteam/openlist:v4.1.0</code><br><br>
        <b>Port</b><br>
        <code>5244</code><br><br>
        <b>CPU</b><br>
        <code>0.5 Core</code><br><br>
        <b>Memory</b><br>
        <code>512 Mi</code>
      </td>
      <td>
        <code>PUID=0</code><br>
        <code>PGID=0</code><br>
        <code>UMASK=022</code>
      </td>
      <td>
        <b>Type</b><br>
        <code>EmptyDir</code><br><br>
        <b>Mount Path</b><br>
        <code>/opt/openlist/data</code><br><br>
        <b>Size</b><br>
        <code>1Gi</code>
      </td>
    </tr>
  </tbody>
</table>
