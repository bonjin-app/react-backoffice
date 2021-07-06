# React BackOffice

### GitHub Pages
```bash
npm install --save gh-pages
```

package.json
```js 
"scripts: {
    "predeploy": "npm run build",
    "deploy": "gh-pages -d build"
}
```

```bash
npm run deploy
```