# CursorRules

Project rules structure for Cursor AI. Visit our [landing page](https://blodyle.github.io/cursorrules) for a detailed guide.

## Quick Start

1. Create the rules directory structure:
```bash
mkdir -p .cursor/rules/
```

2. Add the required files:
```
.cursor/rules/
├── overview.mdc     # Project overview and architecture
├── tech-stack.mdc   # Technologies and dependencies
├── design-rules.mdc # UI/UX and styling standards
├── areas.mdc        # Features and components
└── development-guidelines.mdc # Code standards
```

3. Configure file-specific rules using globs:
```yaml
---
description: React component guidelines
globs: 
  - src/components/**/*.tsx
  - src/components/**/*.jsx
---

## Component Rules
- Use functional components
- Follow project naming conventions
- Implement proper prop types
```

## Examples

Check the `examples/` directory for complete rule setups:
- [Water Tracker](examples/water-tracker/.cursor/rules/)
- [Todo App](examples/todo-app/.cursor/rules/)
- [Recipe Finder](examples/recipe-finder/.cursor/rules/)

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-rules`)
3. Commit your changes (`git commit -m 'Add some amazing rules'`)
4. Push to the branch (`git push origin feature/amazing-rules`)
5. Open a Pull Request

## License

MIT
