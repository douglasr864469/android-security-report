# Android 系统漏洞安全研究资料

从防御视角梳理 Android 系统攻击面、漏洞类型、典型案例、编号与公告体系、底层架构与研究方法的公开研究资料，含一份总览报告、三份专题手册与一篇底层漏洞研究文章。

## 内容

- **总览报告**：[android-system-vulnerability-report.md](android-system-vulnerability-report.md)
  启动链与信任模型、攻击面分析、漏洞类型、8 个已修复典型案例、利用链与缓解、防御建议
- **系统底层漏洞研究文章**：[android-low-level-vulnerability-research.md](android-low-level-vulnerability-research.md)
  分层架构与安全边界、四类底层漏洞成因（内存安全／权限边界／Binder／设备驱动）、源码审计与模糊测试等研究方法、复现与影响评估要求、防护机制与研究挑战
- **通用漏洞类型手册**：[android-common-system-vulnerabilities.md](android-common-system-vulnerabilities.md)
  分层攻击面速览、11 类缺陷清单（识别特征与缓解）、自查观测点与判读、分角色行动清单、类型速查表
- **漏洞编号与公告体系手册**：[android-cve-and-security-bulletins.md](android-cve-and-security-bulletins.md)
  CVE / Android bug ID / OSV / CWE / 厂商编号的对应关系、SPL 机制、Android 与厂商公告分层结构、逐字段读公告、查询与核对实操
- **远程代码执行与权限提升专题手册**：[android-rce-and-privilege-escalation.md](android-rce-and-privilege-escalation.md)
  执行上下文与影响半径、提权三段式、RCE 与 EoP 根因模式、链条组装与缓解矩阵、17 条公开案例复盘、自查检测与处置优先级
- **适用对象**：安全学习者、企业安全管理者、Android 开发者、设备厂商与 ROM 维护者

## 说明

- 资料仅基于公开、已修复的漏洞信息，用于教育与防御目的
- 不包含可直接用于攻击的利用代码
- 案例与时间线均来自公开资料，具体修复版本请以厂商公告为准

## 参考

- [Android Security Bulletin](https://source.android.com/docs/security/bulletin)
- [Android Security Overview](https://source.android.com/docs/security)
- [OWASP MASTG](https://mas.owasp.org/MASTG/)

## 联系方式

咨询 Android 系统详情请联系 https://t.me/one00190

---

*本仓库内容仅供安全学习与防御研究使用。*
