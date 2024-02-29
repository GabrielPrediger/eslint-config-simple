# Rocketseat ESLint config

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;

## Setup

### React (with Next.js)

Install dependencies:
```
npm i -D eslint @pred/eslint-config-simple
```
Inside `.eslintrc.json`
```
{
  "extends": [
    "@pred/eslint-config-simple/next", 
    "next/core-web-vitals"
  ]
}
```

### React (without Next.js)

Install dependencies:
```
npm i -D eslint @pred/eslint-config-simple
```
Inside `.eslintrc.json`
```
{
  "extends": "@pred/eslint-config-simple/react"
}
```

### Node.js

Install dependencies:
```
npm i -D eslint @pred/eslint-config-simple
```
Inside `.eslintrc.json`
```
{
  "extends": "@pred/eslint-config-simple/node"
}
```
