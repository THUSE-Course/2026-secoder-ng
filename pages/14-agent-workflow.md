# 一个 Agent 工作流：每一步都留下可回看的证据

<div class="mt-12 text-2xl leading-loose">

读取说明
<span class="opacity-50">→</span>
确认目标
<span class="opacity-50">→</span>
修改代码或配置
<span class="opacity-50">→</span>
提交并部署
<span class="opacity-50">→</span>
验证结果

</div>

<div class="grid grid-cols-5 gap-3 mt-12 text-left text-sm opacity-80">
  <div>API、仓库和命名空间边界</div>
  <div>人确认范围与风险</div>
  <div>产生可审查的 diff</div>
  <div>触发 CI/CD</div>
  <div>读取状态、日志、指标</div>
</div>

<!-- [讲者备注]
- [待填：Agent 处理一个小改动的完整示例]
- 强调提交 diff 和平台反馈，而不是只展示 Agent 的聊天记录。
-->

<!-- [Sources]
- API 使用说明：/home/ajax/source/secoder-new/secoder-backend/docs/AGENTS.md
- 部署手册：/home/ajax/source/secoder-new/man/src/deploy.md
-->
