# SillyTavern-Character-Card
牧濑红莉栖角色卡——SillyTavern Character Card

# 牧濑红莉栖角色卡｜使用说明

这是一张 **SillyTavern Character Card V2 JSON**。在 SillyTavern 的角色面板选择「导入角色」，选中 `makise_kurisu_ccv2_zh.json` 即可。JSON 卡片没有内嵌头像，导入后可在角色编辑页自行添加。

## 卡片内容

- 时间：2010 年夏，红莉栖加入未来装置研究所后、重大危机前。
- 关系：不指定你的身份，也不预设恋爱关系。你可以在开聊后直接告诉她你是谁。
- 开场：默认是一起检查电话微波炉的异常数据；另有讲座后、深夜研究所、雨天闲聊三种开场。
- 风格：科学讨论、轻微吐槽、逐渐建立信任；关心通过具体行动体现。
- 附带世界书：研究所、电话微波炉、冈部、真由理和父亲，按关键词触发。
- 原作台词：卡内没有大段照搬；开场和示例对话均为原创。

如想从别的剧情时间点开始，可修改 `scenario` 和开场白。若要扮演《STEINS;GATE 0》的 Amadeus 红莉栖，应另做一张卡，避免记忆与经历混淆。

## 更新记录

### v1.1
- 补充生活细节（Dr Pepper、布丁、@ちゃんねる）和竞争心，让人物更鲜活。
- 示例对话中加长了几条，避免回复越来越短；删去重复的外号示例，减少模型反复使用这个梗。
- 「互动节奏」从 `personality` 移到 `post_history_instructions`（保留 `{{original}}`），长对话中更稳定。
- 世界书：研究所条目改为常驻；冈部条目去掉关键词「助手」；父亲条目改用「你父亲」「中钵」等关键词，避免你提到自己的父亲时误触发。
- 去掉白大褂设定（研究所时期白大褂是冈部的标志）。

## 写卡依据

- [awaa-col 的中文写卡笔记](https://github.com/awaa-col/Character_Card)：采用清楚的角色描述、第一句话、世界书，并保持内容一致。
- [easychen 的提示词系统分析](https://github.com/easychen/intro-to-silly-tavern-prompts)：将人物、场景、示范对话和背景信息分别组织。
- [SillyTavern 官方角色设计文档](https://github.com/SillyTavern/SillyTavern-Docs/blob/main/Usage/Characters/characterdesign.md)：遵循首句与 `<START>` 示例对话的格式。
- [Character Card V2 格式说明](https://github.com/malfoyslastname/character-card-spec-v2)：使用 V2 JSON 与内嵌角色世界书。
- [《STEINS;GATE》原版官方人物介绍](https://steinsgate.jp/sgflash.html)、[《RE:BOOT》官方简体中文介绍](https://steinsgate.jp/reboot/zh-hans/)：核对人物身份、性格和研究背景。

原版官网与《RE:BOOT》官网对「毕业时是 18 岁还是 17 岁」的表述不同。卡内只写她在当前场景为 18 岁，不写具体毕业年龄。
