# 一张地图：代码最后会经过哪些环节？

<div class="mt-12 text-2xl leading-loose">

账号入口
<span class="opacity-50">→</span>
GitLab 仓库
<span class="opacity-50">→</span>
CI/CD 流水线
<span class="opacity-50">→</span>
Kubernetes 命名空间
<span class="opacity-50">→</span>
质量与运行反馈

</div>

<div class="grid grid-cols-5 gap-3 mt-12 text-sm opacity-80">
  <div>注册 / 登录<br />组队 / 凭据</div>
  <div>代码 / MR<br />Registry</div>
  <div>构建 / 测试<br />部署</div>
  <div>服务 / 日志<br />资源状态</div>
  <div>SonarQube<br />Grafana</div>
</div>

<!-- [讲者备注]
- [待填：平台截图或流程动画]
- 这一页建立全课的共同语言，后续每个组件都放回这条链上。
-->
