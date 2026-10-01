# 句子卡模板 · Sentence Card Template

> 用GitHub学英语 · 第三步"建卡"配套模板。每句一卡，四段式。

```markdown
---
type: 句子卡 / Sentence Card
repo: <仓库名>
source: <文件 / 位置>
url: <链接，可溯源>
date: YYYY-MM-DD
tags: [句式, 生词, <领域>]
mastery: <1-5>
---

## 原句 · Original
<英文原句>

## 出处 · Source
<仓库名> · <文件> · <链接>

## 拆解 · Breakdown（≤3条）
1. 生词：<word> — <释义>
2. 短语：<phrase> — <释义>
3. 句式：<pattern> — <说明>

## 复用 · Reuse
<用同句式造的1句，用在自己的场景>
```

## 填卡规则

- 拆解不超过 3 条，只写你真正不会的；
- 复用句必须换场景，不抄原句改名词；
- 掌握度自评（5 级）：
  1. 秒懂 → 2. 知出处 → 3. 能复述 → 4. 换场景能用 → 5. 能教别人。

## 示例

```markdown
## 原句
A well-designed API is one that is easy to use and hard to misuse.

## 出处
example-utils · README.md · https://github.com/example/utils#readme

## 拆解
1. 句式：A well-designed X is one that is easy to A and hard to B（对比式定义）
2. 生词：misuse — 误用

## 复用
A well-designed onboarding flow is one that is easy to start and hard to give up.
```
