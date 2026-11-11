<h1 align="center">Cong · ccccongggg</h1>

<p align="center">
  <img src="https://avatars.githubusercontent.com/u/239195140?v=4" width="110" alt="avatar"/>
</p>

<p align="center">
  <a href="https://ccccongggg.github.io"><img src="https://img.shields.io/badge/线上主页-Astro-056de8?style=flat-square&logo=astro&logoColor=white" alt="site"/></a>
  <img src="https://img.shields.io/badge/专业-智能制造工程-2E7A66?style=flat-square" alt="major"/>
  <img src="https://img.shields.io/badge/认证-初级PCB工程师-1F5C4D?style=flat-square" alt="pcb"/>
  <img src="https://img.shields.io/badge/坐标-济南·广州-orange?style=flat-square" alt="loc"/>
  <img src="https://img.shields.io/badge/方向-硬件·机器人·数字孪生-blue?style=flat-square" alt="focus"/>
</p>

<p align="center">
  <b>硬件打底</b>，往上补嵌入式与视觉算法 ｜ 2026 年 8 月底到 11 月上旬，两个半月连续 7 场黑客松 ｜ 习惯把还很模糊的想法做成能演示、能拆开看的实物
</p>

---

### 🔭 现在

- 在把 **GalbotCare** 的「虚实一致性」做法抽成模板：孪生环境和真机共用同一份动作定义，交付前跑四层校验，堵死「孪生能演、真机被拒」。
- 补三块短板：机械臂强化学习、工业数字孪生、产品定义方法。
- 具体过程写在各仓库的 `需求文档` / `项目进度` / `项目总结` 里——更愿意让工程痕迹自己说话。

### 🦾 硬件 / 机器人

