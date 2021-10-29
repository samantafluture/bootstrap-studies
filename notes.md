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