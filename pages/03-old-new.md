# 新 SECoder 把平台重心移到了完整开发闭环

| 老 SECoder | 新 SECoder |
| --- | --- |
| 项目首页和统计指标 | 账号、组队、服务入口统一管理 |
| 启用部署后获得关联容器 | 通过 CI/CD 声明式部署到个人命名空间 |
| 手工理解配置项与持久存储 | 用 Git 管理配置、资源和部署变更 |
| 看到项目结果 | 同时看到流水线、容器状态、日志和指标 |
| 主要面向人工操作 | 增加 `AGENTS.md`、JSON API 和 CLI 入口 |

<div class="mt-8 text-left text-lg opacity-75">
  核心变化：平台不只是“放代码和看统计”，而是把开发、交付、运行、反馈串起来。
</div>

<!-- [讲者备注]
- [待填：老平台具体痛点、迁移动机、稳定性案例或数据]
- 不把没有数据支撑的内容讲成精确性能指标。
-->

<!-- [Sources]
- 老平台内容：/home/ajax/source/secoder-new/secoder.pptx
- 学生手册：/home/ajax/source/secoder-new/man/src/overview.md
- 部署手册：/home/ajax/source/secoder-new/man/src/deploy.md
-->
