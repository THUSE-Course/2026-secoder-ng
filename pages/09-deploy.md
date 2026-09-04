# 部署应用：把声明式配置交给 CI/CD

<div class="grid grid-cols-2 gap-10 mt-10 text-left">

<div>

### 你需要准备

- `kustomization.yaml`
- Route、前端、后端等补丁
- GitLab CI/CD 中的 `TOKEN` 和 `NAMESPACE`

</div>

<div>

### 平台负责连接

- 使用标准模板合成资源
- 在自己的 Kubernetes 命名空间中部署
- 通过 ApplySet 管理后续资源变化

</div>

</div>

<div class="mt-10 text-left text-lg opacity-75">
  目标不是记住每条命令，而是理解：代码、配置、镜像和运行资源都能被追踪。
</div>

<!-- [讲者备注]
- [待填：最小示例仓库、CI 文件、部署成功截图]
- [待填：课程要求的命名空间和变量说明]
-->

<!-- [Sources]
- 部署手册：/home/ajax/source/secoder-new/man/src/deploy.md
- 部署模板：/home/ajax/source/secoder-new/secoder-tmpl/examples/minimal/kustomization.yaml
-->
