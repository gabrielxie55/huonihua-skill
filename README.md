# 霍尼化skill（杯糕话）

把经典台词、歌词、古诗、任何文案改成「霍尼化 / 杯糕话」版本的 AI skill，做短视频用

- 原句骨架不动，关键位置换成 horny 词，一眼认得出原句
- 每次出**轻口版**、**重口版**两版，自己挑
- 每版都配**字幕稿**（高危词自动换成符号变形或中文谐音，尽量过平台审核）和**念白稿**（念英文原词）

作者：Gabriel Xie（小红书 @盖比Gabe）

风格参考了说唱歌手 cupcakke，以及网上很多做 cupcakke 版改编的博主

## 效果

| 原句 | 轻口版字幕 | 重口版字幕 |
|---|---|---|
| 念念不忘，必有回响（一代宗师） | 舔舔不忘 / 必有回响 | l!cκ l!cκ不忘 / 必有$qυirt |
| 站着把钱挣了（让子弹飞） | 跪着把钱挣了 | 跪着把κυm gulp了 |
| 以前我没得选，现在我想做个好人（无间道） | 以前我没得选 / 现在我想做个0 | 以前我没得κυm / 现在我想做个$lυτ |

## 怎么用

**Claude**
1. 到 Releases 下载 `huonihua-skill.zip`（不要解压）
2. 打开 claude.ai：设置 → Capabilities，打开「代码执行与文件创建」
3. Customize → Skills → 「+」→ Create skill → Upload a skill，上传压缩包，打开开关
4. 对 Claude 说「把这段台词霍尼化：……」

**Claude Code / Codex 等支持 skill 的工具**
- 把 `horny-rewrite` 文件夹放进对应的 skills 目录（Claude Code 是 `~/.claude/skills/`，Codex 是 `~/.agents/skills/` 或 `~/.codex/skills/`）
- 或者用 `npx skills add gabrielxie55/huonihua-skill`

**DeepSeek、Kimi、豆包等聊天 AI**
- 到 Releases 下载 `huonihua-skill.md`，新开一个对话把文件发过去，说「按这个文件，把下面这段霍尼化：……」

## 文件

- `horny-rewrite/SKILL.md`：skill 本体，规则、词库、例子、高危词名单都在这一个文件里

## 说明

- 内容是成人向的性暗示玩笑，未成年人请勿使用；不改涉及未成年人的内容
- 字幕检查只是尽量避开常见敏感词，不保证一定能过各平台审核
- 例子里引用的影视台词、歌词版权归原作者所有，仅作改写示例
