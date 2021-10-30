# bootstrap

## container

- mais básico
- 2 tipos: largura fixa ou largura fluida

## mobile first

- faz primeiro pro celular e depois ajusta para outros dispositivos
- experiência tem que ser a mesma
- breakpoints
- no bootstrap, se não adicionar breakpoints, então está fazendo para celular

### breakpoints/media queries do bootstrap

- xs = até 576px 
- sm = a partir de 576px
- md = a partir de 768px
- lg = a partir de 992px
- xl = a partir de 1200px

-> xs é o padrão do bootstrap, logo os breakpoints/media queries começam no `sm`

## sistema de grids

- 12 colunas e 5 camadas
- linhas = `.row`
- colunas = `.col-4` ou o número de colunas (dentro de 12) que deverá pegar

-> todo `.container` tem um `.row` e todo `.row` tem um `.col`

- div container > div row > div col

-> usando apenas `.col` -> distribui por igual 

- quando coloco apenas `.col` sem especificar o valor da coluna (ex: `col-4`)
- o bootstrap usa o flex layout e divide o container em partes iguais
- de acordo com a quantidade de coluna que colocar
- exemplo: `.col` `.col-6` `.col` -> 6 colunas ao meio e 3 de cada lado
- pode até colocar valores quebrados

-> `.order` mudar a partir do breakpoint determinado
- exemplo `.order-sm-2` significa que a partir do breakpoint `sm`, esta coluna ficará em segundo lugar na ordem de colunas da `row` em questão

-> `.offset`
- pule um espaço vazio

## flex box

- dentro de um container
- `.d-flex`
- tudo o que estiver aí dentro terá alinhamento de display flex

## padding & margin

- p-1 a p-4 (de 0.25 a 1rem)
- m-1 a m4 (de 0.25 a 1rem)
- mx-auto = margin no eixo x -> 0 auto

## image

- `img-fluid` para ela ficar responsiva
- `img-thumbnail` para com uma borda
- `img-fluid rounded` para ela ficar responsiva e arredondada

## tables

- class `table` deixa a tabela responsiva
- usar ela dentro da tag `<table></table>`
- cores: `table-dark` ou `table-light` usando em tags table ou interiores à table
- `table-striped` fica uma cor escura e outra clara
- `table-hover` acende a linha onde o mouse está
- `table-bordered` coloca borda em tudo
- `table-borderless` tira todas as bordas

## alertas

- class `alert` pode ter também `alert-primary` ou `alert-danger` etc para mudar a cor

## buttons

- class `btn` e `btn-primary` (entre outros -danger etc) podem ser usadas com: `<a>` e `<input>` 
- outline = contorno (`outline-primary`)
- `btn-block` pega todo o espaço do container
- `active` mostra o visual do botão pressionado
- atributo html `disabled` deixa o visual desabilitado

## list-group

- div com `list-group` e internamente div (uma ou mais) com `list-group-item`
- refere-se à agrupamento de itens de conteúdo (não importa quais)
- `list-group-item-action` é para mostrar ação de clique (tem hover, tem cursor hand, etc)


