# Markdown Translator Builder

```
git clone https://github.com/mrtcode/markdown-translator-builder.git
cd markdown-translator-builder
npm install
```

Edit translator and update `lastUpdated` in `src/translator.js` metadata.
```
npm test
npm run build
```

Copy `build/markdown.js` to [https://github.com/zotero/translators/markdown.js](https://github.com/zotero/translators/markdown.js).
