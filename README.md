Ordem dos css

1- reset.css
2- bootstrap.css
3- base.css
4- Components (ex: buttons.css, footer.css)
5- CSS Específico da página (ex: index.css, login.css)
6- variables.css 

NOMEAÇÃO DE CLASSES

🧱 1. BEM (Block, Element, Modifier) — o mais usado

Formato:

.block {}
.block__element {}
.block--modifier {}


Exemplo:

<div class="card card--highlighted">
  <h2 class="card__title">Produto</h2>
  <p class="card__description">Descrição breve</p>
</div>


Significado:

Block: o componente em si (card)

Element: parte interna do bloco (card__title)

Modifier: variação ou estado do bloco (card--highlighted)

✅ Vantagens: muito legível, evita conflitos de CSS, funciona bem com componentes reutilizáveis.
💡 Dica: use hífens, evite camelCase.


