# Desafio de lógica DIO - Classificação de Nível de Herói

### Objetivo

Crie uma variável para armazenar o nome e a quantidade de experiência (XP) de um herói, depois utilize uma estrutura de decisão para apresentar alguma das mensagens abaixo:

Se XP for menor do que 1.000 = Ferro; <br>
Se XP for entre 1.001 e 2.000 = Bronze; <br>
Se XP for entre 2.001 e 5.000 = Prata; <br>
Se XP for entre 6.001 e 7.000 = Ouro; <br>
Se XP for entre 7.001 e 8.000 = Platina; <br>
Se XP for entre 8.001 e 9.000 = Ascendente; <br>
Se XP for entre 9.001 e 10.000= Imortal; <br>
Se XP for maior ou igual a 10.001 = Radiante;

### Saída

Ao final deve se exibir uma mensagem:
"O Herói de nome **{nome}** está no nível de **{nivel}**"

### Minha resolução

Para solucionar o desafio usei as estruturas condicionais "if, else if e else". <br>

Declarei duas variáveis uma com o nome do herói e outra com o seu nível. Onde cada condição verificaria a range de valores. Caso o nível do herói estivesse dentro da range de uma das condições, a condição exibiria uma mensagem com o nome do Herói e o seu nível de acordo com cada range de valor.
