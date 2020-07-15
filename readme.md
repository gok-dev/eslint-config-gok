<!-- PROJECT SHIELDS -->

[![npm](https://img.shields.io/npm/v/eslint-config-gok.svg?label=npm%20package)](https://www.npmjs.com/package/eslint-config-gok)
[![npm](https://img.shields.io/npm/dt/eslint-config-gok.svg)](https://www.npmjs.com/package/eslint-config-gok)
[![GitHub issues](https://img.shields.io/github/issues-raw/gok-dev/eslint-config-gok.svg)](https://github.com/gok-dev/eslint-config-gok/issues)
[![GitHub last commit](https://img.shields.io/github/last-commit/gok-dev/eslint-config-gok.svg)](https://github.com/gok-dev/eslint-config-gok/commits/master)
[![NPM](https://img.shields.io/npm/l/eslint-config-gok.svg)](https://choosealicense.com/licenses/mit)

<h1 align="center">ESLint Config Gok</h1>

[ESLint Configuração Compartilhada](http://eslint.org/docs/developer-guide/shareable-configs) Para código JavaScript produzido pelo grupo de desenvolvedores da Gok, mais projetado para ser utilizável em toda a empresa. Ao adotar uma configuração do eslint comum, esperamos incentivar estilo e qualidade consistentes em todos os nossos repositórios.

## Modo de Usar

```sh
npm install --save-dev eslint-config-gok
```

Then, extend `gok` in your `.eslintrc`:

```json
{
  "extends": "gok"
}
```

## Nota Sobre a Dependência
*eslint-config-gok* tem *babel-eslint* e *eslint* como dependências porque se baseia em versões desses pacotes para suporte ao ES2015.
