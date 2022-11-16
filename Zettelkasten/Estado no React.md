2022-11-02 22:58
Status: #idea
Tags: [[React]], [[Javascript]]

# useState no React
### O react não atualiza os valores para você
Se vc tem um valor que precisa mudar na tela, então esse valor precisa de estado, pois, por padrão o react não vai redesenhar o componente na tela quando os dados mudam.

Bom, o useState me parece funcionar da seguinte forma:
1. Tu coloca um valor na func useState, e ela vai ter retornar esse valor em uma variavel e uma função para setar novos valores nessa variavel
2. Tu bota a sua variavel lá
3. Quando tu chamar o setValor ele vai disparar algo, e vai recarregar o componente

Eu achei isso mais trabalhoso que o vue, mas pelo menos, é algo explicito, e não uma bruxaria que executa sozinha e pode bugar.

Se vc vai atualizar um estado que depende do anterior (tipo um contador, por exemplo), vc precisa passar uma função anonima na hora do setState, que recebe o prev value e aí sim tu chama seu codigo. Isso evita o react te dar um estado desatualizado


### React tem mt estado, estado até demais
---
# References

