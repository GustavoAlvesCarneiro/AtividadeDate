Script está no HTML - Funções e explicações:

Função maiorData() utiliza o operador ternário, realizando uma comparação entre as duas datas:
se data1 for maior que data2, a função retorna data1 como maior data,
senão, a função retorna data2 como maior data.

Função calcularIntervalo() compara se a data1 é maior do que a data2:
se a data1 for maior aparece um texto de erro na tela, pois a primeira data deve ser sempre menor que a segunda,
senão é calculado o intervalo: a diferença em milissegundos entre as duas datas é calculada subtraindo a data mais antiga pela mais nova,
Após isso utiliza-se uma expressão para transformar os milissegundos em dias.

Função dataAtualFormatada() retorna a data e hora atuais no formato hora:minuto - dia/mês/ano. 
A função toString() converte os valores de dia, mês, hora e minuto em strings e usa padStart(2, '0') 
para que cada valor tenha pelo menos dois caracteres. Se o valor tiver menos de dois caracteres, ele adiciona zeros à esquerda para preencher.

Função calcular() primeiro confere se as datas inseridas são válidas através da função isNaN:
se não forem é pedido para que seja inseridas datas válidas,
se forem válidas ele chama todas as funções e depois imprime na tela através do innerHTML os resultados.