| 项目 | 是什么 | 做到什么地步 | 技术 |
|---|---|---|---|
| **[伊宝 YiBao](https://github.com/ccccongggg/YiBao)**<br><sub>SheNicest 千人黑客松 · 硬件赛道入围奖 · 最佳人气奖</sub> | 能真的接管电脑的桌面机器人：机身模块化可拆装，云台跟着人脸转 | 固件自检 + 云台跟踪 + 三代外壳模型已落地；官方 SDK 安装包未入库 | ESP-IDF + ESP32-S3-N16R8 舵机固件 · Insta360 Link 2 云台（YuNet 检测 / SFace 识别 / P 控制）· DirectShow 守护进程（<10 ms 响应）· SolidWorks 三代外壳 |
| **[陪一把 GalbotCare](https://github.com/ccccongggg/GalbotCare)**<br><sub>JUNCTION CHINA 2026 · 具身智能赛道（GALBOT G1）</sub> | 认知症老人陪伴看护。真机稀缺，先把机器人搬进浏览器：42 小时内从需求拆解做到答辩材料 | 数字孪生 + 动作调试台 + 四层一致性校验 + dry-run 清单闭环；真机 dry-run 待验收 | Three.js 数字孪生 · FastAPI + WebSocket 桥 · A* 栅格导航 · 33 关节 URDF · 109 条 SDK 命令四层一致性校验 · 四链 12 段整链 |
| **[university-competitions](https://github.com/ccccongggg/university-competitions)** | 学科竞赛资料总仓，五个子仓索引：智能车 / 机械创新 / 电子设计 / 机电产品 / 先进成图 | 5 个有内容仓库已挂为子模块；`robot` 空仓库占位待首次提交 | 4 层 PCB · 传感器与电源/运放 · C |

### 🎯 AI 应用 / 产品

| 项目 | 是什么 | 做到什么地步 | 技术 |
|---|---|---|---|
| **[问全 Qall](https://github.com/ccccongggg/wenquan-interview-copilot)**<br><sub>京东黑客松 · AI 眼镜赛道</sub> | 眼镜 + 手机双端访谈助手：认真听的同时抓住该追问的点，会后按主线归纳且**每条要点带原话出处** | V0.6.0 开发预览：声音身份与多人建档；自动回归 148/148 通过；真实六人设备验收与线上部署未完成 | MemoMind Studio · Node 22 · WebSocket · 豆包流式 ASR · sherpa-onnx + WeSpeaker 声音身份建档 |
| **[弦养](https://github.com/ccccongggg/xianyang-s4)**<br><sub>西安黑客松 · AI 软件</sub> | 跟练八段锦，做对一个动作就拨响一根古琴弦；练完一套 = 弹完一曲 | 纯前端 H5 可离线运行；6039 帧真机实测标定；三级现场兜底（预录视频待真人拍摄） | Vite 6 + Vue 3.5 · MediaPipe Pose 33 点 · 自研八式判定器 + 骨骼稳定性滤波 · 真实古琴采样 |
| **[场景炼金师](https://github.com/ccccongggg/scene-alchemist)**<br><sub>知乎校园黑客松 · AI 软件</sub> | 把一篇好帖迁移到读者的真实处境里，长出不同解法，沉淀成一张可检索的场景应用网 | 主应用闭环（收藏台 / 场景工坊 / 星图 / 贡献入库）+ 起源原型；Mock 模式无需密钥即可演示 | Vue 3 + Vite · FastAPI + SQLite · 星图可视化（三层轨道环 = 照搬要改多深） |
| **[电子衣橱 outfit-mystic](https://github.com/ccccongggg/outfit-mystic)**<br><sub>西安开元黑客松 · 入围决赛</sub> | 只在你自己的衣橱里推荐穿搭；用塔罗给一个不用动脑的理由 | 主链路上传→抠底→打标→选款→文案跑通；三级断网兜底；美学规则 / 上身试穿未做 | rembg 抠底 · VLM 打标 · 塔罗约束 JSON · 规则引擎选款 |

### 🏫 校园与基础设施

| 项目 | 是什么 | 做到什么地步 | 技术 |
|---|---|---|---|
| **[实验室安全通关 Skill](https://github.com/ccccongggg/qilu-lab-safety-skill)**<br><sub>SkillHub 宝藏母校 · 实用刚需赛道</sub> | 把实验室规范做成可交互通关考核：学生边学边考，教师一键组考并发勋章式通过卡 | 双模式 + 三级知识库 + L1–L6 防作弊闭环 + 卡片生成器，零第三方依赖 | Python 3 标准库 · SKILL.md + 三级知识库 |
| **[QLU Campus Hub](https://github.com/ccccongggg/qlit-community-kb)**<br><sub>WorkBuddy 校园大使</sub> | 面向同一所学校的两套内容归并成 monorepo：对外社群知识库 + 对内校园资源库 | 两个子项目源码已归并；可见性边界与部署策略见仓库 README | Hexo 8 + Butterfly + Sveltia CMS · Astro 7 + Pagefind · EdgeOne Pages |
| **[个人主页](https://ccccongggg.github.io)** | 线上站点 | 静态站点已上线；Vue 3 + Vite + TS 重构版在 `personweb`（私有开发仓） | Astro 5 + Sveltia CMS + EdgeOne Pages |

### 🏁 七场黑客松 · 2026.08 → 11

| 时间 | 赛事 | 赛道 | 作品 | 结果 |
|:--|:--|:--|:--|:--|
| 08 | SheNicest 千人黑客松 | AI 硬件 | 伊宝 | **硬件赛道入围奖 · 最佳人气奖** |
| 09 | SkillHub 宝藏母校大赛 | Agent Skill | 实验室安全通关 Skill | — |
| 09 | 知乎校园黑客松 | AI 软件 | 场景炼金师 | 参与奖 |
| 09 | 西安开元黑客松 | AI 软件 | 电子衣橱 | **入围决赛** |
| 10 | 西安黑客松 | AI 软件 | 弦养 | — |
| 10 | 京东黑客松 | AI 眼镜 | 问全 Qall | — |
| 11 | JUNCTION CHINA 2026 | 具身智能 | 陪一把 GalbotCare | — |

> 没拿奖的那几场，收获通常更硬：问全那一轮让我看清「对话目标校验」在客户拜访、售后诊断里比访谈场景更刚；陪一把那 42 小时让我确认，机器人真正的难点不是单个模型，而是异常状态下怎么编排行为、怎么兜底。

### 🧰 技术栈

<p align="center">
  <img src="https://skillicons.dev/icons?i=c,python,js,nodejs,vue,threejs,fastapi,html,css,linux,git,docker,arduino,raspberrypi&perline=7" alt="stack"/>
</p>

- **硬件**　4 层 PCB（嘉立创 EDA）· ESP-IDF / ESP32-S3 · STM32 / MSPM0G3507 · 传感器、电源与运放电路
- **结构与制造**　SolidWorks 2024 高阶建模 · 3D 打印落地 · 舵机 / 云台机构 · URDF 与关节限位对照
- **软件**　Python · C · JavaScript · Vue 3 / Vite · Three.js · FastAPI · SQLite
- **AI**　MediaPipe Pose · YuNet / SFace · YOLO · 流式 ASR · sherpa-onnx · VLM 打标
- **在学**　机械臂强化学习 · 工业数字孪生 · FPGA · Rust

### 📐 干活的方式

- **需求先变成文档，再动手。** 赛首 4 小时先出需求拆解、FR 分级、硬约束和排期，再分派工卡；进度只认一份 `项目进度.md`。
- **单一事实源。** 动作定义 `motions.json` 被孪生和真机共用，改一处两边同时变，不维护两份。
- **交付前必须跑校验。** 109 条 SDK 命令四层对照、148/148 自动回归、6039 帧实测标定——先让机器判定，再让人看画面。
- **敢说「还没验收」。** README 里明确区分已验证与未验证的部分，不把预览版说成线上版。

### 🏅 竞赛与认证

- 山东省机电产品创新设计大赛 · **省级二等奖**（三维设计负责人）
- 全国大学生先进成图大赛 · **轻量化设计与 AI 应用二等奖** / 机械成图技术团体三等奖
- 全国大学生智能汽车竞赛、电子设计竞赛 · 队长 / 硬件（一体化 PCB 核心板、MaixCAM + 步进电机动态平衡）
- **初级 PCB 设计工程师**认证 · 计算机二级（C 语言）
- 第十二届 3S 杯物联网大赛、NVIDIA DGX Spark Agent Skills 挑战赛 · 参与

### 📫 联系

- 🌐 主页：<https://ccccongggg.github.io>
- ✉️ 邮箱：195311697@qq.com
- 💻 GitHub：[@ccccongggg](https://github.com/ccccongggg)

<sub>最近整理：2026-11 · 部分项目源码含私密配置或大体积模型，故仅保留结构与文档</sub>
