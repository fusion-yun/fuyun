# 浮云平台功能 · Features

本页按使用者视角介绍浮云平台的功能；具体可用范围以各站点的公告为准。

## 数据发布与长期保存

- **汇交与审查**：数据提供方在线提交数据集，经社区策划审查后发布；未通过审查的数据不公开。
- **版本与引用**：每个数据集有版本历史；已发布版本不改写，修正以新版本发布；支持规范的引用格式与持久标识（申请中）。
- **分级开放**：开放、延期开放、受限、仅元数据等访问级别；受限数据须授权访问。
- **符合 FAIR 原则**：机器可读元数据、标准许可声明、开放收割接口（OAI-PMH）与检索接口。
- **长期保存**：完整性校验、定期备份与恢复演练。

## 装置数据浏览与标准化

- **按炮号浏览**：在网页上浏览实验装置的原始诊断信号（需授权）。
- **标准数据模型**：按需把装置数据转换为国际通行的 IMAS 数据模型，统一单位与约定，便于跨装置、跨程序使用。
- **模拟结果管理**：兼容通行的模拟数据登记格式，保存模拟结果及其输入与运行信息。

## 统一标识

平台上的装置、炮次、数据集、处理过程、软件与标注都有稳定、可解析的网址标识：人打开看到说明页，程序取得机器可读的描述，引用时指向确定的版本。

## 协作与处理

- **数据仓**：个人与小组的数据仓，成员与可见范围可管理，协作修改有记录。
- **在平台内处理**：受保护的数据可在平台内用经过审核的程序处理，处理结果经检查后导出。
- **处理留痕**：每次处理都记录所用代码、环境、参数与输入，便于追溯与复现。

## 标注与审核

- 对数据片段添加注释与质量评估；评估须经他人审核后才生效。
- AI 生成的标注单独标记，须经人工确认。

## 智能体访问

通过模型上下文协议（MCP），AI 助手可以在与用户相同的权限下检索与读取平台数据，不越权、有记录。

## 身份与安全

- 统一身份认证（单点登录），按组授权。
- 全部访问与变更留有审计记录。
- 按国家网络安全等级保护要求建设与运维。

---

*English summary.* FuYun offers FAIR data publication with curation, versioning, access levels and preservation; browsing of device data by shot and on-demand conversion to the IMAS data model; stable resolvable identifiers for devices, shots, datasets, processing runs and software; personal and group workspaces with in-platform processing of protected data; recorded provenance; peer-reviewed annotations; AI-assistant access via MCP under the user's own permissions; single sign-on and full audit.
