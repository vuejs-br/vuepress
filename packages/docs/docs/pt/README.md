---
home: true
heroImage: /hero.png
actionText: Iniciando →
actionLink: /guide/
footer: MIT Licensed | Copyright © 2018-present Evan You
---

<div style="text-align: center">
  <Bit/>
</div>

<div class="features">
  <div class="feature">
    <h2>Simplicidade Primeiro</h2>
    <p>A configuração mínima com a estrutura do projeto centralizada no _markdown_ ajuda você a se concentrar na escrita.</p>
  </div>
  <div class="feature">
    <h2>Baseado em Vue</h2>
    <p>Aproveite a experiência de desenvolver com Vue ) + webpack, use componentes Vue no _markdown_, e desenvolva temas personalizados com o Vue.</p>
  </div>
  <div class="feature">
    <h2>Performático</h2>
    <p>O VuePress gera HTML estático pré-renderizado para cada página e é executado como uma SPA assim que a página é carregada.</p>
  </div>
</div>

### Tão fácil como 1, 2, 3

``` bash
# instale
yarn global add vuepress
# OU npm install -g vuepress

# crie um arquivo de _markdown_
echo '# Hello VuePress' > README.md

# comece a escrever
vuepress dev

# gere os arquivos estáticos
vuepress build
```

::: aviso NOTA DE COMPATIBILIDADE
VuePress requer Node.js >= 8.6.
:::
