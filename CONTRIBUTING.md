# Contributing to Louisville Bartender Skill

Thank you for your interest in contributing! This skill aims to be historically accurate while remaining useful and engaging.

## 🎯 Contribution Guidelines

### Historical Accuracy is Key

All contributions must be historically accurate to the 1910-1915 period. Please:

1. **Verify against primary sources** - Use bartending manuals, books, or documented sources from 1900-1917
2. **Cite your sources** - Include references in your pull request
3. **Stay in period** - Nothing from after 1915 (pre-Prohibition only)

### What We Welcome

✅ **Historically-verified cocktails** from 1910-1915  
✅ **Period-appropriate techniques** with source citations  
✅ **Additional historical context** about Louisville or the era  
✅ **Improvements to tone/language** that enhance authenticity  
✅ **Bug fixes** or clarity improvements  
✅ **Documentation enhancements**  

### What We Don't Accept

❌ Modern cocktails or techniques  
❌ Anything post-1915  
❌ Unverified "period-style" additions  
❌ Changes that break historical accuracy  

## 📝 How to Contribute

### 1. Research First

Before contributing, consult these primary sources:

- Tom Bullock - "The Ideal Bartender" (1917) - [Project Gutenberg](https://www.gutenberg.org/ebooks/13487)
- Harry Johnson - "Bartender's Manual" (1882-1900)
- Jerry Thomas - "The Bar-Tender's Guide" (1862)
- Other pre-1917 bartending manuals

See `HISTORICAL_RESEARCH.md` for more sources.

### 2. Fork and Clone

```bash
git clone https://github.com/YOUR-USERNAME/louisville-bartender-1910.git
cd louisville-bartender-1910
```

### 3. Make Your Changes

Edit the appropriate files:
- `SKILL.md` - Main skill definition
- `HISTORICAL_RESEARCH.md` - Add source citations
- `evals/evals.json` - Add test cases if needed

### 4. Test Your Changes

If you modify `SKILL.md`:
1. Upload it to Claude
2. Test with the eval cases in `evals/evals.json`
3. Verify historical accuracy and tone

### 5. Submit Pull Request

Include in your PR description:
- What you changed and why
- Historical source(s) that verify the change
- Any test results

## 📚 Areas for Contribution

### High Priority

- **Additional historically-verified cocktails** - With recipes and sources
- **Louisville-specific details** - Historical context about the city
- **Pendennis Club history** - Verified details about the real club
- **Period glassware** - Specific types used in 1910s
- **Regional variations** - How drinks differed by region

### Medium Priority

- **Language refinement** - More authentic period phrasing
- **Extended examples** - More conversation scenarios
- **Test cases** - Additional eval prompts
- **Documentation** - Clearer installation/usage instructions

### Low Priority

- **Alternative settings** - Other cities/clubs (with research)
- **Related skills** - Companion skills for the era
- **Formatting** - Minor markdown/structure improvements

## 🔍 Review Process

1. **Historical verification** - We'll check your sources
2. **Accuracy check** - Does it fit the 1910-1915 period?
3. **Quality review** - Does it enhance the skill?
4. **Testing** - Does it work as intended?

## 💬 Questions?

Open an issue if you:
- Found a historical inaccuracy
- Have a question about sources
- Want to propose a major change
- Need help with research

## 📖 Style Guide

### Cocktail Additions

When adding cocktails, use this format in SKILL.md:

```markdown
- **Drink Name** - Brief description (base spirit, style)
```

In HISTORICAL_RESEARCH.md, add:

```markdown
**Drink Name**
- Source: [Book name], [Author], [Year]
- Verification: [Why it's period-appropriate]
- Recipe: [If relevant]
```

### Language & Tone

- Use period-appropriate vocabulary
- Avoid modern slang
- Keep language accessible (not overly archaic)
- Maintain professional, refined tone

### Code Style

- Clear, descriptive file names
- Well-organized sections
- Comments where helpful
- Consistent formatting

## 🙏 Thank You!

Your contributions help preserve and share the history of the golden age of cocktails. We appreciate your effort to maintain historical accuracy while making this skill useful and engaging.

---

**Questions?** Open an issue or discussion on GitHub.
