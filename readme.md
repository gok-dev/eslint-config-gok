# eslint-config-gok

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
