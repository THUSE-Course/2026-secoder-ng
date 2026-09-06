---
theme: default
title: SECoder 新平台简介
subtitle: "2026 秋季软工小作业第二讲"
author: 软件工程课程助教团队 Ajax
info: |
  Introduction to the new SECoder platform.
  Platform: https://t.secoder.net
class: text-center
highlighter: shiki
lineNumbers: true
drawings:
  persist: false
transition: slide-left
mdc: true
aspectRatio: 16/9
fonts:
  sans: Noto Sans CJK SC
  mono: JetBrains Mono
---

# SECoder <br> Next Generation

---

# 资料速查

- 平台入口: [t.secoder.net](https://t.secoder.net) (校内访问)
- 平台文档: [thuse-course.github.io/man/](https://thuse-course.github.io/man/) (国内访问性一般); [man.t.secoder.net](https://man.t.secoder.net/) (校内访问)
- GitLab 文档: [docs.gitlab.com](https://docs.gitlab.com/)
- SonarQube 文档: [docs.sonarsource.com](https://docs.sonarsource.com/)
- 容器教程与文档: [Container Internals](https://developers.redhat.com/learn/openshift/container-internals); [Docker 101](https://www.docker.com/101-tutorial/)
- Kubenetes 基础教程: [kubernetes-basics](https://kubernetes.io/docs/tutorials/kubernetes-basics/), [tutorials](https://kubernetes.io/docs/tutorials/)
- 往年资料: [上学期小作业讲 Docker 和 CI/CD](https://thuse-course.github.io/2026-deploy/); [去年讲 Docker 和 CI/CD](https://thuse-course.github.io/2025-deploy/); [暑培讲前后端](https://summer26.net9.org/frontend-and-backend/index_frontend-and-backend/)

<br>

# 使用方法: 打开 Codex, 把链接丢给他让他讲

---
layout: section
---

# SECoder *Refreshed*

---

# SECoder *Refreshed*

<div style="display: flex; align-items: center; justify-content: center; gap: 2rem;">
  <img src="./assets/secoder-old.png" alt="SECoder Old" style="width: 45%;" />
  <span style="font-size: 2rem;">→</span>
  <img src="./assets/secoder.png" alt="SECoder" style="width: 45%;" />
</div>

<!--
我们完整重建了 SEcoder, 用现代的前后端重建. UI 现在更好看了, 我们支持三种语言和暗色模式. 而在 UI 的可用性上我们也做了文章, 希望给大家良好的体验.
-->

---

# Components *Updated*

<div style="display: grid; grid-template-columns: repeat(2, minmax(0, 1fr)); gap: 1rem 1.5rem; width: 100%;">
  <div style="display: flex; justify-content: center; gap: 0.75rem;">
    <div style="width: 45%; text-align: center;">
      <img src="./assets/gitlab-old.png" alt="GitLab Old" style="width: 100%; height: 9rem; object-fit: contain;" />
      <div>GitLab 13.3.0</div>
    </div>
    <div style="display: flex; align-items: center; font-size: 1.5rem;">→</div>
    <div style="width: 45%; text-align: center;">
      <img src="./assets/gitlab.png" alt="GitLab" style="width: 100%; height: 9rem; object-fit: contain;" />
      <div>GitLab 19.3.0</div>
    </div>
  </div>

  <div style="display: flex; justify-content: center; gap: 0.75rem;">
    <div style="width: 45%; text-align: center;">
      <img src="./assets/sonar-old.png" alt="SonarQube Old" style="width: 100%; height: 9rem; object-fit: contain;" />
      <div>SonarQube 8.4.2</div>
    </div>
    <div style="display: flex; align-items: center; font-size: 1.5rem;">→</div>
    <div style="width: 45%; text-align: center;">
      <img src="./assets/sonar.png" alt="SonarQube" style="width: 100%; height: 9rem; object-fit: contain;" />
      <div>SonarQube 26.7.0</div>
    </div>
  </div>

  <div style="display: flex; justify-content: center; gap: 0.75rem;">
    <div style="width: 45%; text-align: center;">
      <img src="./assets/grafana-old.png" alt="Grafana Old" style="width: 100%; height: 9rem; object-fit: contain;" />
      <div>*404*</div>
    </div>
    <div style="display: flex; align-items: center; font-size: 1.5rem;">→</div>
    <div style="width: 45%; text-align: center;">
      <img src="./assets/grafana.png" alt="Grafana" style="width: 100%; height: 9rem; object-fit: contain;" />
      <div>Grafana v13.2.0</div>
    </div>
  </div>

  <div style="display: flex; justify-content: center; gap: 0.75rem;">
    <div style="width: 45%; text-align: center;">
      <img src="./assets/observability-old.png" alt="Observability Old" style="width: 100%; height: 9rem; object-fit: contain;" />
      <div>*手搓的, 坏了*</div>
    </div>
    <div style="display: flex; align-items: center; font-size: 1.5rem;">→</div>
    <div style="width: 45%; text-align: center;">
      <img src="./assets/observability.png" alt="Observability" style="width: 100%; height: 9rem; object-fit: contain;" />
      <div>Headlamp 0.45.0</div>
    </div>
  </div>

</div>

<!--
我们把旧的 SECoder 的各个组件都做了大升级, 核心的 GitLab 和 SonarQube 升级到了最新版 (好吧, 至少是一个月前的最新版), 致力于给大家现代的体验.
我们修好了 Grafana, 里面可以看到集群的历史情况; 引入了 Headlamp 替代旧 SECoder 手搓的一直坏的面板.
在大模型时代, 我们选择尽量使用标准件, 尽量减少定制件, 使得大模型能根据训练数据, 同学们也可以根据网上的大量资料熟悉我们的平台.
对于为数不多的定制件, 我们给出了详尽的文档, 希望大家能通过文档解决大部分问题.
-->

---

# Workflow *Standarized*

<div style="display: grid; grid-template-columns: minmax(0, 0.8fr) auto minmax(0, 2fr); gap: 0.75rem; align-items: center; width: 100%;">
  <div style="display: flex; flex-direction: column; align-items: center; gap: 0.35rem;">
    <img src="./assets/secoder-flow-old-1.png" alt="SECoder flow old 1" style="width: 100%; height: 5.5rem; object-fit: contain;" />
    <img src="./assets/secoder-flow-old-2.png" alt="SECoder flow old 2" style="width: 100%; height: 5.5rem; object-fit: contain;" />
    <img src="./assets/secoder-flow-old-3.png" alt="SECoder flow old 3" style="width: 100%; height: 5.5rem; object-fit: contain;" />
    <img src="./assets/secoder-flow-old-4.png" alt="SECoder flow old 4" style="width: 100%; height: 5.5rem; object-fit: contain;" />
  </div>

  <div style="font-size: 2.5rem;">→</div>

  <div style="display: flex; flex-direction: column; align-items: center; justify-content: center; justify-self: center; height: 85%; aspect-ratio: 16 / 9; overflow: hidden;">
    <img src="./assets/kustomization-flow.png" alt="Kustomization flow" style="width: 100%; height: 90%; object-fit: cover;" />
    <div style="color: grey;">*GPT Generated Image</div>
  </div>
</div>

<!--
在工作流上, 我们也选用了标准的 K8S 工作流, 即在仓库中存储 Kustomization 文件, 使用 kubectl apply 动态更新. 当然, 现在的公司可能更常用 ArgoCD / FluxCD 一类的 GitOps 方式部署, 简单起见我们省略了这一块.
-->

---
layout: section
---

# Stability *Improved?*

## 这学期是第一次用新 SECoder, 如果炸了怪我

---
