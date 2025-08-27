# HTML + CSS

###

Tem como objetivo de manter um setup básico para desenvolviento Front-End puro, com **Live Server**, **Estrutura**, e **Linting**.

###

**<h2>📁 Estrutura dos Diretórios</h2>**

###
```pgsql
html-css-template/
│
├── public/
│   └── index.html
│
├── src/
│   ├── styles/
│   │   └── main.css
│   └── scripts/
│       └── main.js
│
├── .editorconfig
├── .gitignore
├── README.md
└── package.json
```

###

**<h2>✅ Ferramentas Para Uso</h2>**

###

- `Live Server` ou `Vite` para hot reload;
- `Stylelint` para lintinga de CSS;
- `Prettier` para formatação.

###

**<h2>💡 Package.json com Live Server</h2>**

###
```json
{
  "name": "html-css-template",
  "scripts": {
    "dev": "live-server public"
  },
  "devDependencies": {
    "live-server": "^1.2.1"
  }
}
```


