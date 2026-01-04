# Contributing to Claude Slop Detector

Thanks for your interest in improving the slop detector! This project aims to help writers identify and fix AI-generated patterns in their content.

## Ways to Contribute

### Report New Patterns

Found an AI pattern not covered? Open an issue with:

1. **The pattern** - exact phrase or structural tell
2. **Examples** - before/after showing the pattern in context
3. **Tier suggestion** - which tier it belongs to (1, 2, or 3)
4. **Evidence** - research or frequency data if available

### Improve Detection

- Submit fixes for false positives
- Add edge cases the current detection misses
- Improve the fix recommendations

### Enhance Documentation

- Better examples
- Clearer explanations
- Additional use cases

## Submitting Changes

1. Fork the repository
2. Create a feature branch (`git checkout -b improve-detection`)
3. Make your changes to `skills/slop-detector/SKILL.md`
4. Test with sample content
5. Submit a pull request

## Guidelines

### Pattern Criteria

New patterns should:

- **Be specific** - not general writing advice, but identifiable AI tells
- **Have evidence** - either research backing or consistent observation
- **Include fixes** - not just "don't do this" but "do this instead"

### Tier Assignment

| Tier | Criteria |
|------|----------|
| 1 | Almost always indicates AI - immediate removal recommended |
| 2 | Suspicious when overused or clustered |
| 3 | Fine individually, problematic in groups |

### Writing Style

Keep contributions:

- Concise - no fluff
- Practical - actionable advice
- Evidence-based - cite sources where possible

## Questions?

Open an issue for discussion before major changes.
