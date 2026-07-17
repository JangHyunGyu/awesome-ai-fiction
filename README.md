# Awesome AI Fiction [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A fact-checked map of tools for AI fiction: story continuation, novel-writing suites, tavern-style roleplay, AI companions, audiobook TTS, local-first stacks, character-card formats, and fiction benchmarks.

**What this is.** A curated list where every entry links the official site or repository and carries at least one verifiable fact (pricing model, platform, license, or core mechanism) — no marketing adjectives.

**Why it exists.** This space is fragmented across app stores, GitHub, Discord, and Chinese app markets, and products in it shut down quietly and often. General "AI tools" directories mix fiction tools with marketing-copy generators; this list only covers fiction.

**Maintenance.** Every link was manually checked on **2026-07-18**. Dead or discontinued services get a `status:` tag or are removed rather than silently kept (see [CONTRIBUTING.md](CONTRIBUTING.md)). Entries are alphabetical within each category; nothing is pinned or bolded.

中文版 → [README.zh.md](README.zh.md)

## Contents

- [Story Continuation & Interactive Fiction](#story-continuation--interactive-fiction)
- [Writing Suites for Authors](#writing-suites-for-authors)
- [Tavern Frontends & Roleplay Platforms](#tavern-frontends--roleplay-platforms)
- [AI Companions](#ai-companions)
- [Audiobooks & TTS](#audiobooks--tts)
- [Local-First & BYOK Infrastructure](#local-first--byok-infrastructure)
- [Character-Card Formats & Tooling](#character-card-formats--tooling)
- [Benchmarks & Evaluation](#benchmarks--evaluation)
- [Related Resources](#related-resources)

## Story Continuation & Interactive Fiction

These tools take a story that already exists — your draft, an imported novel, or a scenario — and generate what happens next, with the reader steering. The category spans text-adventure platforms (AI Dungeon), storytellers with in-house models (NovelAI, AI Novelist), and reader apps that keep every continuation as a comparable branch (Foreverse, StoryLord). China's 彩云小梦 has offered continuation-as-a-service since 2021.

- [AI Dungeon](https://aidungeon.com) — Text-adventure platform by Latitude, running since 2019; free tier plus subscriptions that unlock stronger models and longer memory; scenarios and multiplayer included.
- [AI Novelist (AIのべりすと)](https://ai-novel.com) — Japanese-language storyteller by Bit192, trained from scratch on a 2 TB+ corpus; usable free in the browser, premium tiers add larger models; generated content is free for commercial use per its terms.
- [Caiyun Xiaomeng (彩云小梦)](https://if.caiyunai.com) — Chinese continuation writer by Caiyun Tech (web + iOS/Android) with genre styles, world-entry settings, and character chat; free daily quota plus paid membership. Its international edition Dreamily was shut down on 2026-04-21.
- [Foreverse](https://foreverse.app) — Android reader that imports local TXT/EPUB novels and continues them from any selected passage; every AI continuation is kept as a branch beside the original text. BYOK across 60+ providers with keys stored on-device; also runs SillyTavern-format character cards (see [Roleplay](#tavern-frontends--roleplay-platforms)).
- [Friends & Fables](https://fables.gg) — Browser tabletop RPG with an AI game master ("Franz") running D&D 5e SRD rules, battlemaps, and persistent lore; free tier with credits for premium narration models; solo or parties up to six players.
- [NovelAI](https://novelai.net) — Subscription storyteller (free trial only) built on models trained in-house, with lorebook context management and anime-style image generation alongside text.
- [Perchance AI Story Generator](https://perchance.org/ai-story-generator) — Free, no-login story writer on the Perchance generator platform; generates paragraph by paragraph with user steering; community-built and ad-supported.
- [StoryLord](https://www.gennovel.app/en) — Web app that imports an existing novel (TXT/DOCX/Markdown) and continues or rewrites it in the original style; credit-based with 100 free credits on signup; supports 9 languages including Chinese.

## Writing Suites for Authors

Author-facing suites wrap an LLM in the scaffolding long-form fiction needs — story bibles, character codices, outline trees, foreshadowing trackers — so the model stops forgetting book-level facts. Sudowrite and NovelCrafter lead the English subscription camp; a distinct wave of Chinese tools (岱宗写作, 蛙趣拼文, 马良写作) targets million-character web novels; Novel Mage, LocalProse, and novelIDE sell offline-first, pay-once alternatives.

- [Biling AI Fiction (笔灵AI小说)](https://ibiling.cn/novel-workbench/) — Chinese web suite with 100+ fiction generators (outlines, settings, characters), a long-form editor, and a hit-novel deconstruction library; free to try, full features behind a membership.
- [Daizong Writing (岱宗写作)](https://www.daizongxiezuo.com) — Chinese long-form tool billed as a "Cursor for writers": story bible, rolling summaries, and a knowledge graph give the AI project-level memory; clients for Windows/macOS/Android/iOS; bundled default models with custom-model support.
- [Jieyou Bizha (解忧笔札AI)](https://xs.jieyoupu.com) — Chinese novelist assistant centered on foreshadowing management (unresolved-plot detection, payoff suggestions) plus character dossiers and plot-structure analysis; online membership, or a one-time offline edition (¥980) that runs local models via Ollama.
- [LocalProse](https://www.localprose.com/en/) — Desktop suite (Windows/macOS/Linux) that ships a bundled local model auto-sized to your RAM; one-time Pro lifetime license instead of a subscription; mobile companion app syncs over local Wi-Fi, no cloud.
- [Maliang Writing (马良写作)](https://maliangwriter.com) — Chinese web platform where seven specialized agents (supervisor, structure, chapter blueprint, generation, consistency check…) built on LangGraph draft chapters against a shared knowledge graph; free to register, billed in credits by model usage.
- [Novel Mage](https://novelmage.com) — Offline-first desktop app for Windows/macOS sold as a $99.99 one-time lifetime license; AI agent, character codex, and story planner run against local models (Ollama/LM Studio) or your own OpenAI/Anthropic/Google key.
- [NovelCrafter](https://www.novelcrafter.com) — Subscription writing workspace with bring-your-own-key model connections; its "codex" wiki (characters, places, lore) is injected into prompts automatically.
- [novelIDE](https://github.com/qq1375828505/novelIDE) — Open-source Android IDE-style app for Chinese web-novel writing: fully offline, an agent with 40+ tools plus sub-agents (outline, anti-water-content, de-AI-flavor), local proofreading, and EPUB export.
- [Sudowrite](https://www.sudowrite.com) — Subscription fiction-drafting tool with credit-metered generation; its Story Bible holds characters, outline, and style and drives chapter drafting.
- [Waqu Pinwen (蛙趣拼文)](https://waqupin.com) — Chinese desktop client (Windows/macOS) sold at ¥89/year or a lifetime buyout; connects any OpenAI-compatible API (DeepSeek, local Ollama…); tracks worldbuilding, characters, and foreshadowing, and generates outlines up to 1,000 chapters.

## Tavern Frontends & Roleplay Platforms

"Tavern-style" chat means persona-driven roleplay built on character cards, lorebooks/world info, swipes, and group chats. Two camps: self-hosted frontends where you bring your own model and API key (SillyTavern is the reference implementation; RisuAI and Agnai are open-source alternatives), and hosted platforms with community card libraries and in-house or proxied models (Character.AI, JanitorAI, Chub).

### Frontends (self-hosted / BYOK)

- [Agnai](https://agnai.chat) — Open-source multi-user roleplay platform usable hosted or self-hosted; supports AI Horde, OpenAI-compatible, NovelAI, and other backends; development active as of mid-2026.
- [Foreverse](https://foreverse.app) — Android client that imports SillyTavern-format character cards (chara_card_v3), lorebooks, regex scripts, and Quick Reply automations next to its novel reader; BYOK-first, no subscription required for the app itself.
- [KoboldAI Lite](https://lite.koboldai.net) — Zero-install web UI for story, adventure, and chat modes; connects to KoboldCpp, the volunteer AI Horde, and various cloud APIs.
- [RisuAI](https://risuai.net) — Open-source cross-platform client (web, desktop, mobile web); its author drafted the Character Card V3 spec, so CharX assets and V3 decorators work natively. [Source](https://github.com/kwaroran/RisuAI).
- [SillyTavern](https://sillytavern.app) — Self-hosted Node.js roleplay frontend, open-source under AGPL-3.0, connecting to most local and cloud LLM APIs; large extension ecosystem (vector storage, TTS, image gen). [Source](https://github.com/SillyTavern/SillyTavern).
- [TavernAI](https://tavernai.net) — The original "tavern" UI that SillyTavern forked from; rebuilt from scratch as TavernAI 2 in June 2026, now a portable Windows/Linux app with branching chat structure and a prompt manager. [Source](https://github.com/TavernAI/TavernAI).

### Hosted platforms

- [Chai](https://chai-research.com) — Mobile-first character chat app (iOS/Android) with user-created characters; freemium with subscription tiers.
- [Character.AI](https://character.ai) — Closed platform running proprietary in-house models; free tier plus a c.ai+ subscription; web and mobile apps.
- [Chub](https://chub.ai) — Community repository of user-made character cards with a public API that other frontends import from; browsing and card hosting are free, with optional subscriptions for its built-in Venus chat models.
- [JanitorAI](https://janitorai.com) — Hosted card platform with a free in-house model (JanitorLLM) and a documented proxy system for your own API key (OpenRouter, DeepSeek, etc.); optional Pro subscription.
- [PygmalionAI](https://pygmalion.chat) — Self-funded open project: free hosted chat plus open-weight roleplay models (Pygmalion-3 12B, Eleusis-12B, Apache-2.0) released on Hugging Face.
- [SpicyChat](https://spicychat.ai) — Hosted roleplay platform with user-created characters; free tier plus subscriptions that remove queues; adult content allowed behind age verification.

## AI Companions

Companion apps optimize for a persistent relationship rather than one-off scenes: long-term memory, proactive messages, voice calls, selfies, and affection systems. Replika (2017) defined the category; Kindroid and Nomi compete on memory depth in the West; in China, MiniMax's 星野 (Talkie internationally), ByteDance's 猫箱, and Yuewen-backed 筑梦岛 occupy the same niche with card-collecting monetization.

- [Kindroid](https://kindroid.ai) — Companion app (web/iOS/Android) with persistent memory, voice calls, and AI selfies; subscription-based.
- [Maoxiang (猫箱)](https://maoxiangai.com) — ByteDance's Chinese roleplay/companion app built on its Doubao models; iOS/Android; free with a membership subscription that adds a smarter mode and longer voice calls.
- [Nomi](https://nomi.ai) — Companion app whose marketed focus is long-term memory and group chats; free tier plus subscription.
- [Replika](https://replika.com) — Launched in 2017, one of the earliest mainstream AI companions; avatar-based, freemium with a Pro subscription.
- [Talkie](https://www.talkie-ai.com) — International edition of MiniMax's Xingye; free to use, monetized through a Talkie+ subscription and collectible "Soul Cards"; the iOS listing is titled "Talkie Lab", and the web version stays available during app-store removals.
- [Xingye (星野)](https://www.xingyeai.com) — MiniMax's Chinese companion/roleplay community app (mobile-only, no web chat); users create and share agents with custom persona, voice, and appearance.
- [Zhumengdao (筑梦岛)](https://zhumengdao.com) — Chinese companion app from the Yuewen (阅文) ecosystem; custom "dream companion" characters, multi-character group chats, and scenario "small theater" play; iOS/Android plus a WeChat mini-program.

## Audiobooks & TTS

Fiction listening splits into commercial reader apps and open-source pipelines. ElevenLabs and Speechify sell natural voices by subscription or credits; on the open side, the Apache-licensed Kokoro-82M model made local audiobook generation practical, and abogen, Audiblez, and epub2tts turn an EPUB into a narrated audiobook — with chapters and subtitles — on your own machine at zero marginal cost.

- [abogen](https://github.com/denizsafak/abogen) — Open-source (MIT) converter from EPUB/PDF/text to audio with synchronized subtitles, built on Kokoro-82M; word-level captions for English, sentence-level for other languages.
- [Audiblez](https://github.com/santinic/audiblez) — Open-source CLI/GUI that converts EPUBs into chaptered audiobook files using Kokoro-82M voices; runs locally on CPU or GPU.
- [ElevenLabs](https://elevenlabs.io) — Commercial TTS with voice cloning, priced by credit-based subscriptions; its free ElevenReader app reads ebooks and PDFs aloud.
- [epub2tts](https://github.com/aedocw/epub2tts) — Open-source Python pipeline that narrates EPUBs into chaptered M4B audiobooks with a choice of engines (Coqui XTTS, OpenAI TTS, MS Edge voices).
- [Kokoro-82M](https://huggingface.co/hexgrad/Kokoro-82M) — Apache-2.0 open-weight TTS model with 82M parameters; small enough for CPU inference; the engine behind abogen and Audiblez above.
- [Speechify](https://speechify.com) — Consumer TTS reader (mobile apps plus browser extension) for ebooks and documents; freemium with premium voices.

## Local-First & BYOK Infrastructure

The plumbing behind "no subscription — your key or your GPU": engines and runners that execute open-weight models locally (llama.cpp, KoboldCpp, Ollama, LM Studio, Jan), frontends built for raw text completion (Mikupad, text-generation-webui), a volunteer compute network (AI Horde), and OpenRouter as the one-key aggregator many BYOK writing tools document first. Most tools elsewhere in this list connect to at least one of these.

- [AI Horde](https://aihorde.net) — Volunteer-run distributed inference network, free to use with a priority ("kudos") system; available as a backend in KoboldAI Lite, SillyTavern, Agnai, and Mikupad.
- [Jan](https://jan.ai) — Open-source desktop app for running local models with a built-in OpenAI-compatible server; Windows/macOS/Linux.
- [KoboldCpp](https://github.com/LostRuins/koboldcpp) — Single-binary llama.cpp fork tuned for storywriting and roleplay (AGPL-3.0); bundles the KoboldAI Lite UI and exposes both Kobold and OpenAI-compatible APIs.
- [llama.cpp](https://github.com/ggml-org/llama.cpp) — MIT-licensed C/C++ inference engine that most local stacks build on; home of the GGUF model format.
- [LM Studio](https://lmstudio.ai) — Free proprietary desktop GUI for downloading and running GGUF models, with a built-in OpenAI-compatible local server.
- [Mikupad](https://github.com/lmg-anon/mikupad) — LLM frontend in a single HTML file, oriented around raw text completion for prose (token probabilities, logit bias); connects to llama.cpp, KoboldCpp, AI Horde, and OpenAI-compatible APIs.
- [Ollama](https://ollama.com) — Open-source local model runner with one-command model pulls and an OpenAI-compatible API; the local backend many writing tools in this list target.
- [OpenRouter](https://openrouter.ai) — One API and one key across hundreds of hosted models, pay-per-token; the aggregator most BYOK-friendly fiction tools document first.
- [text-generation-webui](https://github.com/oobabooga/text-generation-webui) — Gradio-based local UI supporting multiple model loaders; its notebook-style completion mode is widely used for prose.

## Character-Card Formats & Tooling

Character cards are portable JSON payloads embedded in PNG files, so a persona authored once runs in SillyTavern, RisuAI, Agnai, Foreverse, and others. The V2 spec is the de-facto interchange format; V3/CharX adds assets and decorators. Below are the specs themselves, a browser editor, and public card directories — Chub (listed under Roleplay) is also a major card source.

- [AI Character Cards](https://aicharactercards.com) — Directory of downloadable character cards with SFW/NSFW filtering and direct PNG downloads.
- [AI Character Editor](https://desune.moe/aichared/) — Browser-based editor for creating and editing character-card PNGs; no install or account required.
- [character-card-spec-v2](https://github.com/malfoyslastname/character-card-spec-v2) — The Character Card V2 specification (JSON embedded in PNG) that most frontends implement; defines fields like `description`, `first_mes`, and embedded character books.
- [character-card-spec-v3](https://github.com/kwaroran/character-card-spec-v3) — The V3/CharX draft specification extending V2 with assets, decorators, and a zip container format; implemented natively by RisuAI.
- [RisuRealm](https://realm.risuai.net) — RisuAI's public hub for sharing character cards, browsable standalone on the web.

## Benchmarks & Evaluation

How to compare models for fiction without trusting vibes: judge-scored writing benchmarks with anti-slop metrics (EQ-Bench), constraint-satisfaction story tests (lechmazur/writing), and long-context comprehension built from real novels (Fiction.liveBench, NoCha). The long-context ones matter because continuation and roleplay live or die on how much story the model actually holds.

- [EQ-Bench Creative Writing / Longform](https://eqbench.com/creative_writing_longform.html) — LLM-judged longform writing leaderboard tracking slop (over-used "GPT-isms"), repetition, and quality degradation across a long piece; the slop-scoring tool is open source.
- [Fiction.liveBench](https://fiction.live/stories/Fiction-liveBench-Mar-25-2025/oQdzQvKHw8JyXbN87) — Long-context comprehension benchmark built from real serialized web fiction; tests the same story at increasing context lengths and is re-published periodically with new frontier models.
- [LLM Creative Story-Writing Benchmark](https://github.com/lechmazur/writing) — Each model must weave 10 assigned elements (character, object, tone…) into a short story; scored by head-to-head comparisons across a panel of LLM judges, with position-bias correction.
- [NoCha](https://novelchallenge.github.io/) — Claim-verification benchmark over 67 recently published full-length novels (1,001 true/false minimal pairs); recent books are used deliberately so models cannot rely on training-data memory.

## Related Resources

- [SillyTavern Docs](https://docs.sillytavern.app) — Official documentation; also the most complete public reference for tavern concepts (world info, macros, instruct templates).
- [r/SillyTavernAI](https://www.reddit.com/r/SillyTavernAI/) — Community hub for tavern-style roleplay; weekly model discussion megathreads double as a practical "which model for RP" tracker.
- [r/LocalLLaMA](https://www.reddit.com/r/LocalLLaMA/) — The main community for running open-weight models locally, including creative-writing finetune discussion.
- [sindresorhus/awesome](https://github.com/sindresorhus/awesome) — The awesome-list conventions this repository follows.

## Maintainer note

This list is maintained by people who also build one of the listed tools (Foreverse). It is included under exactly the same rules as every other entry — alphabetical order, no bolding, one verifiable fact — and competing tools are listed on their merits. If any description misrepresents a product, please open an issue or PR.

## License

[CC0 1.0](LICENSE) — public domain. Copy anything.
