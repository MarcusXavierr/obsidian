2022-10-22 15:45
Status: #tool
Tags:

# Comandos que aprendi no vim

### Comandos
Aqui eu vou colocar os comandos que eu for aprendendo no vim. A estrutura vai ser o titulo (talvez em negrito) com o comando e embaixo coloco um pequena descrição do que o comando faz.

### Insights
O "c" basicamente funciona como o comando "d" com a diferença de que além de deletar ele entra em insert mode (isso vale pro shift-C também)

#### D
  Deleta o resto da linha (a partir de onde está o cursor)

#### C
Deleta o resto da linha (a partir de onde está o cursor) e entra em insert mode

#### S ====
  Deleta a linha inteira e entra em insert mode

#### c? ====
Funciona igual o "d", mas além de deletar te coloca no insert mode

#### Comandos com "i" no meio: diw, yi(, etc ====
Bom, esses comandos são extrememente uteis pra aplicar o comando anterior "d", "y", etc, nos arredores do cursor, ao inves de ir até o começo de uma palavra pra copiar ela, vc pode simplesmente usar o "i" no meio de "yw" ("yiw") e copiar a palavra que *cerca* o cursor.

#### Comandos com "a" no meio: da{, ya(, etc ====
Esse comando é quase igual ao anterior. A diferença é que ele aplica não só ao que está dentro dos colchetes ou chaves, mas tmb copia o colchete, chave ou aspa que cerca a coisa que está no cursor

#### CTRL-D | CTRL-U ====
Esses dois comandos acima servem pra vc ir meia página pra baixo *Down* e pra ir pra meia página pra cima *Up*. Esses comandos eu preciso criar o hábito de usar mais. Parece ser bem mais eficiente do que apertar j ou k e segurar a tecla pra caminhar

#### % ====
Esse é bem util pra pular pro outro parentese ( ou outra chave { que vc está. Se eu apertar % em cima de uma chave no começo de uma função, eu vou pular logo pro final dessa função onde está a outra chave

#### Números nos comandos ====
Também é possivel colocar numeros nos comandos. Por exemplo, pra apagar dois niveis que estão entre chaves, basta digitar "d2i{" que ele vai apagar o nivel atual dentro de chaves, logo vai apagar o proximo

#### Telescope resume (space fr) ====
Esse é um map que eu fiz pro comando telescope resume que continua a sua ultima busca de onde parou

### Comandos com G ===
#### gj / gk ====
Quando um linha é muito comprida e ocupa duas ou mais linhas visualmente no vim, é possivel usar os comandos acima para navegar pra cima e pra baixo por essa linha como se fosse multiplas linhas

#### g0 / g$ ====
Funciona da mesma forma que o comando anterior, mas dessa vez para navegação horizontal

#### gu? / gU? ====
Esse comando é usado para capitalização de um trecho de texto selecionado (pode ser uma letra, uma palavra, dentro de parenteses e etc).

#### ~ / g~? ====
Funciona como o comando anterior, mas agora ele só troca a capitalização da letra ou palavra (se usar g~)

#### gv ====
Você pode voltar pro ultimo texto selecionado no modo visual (também vale para texto que foi alterado com o ysi??) e irá reselecionar para você

#### g& ====
Aplica a ultima substituição no arquivo inteiro. Util pra fazer uma unica substituição e caso tenha dado certo só apertar esse comando para aplicar no resto do arquivo


---
# References

