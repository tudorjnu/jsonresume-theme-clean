# Actual theme for JSON Resume

Minimalist and modern theme for [JSON Resume](https://jsonresume.org/) standard, designed for
the [v1.0.0 version](https://raw.githubusercontent.com/jsonresume/resume-schema/v1.0.0/schema.json).

- Only meaningful information
- Single color
- Single font-family
- Single page? Up to you!

This theme is based on the actual theme from [here](https://github.com/davcd/jsonresume-theme-actual).

## Prerequisites

- [node.js](https://nodejs.org/en/) runtime with [resume-cli](https://github.com/jsonresume/resume-cli/)

```bash
npm install -g resume-cli
```

## Develop

```bash
git clone git@github.com:tudorjnu/jsonresume-theme-clean.git
cd jsonresume-theme-actual

npm install

gulp
```

## Export

```bash
resume export -t . resume.pdf
```
