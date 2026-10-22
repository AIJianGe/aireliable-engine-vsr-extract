# vsr_extract（本地工具占位，不随仓库分发）

本目录**不是** AIReliable 平台引擎（无 `manifest.yaml`），仅为本地调试
`video-subtitle-remover` 上游源码时使用的临时解压位置。

- 上游项目：<https://github.com/YaoFANGUK/video-subtitle-remover>
- 当前内容：`video-subtitle-remover-main/`（上游整包，约 964MB）
- 入库策略：**不入库**。`.gitignore` 已排除
  `engines/vsr_extract/video-subtitle-remover-main/`，平台仓库不跟踪该目录。
- 获取方式：按需从上游仓库下载对应 Release / Source ZIP 后解压到本目录。

如需将其纳入正式引擎，请先补 `manifest.yaml`、`LICENSE`、`NOTICE`，
并按任务 67 的仓库拆分流程单独建仓（只提交适配层，不提交上游整包）。
