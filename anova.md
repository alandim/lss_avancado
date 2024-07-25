# ANOVA (Análise de Variância)

## O que é ANOVA?
ANOVA (Analysis of Variance) é um conjunto de métodos estatísticos usados para comparar as médias de três ou mais grupos. Ele determina se há uma diferença estatisticamente significativa entre as médias dos grupos.

## Quando usar ANOVA?
- Quando se deseja comparar três ou mais grupos para verificar se pelo menos um deles difere significativamente dos outros.

## Como calcular ANOVA?
1. **Formulação das Hipóteses:**
   - H0 (Hipótese Nula): As médias dos grupos são iguais.
   - H1 (Hipótese Alternativa): Pelo menos uma média é diferente.

2. **Cálculo das Somas dos Quadrados:**
   - **Soma dos Quadrados Total (SST):** Mede a variabilidade total nos dados.
   - **Soma dos Quadrados entre Grupos (SSB):** Mede a variabilidade entre as médias dos grupos.
   - **Soma dos Quadrados dentro dos Grupos (SSW):** Mede a variabilidade dentro de cada grupo.

3. **Cálculo da Estatística F:**
   \[
   F = \frac{MSB}{MSW}
   \]
   Onde:
   - \( MSB \) = Média dos quadrados entre os grupos (SSB dividido pelos graus de liberdade entre os grupos).
   - \( MSW \) = Média dos quadrados dentro dos grupos (SSW dividido pelos graus de liberdade dentro dos grupos).

4. **Determinação do Valor Crítico e Comparação:**
   - Usar a tabela de distribuição F para encontrar o valor crítico.
   - Se o valor calculado de F for maior que o valor crítico, rejeita-se a hipótese nula.

## Exemplo Prático
Vamos supor que um restaurante quer comparar a média de satisfação dos clientes com três tipos de sobremesas: Sorvete, Torta e Frutas. As pontuações de satisfação são:

| Sorvete | Torta | Frutas |
|---------|-------|--------|
| 5       | 7     | 8      |
| 6       | 8     | 7      |
| 5       | 6     | 9      |
| 7       | 8     | 6      |
| 6       | 7     | 7      |

Calcular a média e variância de cada grupo, e então calcular F para determinar se há uma diferença significativa.

---

Este é um guia básico sobre ANOVA. Para aplicações mais complexas e interpretação detalhada dos resultados, recomenda-se consultar uma fonte especializada ou um estatístico.
