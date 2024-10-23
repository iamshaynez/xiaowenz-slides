---
marp: true
paginate: true
theme: default
class:
  - invert
_class:
  - lead
  - invert
---

# Business Process in General

> Processes normally come with Service Level Agreement(SLA)

![](https://vip2.loli.io/2023/09/04/WeVuJIxNmG8pMc4.png)

---

# How Service Supporting Process

> Service to support process also has SLA

![bg right:60% contain](https://vip2.loli.io/2023/09/04/azB8xlIF4viDYo3.png)


---

# Gaps in Services Definition

- Service and tech components
- Interruption on service or tech component?

![bg right:60% contain](https://vip2.loli.io/2023/09/04/azB8xlIF4viDYo3.png)

---

# ITSM - Information Technology Service Management

> ITIL (Information Technology Infrastructure Library) is a framework designed to standardize the selection, planning, delivery, maintenance and overall lifecycle of IT services within a business.

---

# IT Production Management

> Incident / Problem / Change on a Service

- Incident: an unplanned interruption to a service, or reduction in the quality of a service
- Problem: a cause or potential cause of one or more incidents.
- Change: the addition, modification, or removal of anything that could have a direct or indirect effect on services

---

# Support Model in Production

![image.png](https://cdn.sa.net/2024/10/23/JQxSpCX4O8dYcWh.png)

---

# Incident and Incident Management

- 定义：服务被影响就是事故，不要纠结与技术组件是否工作。
- 管理：根因分析不是事故管理的重点，更快的恢复，更短的 MTTR 才是。

---

# Problem and Problem Management

- 定义：可能产生 Incident 的因素，不要纠结于是否技术组件有缺陷。
- 管理：见 Problem RCA 文章。

--- 

# Change and Change Management

- 定义：只要改，就是变更。
- 管理：在乎把不确定性转变为确定，在乎风险。
- 落地关键：在企业风险偏好，效率之间获得平衡。

> 重启是否是变更，存在争议。

ISO 认为重启改变了 State，因此应该做为变更管理。ITIL 没有强制定义，但业界更愿意把重启作为科技的 Operation 来管理，如果产生事故则按照事故和问题对应的制度流程管理。

---

# Role and Responsibility

- 运维：对当下的 Service Level Agreement 负责
  - 生产事故怎么修（指标还是治本）
  - 紧急变更是否要上（究竟有多急）
  - 问题（Problem）的优先级
- 研发：对降低生产风险负责
  - 根因分析，修复问题，配合紧急修复事故

![bg right:50% contain](https://cdn.sa.net/2024/10/23/JQxSpCX4O8dYcWh.png)

