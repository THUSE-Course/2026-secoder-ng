# Agent 可以加速工作，但不能绕过工程边界

<div class="grid grid-cols-2 gap-10 mt-10 text-left">

<div>

### 适合交给 Agent

- 查阅文档和仓库结构
- 生成或修改小范围代码/配置
- 运行测试和读取流水线结果
- 查询个人命名空间中的资源与日志

</div>

<div>

### 必须保留确认

- 令牌、kubeconfig 和密码
- 删除资源、改权限、轮换凭据
- 合并代码和发布高风险变更
- 无法验证结果时的“已完成”判断

</div>

</div>

<div class="mt-10 text-left">
  最小权限 + 可审查变更 + 可验证结果 = 可控的 Agent 协作。
</div>

<!-- [讲者备注]
- [待填：课程允许的 Agent 权限和禁止事项]
- [待填：一个失败或需要人工确认的反例]
-->

<!-- [Sources]
- Kubernetes 凭据安全：/home/ajax/source/secoder-new/man/src/profile.md
- Agent 认证和 API 约定：/home/ajax/source/secoder-new/secoder-backend/docs/AGENTS.md
-->
