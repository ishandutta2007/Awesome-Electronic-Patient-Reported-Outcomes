# Awesome-Electronic-Patient-Reported-Outcomes

# 顶级电子患者报告结局 (ePRO) 平台生态系统



**SaaS 产品与开源 GitHub 项目精选列表**

*聚焦患者自报结局采集、电子临床结局评估与去中心化临床试验数据管理*

**最后更新：2026 年 9 月**



本仓库追踪**电子患者报告结局 (ePRO)** 领域的知名 **SaaS 平台**与**开源项目**。这些工具帮助临床研究团队、制药企业和 CRO 通过电子方式采集患者自报的症状、功能状态和生活质量数据，支持去中心化临床试验、远程患者监测和真实世界证据研究。



**示例**包括 Medable、Signant Health、Clario、YPrime、THREAD Science、Castor ePRO、CRScube、IQVIA eCOA、Kayentis、TrialKit、Veeva ePRO、Clinical Ink、CRF Health、Medidata Patient Cloud、Oracle ePRO、ClinOne 和 eClinical Solutions（该领域的领先者）。



**开源重点**：与许多企业软件类别不同，ePRO 领域存在**少数成熟的开源替代方案**，主要集中在电子数据采集 (EDC) 平台和同意管理层面。完整的企业级 ePRO 系统（如 Medable、Signant）仍然以商业产品为主导，但开源 EDC 平台通过模块化扩展（如 ePRO 模块）可以提供可行的自托管替代方案。本列表重点收录**可自托管的 EDC/ePRO 平台**、**开源同意管理工具**和**FHIR 兼容的表单渲染器**。



欢迎贡献！提交 PR 以添加/更新条目。保持描述事实性，并链接到官方网站。



## 目录



