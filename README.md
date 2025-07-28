# Advanced Reading Textbook Documentation

This is a VuePress documentation site for the "Advanced Reading" textbook, containing 12 units with 2 articles each.

## Features

- Bilingual content (English and Chinese)
- Audio support for pronunciation practice
- Detailed grammatical analysis
- Cross-cultural insights

## Technical Stack

- [VuePress](https://vuepress.vuejs.org/) - Static site generator
- [Plume Theme](https://theme-plume.vuejs.press/) - Modern documentation theme

## Project Structure

```
docs/
├── unit1/
│   ├── Unit1-T1.md
│   └── Unit1-T2.md
├── unit2/
│   ├── Unit2-T1.md
│   └── Unit2-T2.md
├── ...
├── unit12/
│   ├── Unit12-T1.md
│   └── Unit12-T2.md
└── index.md
```

## Development

```bash
# Install dependencies
npm install

# Start development server
npm run docs:dev

# Build for production
npm run docs:build
```

## Deployment

This site is designed to be deployed via Cloudflare Pages with automatic deployment from GitHub.

## GitHub Repository

- Development: https://github.com/idkbungle/advanced-reading-dev-1
- Production: https://github.com/idkbungle/advanced-reading

## License

MIT