# Web Starter Kit

A starter 💼 kit for any 🕸 web development project!

- Sass for CSS
- Use the latest JavaScript features
- Code linting w/ ESLint and Prettier

## Prerequisites

- VS Code
- Prettier and ESLint extension
- Modifications to VS Code settings

### settings.json

```json
// Prettier and ESLint setup
"editor.formatOnSave": true,
"prettier.eslintIntegration": true,
"[javascript]": {
  "editor.formatOnSave": false
},
"prettier.disableLanguages": ["js"],

// ESLint
"eslint.run": "onSave",
"eslint.autoFixOnSave": true,
"eslint.alwaysShowStatus": true
```

## Getting Started

Clone the repository into your project folder

```shell
git clone https://github.com/mattcroat/web-starter-kit.git .
```

## Installation

```
npm i
```

## Running the development server

```shell
npm run dev
```

## Deployment

```shell
npm run build
```
