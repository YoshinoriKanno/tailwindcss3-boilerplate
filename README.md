# tailwindcss3-boilerplate

# Quick look

静的サイトを生成するときのテンプレートです。

# 要件

- node -v # v14.16.1
- "autoprefixer": "^10.4.2",
- "postcss": "^8.4.5",
- "postcss-cli": "^9.1.0",
- "sass": "^1.38.1",
- "tailwindcss": "^3.0.15"

# Hou to use

## インストール

```
npm install
```

## tailwindcss 実行、ウォッチ

```
npm run tailwindcss
```

tailwindcss については HTML, JS に記述した時点で autoprefixer 付きで CSS ファイルが生成される

##　 SASS ウォッチ

```
npm run sass
```

## autoprefixer

```
npm run postcss
```

SASS で生成された CSS について、autoprefixer を実行
