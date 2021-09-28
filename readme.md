# Exercício JavaScript - Calculadora Flex

## Objetivo

aplicar os conceitos de programação usando a linguagem JavaScript para construir uma aplicação que diga quando é melhor abastecer com Álcool ou Gasolina, dados os valores dos combustíveis de um posto.

## Cálculo

pesquisas apontam que só vale a pena abastecer com Álcool se o valor do litro dele for de no máximo 70% do valor da Gasolina, pois os carros consomem 30% mais combustível no Álcool.

## Interface

a construção da interface deve levar em conta:
- uma imagem que vai mostrar o resultado do cálculo e indicar a melhor alternativa.
- um campo para inserir o valor do litro do Álcool.
- um campo para inserir o valor do litro da Gasolina.
- um botão para executar o cálculo.

## Passo a passo

1. construir a interface considerando todos os elementos citados acima.
2. a imagem, deve exibir no início por padrão a imagem do resultado neutro (imagem 1).
3. o botão deve executar uma função JavaScript que vai realizar o cálculo.
4. nessa função, os textos dos campos devem ser convertidos para número através da função `parseFloat` da classe `Number` ([Documentação](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Number/parseFloat)) que é nativa do JavaScript.
5. tendo os valores armazenados em variáveis, basta realizar o calculo de comparação dos 70% do Álcool com a gasolina.
6. deverá ter uma variável que armazenará o valor que indicará qual o melhor combustível (podendo ser `0` ou `1`, `true` ou `false`).
7. por final, de acordo com o resultado do calculo na variável, deverá alterar o DOM, e mudar a imagem de neutra (imagem 1) para Álcool (imagem 2) ou Gasolina (imagem 3).

## Recursos de imagens

utilize as imagens disponibilizadas neste repositório (diretório `img`) para construir sua aplicação.

## Entrega

as entregas devem ser feitas através do google classroom. na resposta deve conter um link para um repositório git público para a análise do desenvolvimento e para que seja feita a devolutiva com observações (caso necessário).

*atenção!! devem fazer a entrega desse exercício todos os alunos para que o professor possa avaliar o andamento da turma.*