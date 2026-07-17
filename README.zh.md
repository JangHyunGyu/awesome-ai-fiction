# Awesome AI Fiction · AI 小说与角色扮演工具全景 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> 一份逐条核实过的 AI 小说工具地图：续写与互动小说、作者向写作套件、酒馆角色扮演、AI 伴侣、听书 TTS、本地部署与 BYOK、角色卡格式、写作评测基准。

**这是什么。** 一份精选清单：每个条目只链官网或源码仓库，描述里至少带一个可核验的事实（定价模式 / 平台 / 是否开源 / 核心机制），不写"强大""惊艳"这类空话。

**为什么做。** 这个领域的工具散落在应用商店、GitHub、Discord 和国内各应用市场，而且产品悄悄停服是常态。通用"AI 工具导航"会把写小说和写营销文案的工具混在一起——这份清单只收小说方向。

**维护声明。** 全部链接于 **2026-07-18** 逐条人工核验。死链或停服的服务会打 `status:` 标注或直接移除，不做无声保留（见 [CONTRIBUTING.md](CONTRIBUTING.md)）。每个分类内按名称字母序排列，不置顶、不加粗。

English version → [README.md](README.md)

## 目录

- [续写与互动小说](#续写与互动小说)
- [作者向写作套件](#作者向写作套件)
- [酒馆前端与角色扮演平台](#酒馆前端与角色扮演平台)
- [AI 伴侣](#ai-伴侣)
- [听书与 TTS](#听书与-tts)
- [本地部署与 BYOK 基建](#本地部署与-byok-基建)
- [角色卡格式与工具](#角色卡格式与工具)
- [评测基准](#评测基准)
- [延伸资源](#延伸资源)

## 续写与互动小说

这类工具面向"读者"而非"作者"：拿一段已有的故事——你的草稿、一本导入的小说、一个开场设定——让 AI 接着往下写，由你掌舵方向。形态上覆盖文字冒险平台（AI Dungeon）、自研模型的故事机（NovelAI、AIのべりすと）、把每次续写保留成可对比分支的阅读器（Foreverse、StoryLord），以及从 2021 年就做续写的彩云小梦。

- [AI Dungeon](https://aidungeon.com) — Latitude 旗下文字冒险平台，2019 年上线运营至今；免费档 + 订阅解锁更强模型和更长记忆；带剧本（scenario）和多人模式。
- [AIのべりすと（AI Novelist）](https://ai-novel.com) — Bit192 出品的日语故事生成器，模型用 2TB+ 语料从零训练；浏览器免费可用，付费会员解锁更大模型；按其条款生成内容可商用。
- [彩云小梦](https://if.caiyunai.com) — 彩云科技的中文续写平台（网页 + iOS/Android），2021 年上线；多种续写风格、世界设定词条、角色对话；免费额度 + 会员订阅。其海外版 Dreamily 已于 2026-04-21 停止服务并删除用户数据。
- [Foreverse（新梦）](https://foreverse.cn) — 安卓端阅读器：导入本地 TXT/EPUB 小说后，划选任意段落让 AI 续写、改写、配图，每次续写保留为原文旁的独立分支；BYOK 自带 60+ 供应商 Key（密钥只存本机），也兼容 SillyTavern 角色卡（见[酒馆分类](#酒馆前端与角色扮演平台)）。
- [Friends & Fables](https://fables.gg) — 浏览器端桌面 RPG：AI 主持人 "Franz" 按 D&D 5e SRD 规则跑团，带战斗地图和长期设定记忆；免费档限每日回合数，订阅解锁不限量；支持单人或最多六人组队。
- [NovelAI](https://novelai.net) — 订阅制故事生成器（仅试用无永久免费档），模型自研训练；带 lorebook 上下文管理，另附动漫风图像生成。
- [Perchance AI 故事生成器](https://perchance.org/ai-story-generator) — Perchance 生成器平台上的免费故事写手，无需注册登录；逐段生成、逐段引导方向；社区共建、广告支持。
- [StoryLord](https://www.gennovel.app/zh-cn) — 网页应用：上传已有小说（TXT/DOCX/Markdown），AI 保持原著文风续写或改写；积分制，注册送 100 积分；支持含中文在内的 9 种语言。

## 作者向写作套件

作者向套件把 LLM 包进长篇创作需要的脚手架里——故事圣经、角色档案、大纲树、伏笔追踪——让模型别忘了书级设定。英文订阅阵营以 Sudowrite、NovelCrafter 为代表；国内一批工具（岱宗写作、蛙趣拼文、马良写作）直奔百万字网文的"不失忆"问题；Novel Mage、LocalProse、novelIDE 则走离线优先、一次买断的路线。

- [笔灵AI小说](https://ibiling.cn/novel-workbench/) — 笔灵旗下小说工作台：100+ 生成器（大纲 / 设定 / 人物）、长篇编辑器、爆款小说拆解与素材库；可免费试用，完整功能走会员付费。
- [岱宗写作](https://www.daizongxiezuo.com) — 自称"写作圈的 Cursor"的中文长篇工具：故事圣经 + 滚动摘要 + 知识图谱给 AI 项目级记忆，主打写到 200 章不忘设定；Windows/macOS/Android/iOS 多端客户端；默认模型开箱即用，也支持配置自定义模型。
- [解忧笔札AI](https://xs.jieyoupu.com) — 面向小说作者的中文助手，核心卖点是伏笔管理（未填坑检测、坑点图谱、填坑建议），另有人物小传、情节结构与节奏分析；在线版会员制，离线买断版 ¥980，支持 Ollama 本地模型（Windows/Mac/Android）。
- [LocalProse](https://www.localprose.com/en/) — 桌面写作套件（Windows/macOS/Linux）：内置本地 AI 引擎，首次启动按机器硬件配置自动适配；Pro 为一次性终身买断而非订阅；手机伴侣 App 经局域网 Wi-Fi 同步，不走云端。
- [马良写作](https://maliangwriter.com) — 中文网文创作平台：7 个专业 Agent（主管 / 结构 / 章节蓝图 / 内容生成 / 设定 / 一致性检查 / 纠错）共享知识图谱协作出章；免费注册，按模型调用量以积分计费。
- [Novel Mage](https://novelmage.com) — 离线优先的桌面写作软件（Windows/macOS），$99.99 一次性终身买断；AI 写作 Agent、角色 Codex、故事规划器可全程跑本地模型（Ollama/LM Studio），也可自带 OpenAI/Anthropic/Google Key。
- [NovelCrafter](https://www.novelcrafter.com) — 订阅制写作工作台，模型接入走 BYOK（自带 Key）；"codex" 设定百科（角色 / 地点 / 世界观）会自动注入提示词。
- [novelIDE（网文写作IDE）](https://github.com/qq1375828505/novelIDE) — 开源安卓端网文写作 IDE：完全单机运行，主 Agent + 6 个子 Agent（大纲 / 爽点检查 / 水文检测 / 去 AI 味等）调用 40+ 工具，带人物关系图谱、纯本地校对、EPUB 导出。
- [Sudowrite](https://www.sudowrite.com) — 订阅制小说起草工具，生成按积分计量；Story Bible 管理角色、大纲与文风并驱动整章起草。
- [蛙趣拼文](https://waqupin.com) — 中文桌面客户端，专业版 ¥89/年、定制版终身买断；接任意 OpenAI 兼容 API（DeepSeek / 本地 Ollama 等）；世界观·角色·伏笔三系统联动，支持最多千章的三层大纲生成，数据本地存储。

## 酒馆前端与角色扮演平台

"酒馆"指围绕角色卡、世界书（world info）、swipe 多候选和群聊组织的人设扮演聊天。两个阵营：自托管前端——模型和 API Key 都自己带（SillyTavern 是参考实现，RisuAI、Agnai 是开源同类）；托管平台——自带社区卡库和官方模型或代理接入（Character.AI、JanitorAI、Chub）。

### 前端（自托管 / BYOK）

- [Agnai](https://agnai.chat) — 开源多用户角色扮演平台，官方托管站与自部署皆可；支持 AI Horde、OpenAI 兼容、NovelAI 等多种后端；截至 2026 年年中仍在活跃开发。
- [Foreverse（新梦）](https://foreverse.cn) — 安卓客户端：SillyTavern 生态的角色卡（chara_card_v3）、世界书、正则脚本、Quick Reply 自动化可整套导入手机，与小说阅读器同居一个 App；BYOK 优先，应用本体不收订阅费。
- [KoboldAI Lite](https://lite.koboldai.net) — 免安装网页 UI，提供 story / adventure / chat 三种模式；可连 KoboldCpp、志愿算力网络 AI Horde 和多家云 API。
- [RisuAI](https://risuai.net) — 开源跨平台客户端（网页 / 桌面 / 移动网页）；作者即 Character Card V3 规范起草人，CharX 资产与 V3 装饰器原生支持。[源码](https://github.com/kwaroran/RisuAI)。
- [SillyTavern](https://sillytavern.app) — 自托管 Node.js 角色扮演前端，AGPL-3.0 开源，几乎可接一切本地与云端 LLM API；扩展生态庞大（向量记忆、TTS、生图）。[源码](https://github.com/SillyTavern/SillyTavern)。
- [TavernAI](https://tavernai.net) — SillyTavern 的前身、"酒馆" UI 的原型；2026 年 6 月推倒重写为 TavernAI 2，现为便携版 Windows/Linux 应用，带分支式聊天结构与统一提示词管理器。[源码](https://github.com/TavernAI/TavernAI)。

### 托管平台

- [Chai](https://chai-research.com) — 移动优先的角色聊天 App（iOS/Android），角色由用户创建；免费 + 订阅档。
- [Character.AI](https://character.ai) — 封闭平台，跑自研专有模型；免费可用，c.ai+ 订阅解锁加速与新功能；网页 + 移动 App。
- [Chub](https://chub.ai) — 用户自制角色卡的社区仓库，公开 API 被多家前端用作导入源；卡片托管免费，站内聊天（Chub Venus）为付费增值。
- [JanitorAI](https://janitorai.com) — 托管卡片平台：免费自研模型（JanitorLLM）打底，官方文档化的 proxy 通道支持自带 API Key（OpenRouter、DeepSeek 等）；另有 Pro 订阅。
- [PygmalionAI](https://pygmalion.chat) — 自筹资金的开源项目：托管聊天站免费，同时在 Hugging Face 放出开源权重扮演模型（Pygmalion-3 12B、Eleusis-12B，Apache-2.0）。
- [SpicyChat](https://spicychat.ai) — 托管角色扮演平台，角色用户自建；免费档 + 去排队订阅；成人内容需年龄验证后开放。

## AI 伴侣

伴侣类 App 优化的不是单局剧情而是一段持续关系：长期记忆、主动消息、语音通话、自拍照、好感度体系。Replika（2017）定义了这个品类；西方以 Kindroid、Nomi 在记忆深度上竞争；国内同赛道是 MiniMax 的星野（海外版 Talkie）、字节跳动的猫箱和阅文系的筑梦岛。

- [Kindroid](https://kindroid.ai) — 伴侣应用（网页/iOS/Android）：持久记忆、语音通话、AI 自拍；订阅制。
- [猫箱](https://maoxiangai.com) — 字节跳动旗下中文 AI 角色互动 App（原名"话炉"），基于豆包大模型；iOS/Android；免费可用，会员订阅解锁"灵动模式"与更长语音通话时长。
- [Nomi](https://nomi.ai) — 主打长期记忆与群聊的伴侣应用；免费档 + 订阅。
- [Replika](https://replika.com) — 2017 年上线，最早出圈的 AI 伴侣之一；3D 形象养成，免费 + Pro 订阅。
- [Talkie](https://www.talkie-ai.com) — MiniMax 星野的国际版；免费可玩，变现走 Talkie+ 订阅与 "Soul Card" 收集卡牌；原 App 在美区 App Store 下架后，现行 iOS 上架名为 "Talkie Lab"。
- [星野](https://www.xingyeai.com) — MiniMax（稀宇科技）旗下中文 AI 智能体社区（2023 年 9 月上线，仅移动端无网页聊天）：用户自建智能体的形象、声音、人设并分享到社区，主打沉浸剧情与情感陪伴。
- [筑梦岛](https://zhumengdao.com) — 阅文系（上海筑梦岛人工智能科技）AI 伴侣 App："梦中人"自定义人设、多角色群聊、小剧场情境对话；iOS/Android。

## 听书与 TTS

小说听书分两条线：商业阅读器（ElevenLabs、Speechify）按订阅或积分卖自然人声；开源侧，Apache 协议的 Kokoro-82M 模型让本地生成有声书变得可行——abogen、Audiblez、epub2tts 都能在自己电脑上把一本 EPUB 转成带章节、带字幕的有声书，边际成本为零。

- [abogen](https://github.com/denizsafak/abogen) — 开源（MIT）：EPUB/PDF/文本转音频并生成同步字幕，引擎为 Kokoro-82M；字幕粒度可在逐词到逐句之间自选。
- [Audiblez](https://github.com/santinic/audiblez) — 开源 CLI/GUI：用 Kokoro-82M 音色把 EPUB 转成分章节的有声书文件，本地 CPU/GPU 皆可跑。
- [ElevenLabs](https://elevenlabs.io) — 商业 TTS：语音克隆、按积分订阅计费；免费的 ElevenReader App 可朗读电子书和 PDF。
- [epub2tts](https://github.com/aedocw/epub2tts) — 开源 Python 管线：EPUB 转带章节的 M4B 有声书，引擎可选（Coqui XTTS、OpenAI TTS、微软 Edge 音色）。
- [Kokoro-82M](https://huggingface.co/hexgrad/Kokoro-82M) — Apache-2.0 开源权重 TTS 模型，8200 万参数，CPU 也能推理；是上面 abogen 与 Audiblez 的底层引擎。
- [Speechify](https://speechify.com) — 消费级 TTS 阅读器（移动 App + 浏览器扩展），读电子书和文档；免费 + 高级音色订阅。

## 本地部署与 BYOK 基建

"不订阅——用自己的 Key 或自己的显卡"背后的水电煤：本地跑开源权重模型的引擎与启动器（llama.cpp、KoboldCpp、Ollama、LM Studio、Jan）、面向裸文本补全的前端（Mikupad、text-generation-webui）、志愿算力网络（AI Horde），以及被众多 BYOK 写作工具列为首选接入的聚合层 OpenRouter。本清单里的大多数工具至少接其中一种。

- [AI Horde](https://aihorde.net) — 志愿者算力组成的分布式推理网络，免费使用（kudos 优先级机制）；KoboldAI Lite、SillyTavern、Agnai、Mikupad 都内置了它作为后端。
- [Jan](https://jan.ai) — 开源桌面应用：本地跑模型并内置 OpenAI 兼容服务端；Windows/macOS/Linux。
- [KoboldCpp](https://github.com/LostRuins/koboldcpp) — 面向写故事与角色扮演调优的 llama.cpp 单文件分发（AGPL-3.0）；自带 KoboldAI Lite UI，同时暴露 Kobold 与 OpenAI 兼容两套 API。
- [llama.cpp](https://github.com/ggml-org/llama.cpp) — MIT 协议的 C/C++ 推理引擎，绝大多数本地栈的地基；GGUF 模型格式的老家。
- [LM Studio](https://lmstudio.ai) — 免费但闭源的桌面 GUI：下载和运行 GGUF 模型，内置 OpenAI 兼容本地服务端。
- [Mikupad](https://github.com/lmg-anon/mikupad) — 单个 HTML 文件的 LLM 前端，围绕裸文本补全设计（token 概率、logit bias），适合写散文续写；可连 llama.cpp、KoboldCpp、AI Horde 和 OpenAI 兼容 API。
- [Ollama](https://ollama.com) — 开源本地模型运行器：一条命令拉模型，暴露 OpenAI 兼容 API；本清单多款写作工具的默认本地后端。
- [OpenRouter](https://openrouter.ai) — 一个 API、一把 Key 接几百个托管模型，按 token 计费；BYOK 派小说工具文档里出现频率最高的聚合层。
- [text-generation-webui](https://github.com/oobabooga/text-generation-webui) — 基于 Gradio 的本地 UI，支持多种模型加载器；其 notebook 补全模式被广泛用于写长文。

## 角色卡格式与工具

角色卡是嵌在 PNG 图片里的可移植 JSON：一张卡写好，SillyTavern、RisuAI、Agnai、Foreverse 都能直接跑。V2 规范是事实上的交换格式，V3/CharX 追加了资产打包与装饰器。下面是规范本体、一个浏览器编辑器和公开卡库——酒馆分类里的 Chub 同样是主要卡源。

- [AI Character Cards](https://aicharactercards.com) — 角色卡目录站，SFW/NSFW 分区，卡片 PNG 直链下载。
- [AI Character Editor](https://desune.moe/aichared/) — 浏览器端角色卡 PNG 编辑器，免安装免注册。
- [character-card-spec-v2](https://github.com/malfoyslastname/character-card-spec-v2) — Character Card V2 规范（PNG 内嵌 JSON），绝大多数前端实现的就是它；定义 `description`、`first_mes`、内嵌世界书等字段。
- [character-card-spec-v3](https://github.com/kwaroran/character-card-spec-v3) — V3/CharX 规范草案：在 V2 之上扩展资产、装饰器与 zip 容器格式；RisuAI 原生实现。
- [RisuRealm](https://realm.risuai.net) — RisuAI 的公开角色卡分享站，可独立于客户端在网页浏览。

## 评测基准

不靠体感比较"哪个模型写小说强"的几条路：带反 AI 味（slop）指标的评审型写作榜（EQ-Bench）、约束满足式的命题写作测试（lechmazur/writing），以及用真实小说构建的长上下文理解基准（Fiction.liveBench、NoCha）。长上下文这组尤其要紧——续写和角色扮演的成败，就压在模型真正"记得住"多少故事上。

- [EQ-Bench Creative Writing / Longform](https://eqbench.com/creative_writing_longform.html) — LLM 评审的长文写作榜：追踪 slop（AI 高频套话）、复读率和长文后段质量衰减；配套 slop 检测工具开源。
- [Fiction.liveBench](https://fiction.live/stories/Fiction-liveBench-Mar-25-2025/oQdzQvKHw8JyXbN87) — 用真实连载网文构建的长上下文理解基准：同一故事按不同上下文长度切档测试，定位模型在多长上下文开始"读不懂"；随新模型定期重发。
- [LLM Creative Story-Writing Benchmark](https://github.com/lechmazur/writing) — 命题写作：每个模型必须把 10 个指定要素（角色 / 物件 / 基调……）织进一篇短故事；由多个 LLM 评审对同题故事两两对比打分。
- [NoCha](https://novelchallenge.github.io/) — 基于 67 本新近出版长篇小说的论断核验基准（1,001 组真 / 假最小对）；刻意选新书，堵死模型靠训练数据背答案的路。

## 延伸资源

- [SillyTavern Docs](https://docs.sillytavern.app) — 官方文档，也是酒馆概念（世界书、宏、instruct 模板）最完整的公开参考。
- [r/SillyTavernAI](https://www.reddit.com/r/SillyTavernAI/) — 酒馆玩家社区；每周模型讨论楼是事实上的"角色扮演用哪个模型"追踪器。
- [r/LocalLLaMA](https://www.reddit.com/r/LocalLLaMA/) — 本地跑开源权重模型的主社区，含创意写作微调模型讨论。
- [sindresorhus/awesome](https://github.com/sindresorhus/awesome) — 本仓库遵循的 awesome 清单规范。

## 维护者说明

本清单的维护者同时在开发清单内的某款工具（Foreverse）。该条目与其它条目遵守完全相同的规则——字母序、不加粗、带可核验事实——竞品按各自实际能力如实收录。如果任何描述与产品实情不符，欢迎提 issue 或 PR。

## 许可

[CC0 1.0](LICENSE) — 公有领域，随意取用。
