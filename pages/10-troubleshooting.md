# 出问题时：沿着“流水线 → 资源 → 日志 → 指标”定位

<div class="grid grid-cols-4 gap-5 mt-12 text-left">

<div>

### 1

GitLab Job 是否失败？

</div>

<div>

### 2

Pod / Service / Route 是否就绪？

</div>

<div>

### 3

容器日志报了什么？

</div>

<div>

### 4

资源配额或系统指标是否异常？

</div>

</div>

<div class="mt-12 text-left">
  每一步都留下证据：不要把“页面打不开”当作唯一诊断信息。
</div>

<!-- [讲者备注]
- [待填：一个从 Job 失败定位到具体配置的案例]
- [待填：Headlamp / Grafana / 日志截图]
-->

<!-- [Sources]
- 学生主界面与 Kubernetes 仪表板：/home/ajax/source/secoder-new/man/src/overview.md
- 平台观测配置：/home/ajax/source/secoder-new/cluster-config/base/secoder/core/serviceMonitor.yaml
-->
