# Docking

Qual o objetivo do docking?

1. Virtual screening

2. Pose prediction

3. ~~Cálculo de energia~~ (não use o score do docking)

## Recomendações gerais

1. Proteínas com ligante são melhores que proteínas apo (sem ligante)

2. Quanto maior a semelhança entre a molécula a ser docada e o ligante da estrutura, maior a probabilidade de sucesso

3. A utilização de um ensemble de estruturas proteícas, de preferência com ligantes diversos, aumenta a qualidade dos resultados

4. Todas as estruturas do ensemble são utilizadas no docking, então selecione as estruturas mais relevantes (o surflex utiliza no máximo 50 estruturas por job, ele também permite fazer um clustering das estruturas de acordo com a conformação do sítio de ligação)

5. Após o docking, a otimização dos hidrogênios do receptor ou a otimização dos hidrogênios mais alguns átomos "pesados" da receptor, resultam em um valor de score mais preciso. Não há um consenso sobre qual método é melhor, o resultado varia para cada caso. (Ver artigo ?)
