# SQL-Mine-BD

## 1 - Cenário

### Descrição do Cenário

 Em uma vila de um mundo quadrado, Steve tinha acabado de voltar de uma aventura com sua amiga Alex. Eles haviam coletado muitos materiais e encontrado diversas criaturas. Porem no meio dessa aventura eles acabaram perdendo muito tempo procurando itens e criaturas que eles já haviam encontrado de novo por não lembrar mais onde encontrar tais itens. Então eles decidiram criar um sistema de banco de dados para facilitar as próximas aventuras. Nesse sistema eles planejam cadastrar todos os itens e materiais encontrados e todas as criaturas e bosses encontrados, falando sempre o que cada criatura poderia derrubar ao ser abatida.

O que Stive planeja cadastrar será organizado da seguinte forma:

 Itens: contendo um id para cada, nome deles, durabilidade (se tiver), o tempo de uso, o quanto o itens está gasto e a raridade do item

Já os Mobs serão dividos em três categorias sendo elas Mobs Passivos, Mobs Hostis e Mobs Neutros contento os seguintes campos:

 Mobs: contendo um id para cada, o nome deles, o bioma de geração deles e o que esse mob dropa

também será cadastrado Biomas e as combinações de drops de cada mob da seguinte maneira:

 Biomas: contendo um id para cada e o nome do bioma
 Drop dos Mobs: contendo um id para cada combinação de itens que foram dropados e 3 campos para cadastrar até 3 itens que podem ser dropados pelo mob

E por fim será cadastrado também uma tabela para os Boos do jogo de maneira parecida com a dos Mobs:

 Boss: contendo um id para cada, o nome deles, tipo para identificar se é ou não o boss final e em qual bioma se encontra esse bos
 
 ## 2 - Modelagem Conceitual
