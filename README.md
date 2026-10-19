# DaoPath Taoist Metaphysics Trilingual Dataset (EN/ZH-Hans/ZH-Hant/AR)

The first open-source **English-Chinese Traditional-Chinese Arabic** four-language dataset for Chinese Taoist metaphysics, covering **I Ching (易经), BaZi (八字), Zi Wei Dou Shu (紫微斗数), and Taoist philosophy wiki**. **126 curated entries** with unique Arabic translations — no other public dataset provides this cross-cultural bridge between Chinese metaphysics and the Arab world.

## Files

| File | Entries | Description |
|---|---|---|
| `daopath-iching-hexagrams.trilingual.json` | 64 | I Ching 64 hexagrams with names, symbols, pinyin, judgments, and four-language titles/descriptions |
| `daopath-bazi-ten-gods.trilingual.json` | 10 | BaZi Ten Gods (十神) — Friend, Rob Wealth, Eating God, Hurting Officer, Direct/Indirect Wealth, Direct/Indirect Officer, Direct/Indirect Resource, Seven Killings |
| `daopath-ziwei-stars.trilingual.json` | 14 | Zi Wei Dou Shu major stars (紫微星, 天机星, 太阳星, etc.) with element, palace, personality traits |
| `daopath-wiki-articles.trilingual.json` | 38 | Curated Taoist philosophy wiki articles (What is BaZi? What is Chinese astrology? etc.) |

**Total: 126 entries × 4 languages (EN, ZH-Hans, ZH-Hant, AR) = 504 field translations**

## Schema

Each entry follows this structure:

```json
{
  "slug": "hexagram-1",
  "number": 1,
  "symbol": "䷀",
  "pinyin": "Qián",
  "cnName": "乾为天",
  "kingName": "The Creative",
  "title_en": "Hexagram 1: 乾为天 (The Creative) — I Ching Meaning & Reading",
  "title_zh": "第1卦 乾为天 The Creative — 易经卦义详解",
  "title_zh_hant": "第1卦 乾為天 The Creative — 易經卦義詳解",
  "title_ar": "السداسية الأولى: 乾为天 (الخلاّق) — معنى الإي تشينغ وقراءته",
  "category_en": "I Ching Hexagrams",
  "category_zh": "易经六十四卦",
  "category_zh_hant": "易經六十四卦",
  "category_ar": "خطوط الإي تشينغ",
  "description_en": "Hexagram 1 (Qián — The Creative): meaning, judgment and guidance for career, love, wealth and health...",
  "description_zh": "易经第1卦 乾为天（Qián · The Creative）详解：卦辞、寓意及事业、感情、财运、健康指引...",
  "description_zh_hant": "易經第1卦 乾為天（Qián · The Creative）詳解：卦辭、寓意及事業、感情、財運、健康指引...",
  "description_ar": "السداسية الأولى (تشيان 乾 — المبدع): المعنى والحكم والإرشاد في المهنة والحب والثروة والصحة..."
}
```

## Unique Features

### 1. Four-language coverage
- **English** — for Western researchers and general audience
- **Simplified Chinese** (简体) — for mainland China, Singapore
- **Traditional Chinese** (繁體) — for Taiwan, Hong Kong, Macau, overseas Chinese communities
- **Arabic** (العربية) — for 400M+ Arabic speakers in MENA region; **no other Taoist metaphysics dataset offers this**

### 2. Domain expertise
- All Arabic translations generated with **context-aware prompts** (specifying I Ching / BaZi / Zi Wei Dou Shu domain) using DeepSeek-V3
- Proper nouns preserved in original Chinese characters (e.g., 乾 = تشيان) with pinyin transliteration
- Formal Modern Standard Arabic (فصحى) register suitable for scholarly use

### 3. Cross-cultural bridge
- Connects Chinese metaphysical concepts (卦, 神, 星, 紫微) with Arab-Islamic scholarly tradition
- Useful for comparative religion, Silk Road studies, MENA metaphysical market analysis

## Use Cases

- **Machine translation training** — Arabic-Chinese-English parallel corpus for low-resource domain
- **Cross-cultural religious/philosophical research** — Taoism meets Islam
- **MENA metaphysical apps** — Arabic-language BaZi/I Ching calculators
- **Educational tools** — trilingual reference for Chinese metaphysics students
- **Digital humanities** — Silk Road knowledge exchange
- **Chatbots/LLMs** — domain-specific fine-tuning data

## Source & Methodology

- **Original data**: [DaoPaths.com](https://daopaths.com) — first trilingual Taoist metaphysics platform
- **Arabic translations**: DeepSeek-V3 with domain-aware prompting (formal MSA, preserved Chinese terms)
- **Quality control**: All 126 entries have consistent schema across 4 languages; Arabic spot-checked for accuracy
- **Update frequency**: Quarterly as new entries added to DaoPaths

## License

**CC0 1.0 Public Domain** — free for any use, commercial or non-commercial, no permission required. Attribution to DaoPaths appreciated but not required.

## Citation

```bibtex
@dataset{daopath_taoist_trilingual_2026,
  title={DaoPath Taoist Metaphysics Trilingual Dataset},
  author={DaoPaths},
  year={2026},
  publisher={Kaggle},
  url={https://github.com/HeTaobaba123/daopath-terms-dataset},
  note={126 entries, EN/ZH-Hans/ZH-Hant/AR, CC0 1.0}
}
```

## Related Datasets

- [TCM Arabic-Chinese Bilingual Dataset](https://github.com/HeTaobaba123/tcm-arabic-dataset-) — sister project for Traditional Chinese Medicine

## Contact

- Website: https://daopaths.com
- Issues: [GitHub Issues](https://github.com/HeTaobaba123/daopath-terms-dataset/issues)
