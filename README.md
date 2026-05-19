# 🇨🇳 AI Chinese Naming Skills

This repository contains specialized AI skills for **Chinese Baby Naming**. These skills are designed for use with AI agents (like Hermes Agent or Claude Code) to assist users in selecting meaningful names based on classical literature or traditional astrology.

## 📦 Included Skills

### 1. 📚 中文典籍起名 (Chinese Classical Naming)
**Directory**: `chinese-naming/`

An interactive naming assistant based on classic Chinese literature (*Shijing*, *Chuci*, *Analects*, etc.).

*   **Massive Database**: Over **1,263+ names** collected from ancient texts.
*   **Interactive Guidance**: Guides users through gender, style (Classical, Poetic, etc.), and meaning preferences.
*   **Detailed Analysis**: Provides source text, original quote, meaning, and pronunciation analysis for every name.
*   **Best For**: Parents seeking cultural elegance and literary roots.

### 2. 🔮 生辰八字起名 (Bazi & Five Elements Naming)
**Directory**: `bazi-naming/`

A professional naming assistant based on traditional Bazi (Four Pillars of Destiny) and the Five Elements (Wu Xing).

*   **Automatic Analysis**: Computes the Bazi chart from birth date/time, determines the "Day Master" strength, and identifies beneficial elements (Xi Yong Shen).
*   **Zodiac Compatibility**: Checks against the 12 Zodiac animals' favorable and unfavorable radicals.
*   **Character Library**: Includes 1,000+ characters categorized by element.
*   **Best For**: Parents following traditional customs for luck, balance, and destiny.

## 🚀 How to Use

### For AI Agents
Place these folders into your agent's skills directory (e.g., `~/.hermes/skills/` or `.claude/skills/`).

### Manual Trigger
You can ask the AI:
- **For Classical Naming**: "帮我起个名字", "给宝宝取个有文化底蕴的名字"
- **For Bazi Naming**: "根据生辰八字起名", "看看宝宝五行缺什么，起个名字"

## 📋 Skill Structure

```
📂 skills
├── 📂 chinese-naming
│   ├── SKILL.md
│   └── 📂 references
│       └── name-database.md
└── 📂 bazi-naming
    ├── SKILL.md
    └── 📂 references
        └── bazi-knowledge.md
```
