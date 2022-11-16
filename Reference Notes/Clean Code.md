2022-10-22 16:04
Status: #book 
Tags:

# Clean Code
Clean code é um livro muito conhecido e dispensa apresentações. O livro é dividido em 3 partes. 
 1. Apresentação do clean code.
 2. Capítulos com partes mais práticas onde você vai ver mais código (parte mais importante segundo o autor).
 3. Capitulo final com smell e heuristicas

## Capítulo 1
aqui o autor basicamente fala sobre a importância do clean code e fala a definição de clean code. 
A coisa mais importante que ele cita aqui é sobre **Não levar o livro como verdade absoluta**, não existe bala de prata, infelizmente.

## Capítulo 2: Nomes
Aqui o autor fala sobre a importância de se ter bons nomes, não vou ficar falando pq já tenho um artigo só sobre isso

[Meu artigo sobre nomes no dev.to](https://dev.to/marcusxavierr/clean-code-escolhendo-bons-nomes-feb)

## Capítulo 3:  Funcões
Bom, esse capitulo fala sobre a importância de escrever funções que sejam claras. Também tenho artigos sobre isso no dev.to 

[Bom uso das funções - parte 1](https://dev.to/marcusxavierr/clean-code-fazendo-bom-uso-das-funcoes-parte-1-375j)
[Bom uso das funções - parte 2](https://marcusxavier.dev/posts/clean-code-part3/)

## Capítulo 4: Comentários
Bom, eu achei esse capitulo bem óbvio. Talvez na época que o livro foi escrito (2008) fizesse sentido dizer para os programadores não escreverem comentários inuteis e que javadoc é perda de tempo (contém ironia)

## Capítulo 5: Formatação
{{Todo: escrever um artigo sobre formatação pra postar aqui. Aliás, vc pode ler o capitulo e postar as suas core ideas aqui}}

## Capítulo 6: Objetos e Estrutura de dados
Basicamente a ideia é que se usa Classes pra modelar tanto DTOs quanto classes de serviço no Java, então por isso é preciso ter uma separação clara entre o que só guarda dados, e o que opera em cima de dados.

## Capítulo 7: Error Handling
O TL;DR é: use exceções ao invés de retornar erros (Go chora). Não retorne nulo, estoure uma exceção (JS chora). Não passe nulo (python chora). 

Enfim, tente separar as duas preocupações (criar código de produção e fazer error handling) o maximo possivel. Isso diminui o mental overhead de precisar entender as duas coisas ao mesmo tempo.

## Capítulo 8: Boundaries
Aqui o titio bob fala pra você tentar isolar o maximo possível as suas dependências externas. Mas eu sinceramente acho que isso aí é uma parada meio utópica em pleno 2022. O véio não conhecia React

## Capítulo 9: Unit Tests
Bons testes tem uma boa legibilidade. Testes ruins mais atrapalham do que ajudam, pois eles tendem a ser bem mais difíceis de modificar à medida que o sistema evolui.

Abstrair as assertions dos seus testes **pode** ser uma boa ideia, mas é importante ter bom senso. Não misture conceitos diferentes no mesmo teste, se você está testando o caso de sucesso em um teste, é melhor criar um novo teste para testar o caso de exceção do que testar tudo no mesmo teste.

## Capítulo 10: Classes
2022-11-13 15:33
Status: #idea
Tags:

# Clean Code



---
# References



---
# References
O LIvro clean code