- [SaaS/托管平台](#saas托管平台)

- [开源 GitHub 项目](#开源github项目)

- [如何贡献](#如何贡献)

- [免责声明](#免责声明)



## SaaS/托管平台



- **[Medable](https://www.medable.com/)**

  去中心化临床试验平台，提供 ePRO、eCOA、eConsent 和远程数据采集。专注于以患者为中心的数字化临床试验设计，支持 BYOD（自带设备）模式。



- **[Signant Health](https://www.signanthealth.com/)**

  临床结局评估领域的领先供应商，提供 eCOA、ePRO、eConsent 和电子日记。在神经科学、精神病学和疼痛研究领域有深厚积累。



- **[Clario](https://clario.com/)**

  临床研究终点和技术解决方案提供商，提供 eCOA、ePRO、心脏安全、医学影像和呼吸终点服务。由 ERT 和 Bioclinica 合并而成。



- **[YPrime](https://www.yprime.com/)**

  eClinical 技术平台，提供 eCOA、ePRO、IRT 和临床数据管理。以其快速部署和灵活的电子临床解决方案著称。



- **[THREAD Science](https://www.threadresearch.com/)**

  去中心化临床试验平台，提供 ePRO、eCOA、远程患者监测和虚拟访视工具。专注于将临床研究带入患者家庭。



- **[Castor ePRO](https://www.castoredc.com/)**

  Castor EDC 平台中的 ePRO 模块。提供基于网络的电子患者报告结局采集，与 Castor 的电子数据采集系统无缝集成。



- **[CRScube](https://www.crscube.io/)**

  综合 eClinical 平台，包含 cubePRO（ePRO）、cubeCDMS（EDC）、cubeIWRS（RTSM）和 cubeDDC（eSource）。所有解决方案共享同一数据结构和配置工具 。



- **[IQVIA eCOA](https://www.iqvia.com/)**

  IQVIA 的电子临床结局评估平台，提供 ePRO、eCOA、eConsent 和患者参与工具。集成 IQVIA 的临床研究生态系统。



- **[Kayentis](https://www.kayentis.com/)**

  专注于 eCOA 和 ePRO 的临床研究技术提供商，在眼科、呼吸和皮肤病学等领域有专业积累。



- **[TrialKit](https://www.trialkit.com/)**

  基于云的临床研究平台，提供 ePRO、eCOA、EDC 和 eConsent 功能。以其灵活性和可配置性著称。



- **[Veeva ePRO](https://www.veeva.com/)**

  Veeva Clinical Suite 中的 ePRO 模块，与 Veeva Vault CDMS 集成，为生命科学行业提供端到端临床数据管理。



- **[Clinical Ink](https://www.clinicalink.com/)**

  eSource 和 ePRO 平台，专注于将临床数据采集直接带入患者访视流程，减少数据转录和查询。



- **[CRF Health](https://www.crfhealth.com/)**

  eCOA 和 ePRO 领域的早期先驱之一（现为 Signant Health 的一部分），专注于电子临床结局评估。



- **[Medidata Patient Cloud](https://www.medidata.com/)**

  Medidata 的患者中心云平台，提供 ePRO、eCOA、eConsent 和患者参与工具，与 Medidata Rave EDC 深度集成。



- **[Oracle ePRO](https://www.oracle.com/)**

  Oracle Health Sciences 中的 ePRO 模块，与 Oracle Clinical One 平台集成，提供电子患者报告结局采集。



- **[ClinOne](https://clinone.com/)**

  临床试验患者参与平台，提供 eConsent、ePRO 和远程访视工具，专注于简化患者体验。



- **[eClinical Solutions](https://www.eclinicalsol.com/)**

  提供 eClinical 数据管理平台，包括 elluminate 数据科学平台，支持 ePRO 和 eCOA 数据集成与分析。



## 开源 GitHub 项目



- **[OpenClinica](https://github.com/OpenClinica/OpenClinica)**

  全球首个商业开源临床试验软件，用于电子数据采集 (EDC) 和临床数据管理 (CDM)。支持构建研究、创建 eCRF、设计规则/编辑检查、安排患者访视、通过网络采集 eCRF 数据、监测和管理临床数据、审计追踪和电子签名、基于角色的访问控制。**LGPL 许可证**。社区版免费，云托管版提供额外的 ePRO、随机化和报告模块 。



- **[LibreClinica](https://github.com/reliatec-gmbh/LibreClinica)**

  OpenClinica 的社区驱动后继者。提供所有 GCP 合规临床试验所需功能：基于网络的电子表单 (eCRF) 带版本管理、简单和复杂字段验证、完整审计追踪和电子签名、双人数据录入支持、差异笔记和源数据核查 (SDV)、CDISC ODM-XML 导入、导出为 CDISC ODM-XML/TSV/Excel/SPSS/SAS。支持 OpenRosa API 后端，用于与 **ODK 生态系统集成以进行移动数据采集（如 ePRO 和 eCOA）**。LGPL-3.0，Java 技术栈 。



- **[Arcwell](https://github.com/arcweb/arcwell)**

  Arcweb Technologies 发布的开源临床研究平台。使医疗机构能够设计、构建和部署临床试验与健康方案，利用强大的规则引擎支持自主临床运营和决策支持。**在电子数据采集 (EDC) 系统内进行电子临床结局评估 (eCOA) 和采集患者报告结局 (ePRO)**，确保研究可以在同一基础设施上轻松升级。已在宾夕法尼亚大学佩雷尔曼医学院和另一家医疗机构成功实施，后者处理 4,000+ 自定义临床规则。**Apache 2.0 许可证** 。



- **[ClinCapture](https://www.clincapture.com/)**

  经临床验证的开源电子数据采集 (EDC) 软件。其 eClinical Suite 包含 **ePRO 模块**（直观的患者数据采集平台）、CTMS 集成、离线模式（通过 Mi-Co 合作支持平板和数字笔）、生物标本追踪、安全系统和 CDISC 数据转换。ePRO 数据自动安全地导入 ClinCapture 数据库。免费开源，自托管 。



- **[clinicedc](https://github.com/clinicedc)**

  基于 Django 的多站点纵向临床试验数据管理框架。提供一套 Python 模块，用于构建 EDC/eSource 系统，处理知情同意、计划数据采集、质量保证、试验监测、报告、不良事件、临床事件分级、数据导出和审计。源代码在 GitHub 上公开发布，最新试验有可在本地构建运行的演示。**GPL-3.0**。已用于哈佛 T.H. Chan 公共卫生学院、博茨瓦纳-哈佛艾滋病研究所合作项目等机构的 NIH 资助试验 。



- **[CHAVI PROM](https://www.preprints.org/manuscript/202508.1013)**

  开源电子患者报告结局测量系统的更新版本。基于 **Django** 完全重写（此前为 Drupal），使用 PostgreSQL 数据库、Tailwind CSS 和 HTMX 前端。关键特性：**构造 (Construct) 与条目 (Item) 的详细定义**（含方向、阈值分数、常模均值和标准差）、**方程编辑器**（使用 Lark 解析器处理复杂评分逻辑，支持多行方程和 if-else 语句）、**复合构造分数**（如 FACT TOI）、**媒体响应类型**（患者可录制语音和视频）。患者信息在数据库中加密存储 。



- **[REDCapPRO](https://github.com/AndrewPoppe/REDCap-PRO)**

  REDCap 外部模块，**以符合监管规定的方式实现患者报告结局 (PRO)**。作为独立于 REDCap 的研究数据采集系统运行，支持多因素认证、参与者自注册、自动注册和 API。参与者使用单独的用户名和密码登录，与 REDCap 研究团队凭证分离。支持数据访问组 (DAG) 管理、密码重置和角色 based 访问控制 。



- **[PrivacyLens](https://github.com/PrivacyLens)**

  卡内基梅隆大学可用性研究人员开发的下一代同意管理 UI。支持知情同意机制，利用联邦基础设施进行信任验证。功能包括：以用户友好形式显示正在发送的属性名称和值、区分必需和可选属性、多种“同意频率”选项、肯定性操作、使用先前同意日志通知用户、撤销、将属性分组为同意捆绑。**开源**，基于 NSTIC/NIST 资助的研究 。



- **[lforms-fhir-app](https://github.com/LHNCBC/lforms-fhir-app)**

  SMART on FHIR 应用，使用 LHC-Forms 小部件处理 **FHIR SDC (Structured Data Capture) Questionnaire 和 QuestionnaireResponse 资源**。可在支持 SMART on FHIR 的 EHR 系统中启动，显示 FHIR 表单并采集数据为 QuestionnaireResponse 资源。支持 FHIR Questionnaire STU3 和 R4 版本，以及 SDC 实施指南的部分内容。可用于构建自定义 ePRO 表单渲染器 。



- **[smart-forms](https://github.com/aehrc/smart-forms)**

  CSIRO 澳大利亚 e-Health 研究中心开发的 **React 基础 FHIR 驱动表单应用**。实现 HL7 FHIR 规范中的 Questionnaire 和 QuestionnaireResponse 资源、**Structured Data Capture (SDC) 实施指南**，并利用 SMART on FHIR 能力。可由初级保健临床管理系统启动，采集标准化健康检查信息。TypeScript/React，开源 。



### 其他强开源选项



- **EDC 平台**：**OpenClinica** 社区版（成熟、LGPL）、**LibreClinica**（OpenClinica 后继、支持 ODK/ePRO 集成）、**ClinCapture**（含集成 ePRO 模块）。

- **同意管理**：**PrivacyLens**（CMU 开发、功能丰富）、**gICS**（模块化知情同意服务、已记录 336,000+ 同意和 2,400+ 撤回）、**REDCap 同意框架模块** 。

- **FHIR 表单渲染**：**lforms-fhir-app**（SMART on FHIR 表单显示）、**smart-forms**（CSIRO 开发的 SDC 表单应用）。

- **PRO 分析**：**PROreg**（R 包，患者报告结局回归分析方法，支持混合效应模型和 beta-二项分布分析）。



**构建自定义系统的框架**：结合 **LibreClinica** 或 **OpenClinica** 社区版作为核心 EDC 平台，**smart-forms** 或 **lforms-fhir-app** 作为 FHIR 兼容的 ePRO 表单渲染器，**PrivacyLens** 或 **gICS** 处理知情同意管理，**REDCapPRO** 提供符合监管的 PRO 采集。添加 **PostgreSQL** 和 **ODK** 生态系统支持移动数据采集。



## 如何贡献



1. Fork 仓库。

2. 在 `README.md` 中添加/编辑条目（遵循现有格式）。

3. 包含：名称、链接、1–2 句描述，以及是 SaaS 还是开源。

4. 提交 PR 并附简短说明。



如果你觉得这个仓库有用，请点星！



## 免责声明



- 这是一个**社区精选**列表——并非详尽无遗，也不构成认可。

- ePRO 系统处理敏感的临床试验和患者数据；确保符合 21 CFR Part 11、GCP、HIPAA 和 GDPR 等适用法规。

- **开源现实**：完整的开源 ePRO 系统（可直接替代 Medable、Signant）尚不成熟。可行的自托管路径是组合 **OpenClinica/LibreClinica** EDC 平台与 **FHIR 兼容表单渲染器**（smart-forms、lforms-fhir-app）及**同意管理工具**（PrivacyLens、gICS）。这种组合可覆盖 ePRO 核心功能，但需要工程投入进行集成和验证。



---



**为临床研究协调员、数据管理员、CRO 技术团队和数字健康开发者打造。**

让临床试验数据采集更开放、透明、以患者为中心。
