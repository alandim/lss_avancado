# Teste Qui-Quadrado e ANOVA

## Teste Qui-Quadrado

### O que é o Teste Qui-Quadrado?
O teste Qui-Quadrado (χ²) é um teste estatístico usado para determinar se há uma diferença significativa entre as frequências observadas e as frequências esperadas em uma ou mais categorias.

### Quando usar o Teste Qui-Quadrado?
- Para testar a independência entre duas variáveis categóricas (teste de independência).
- Para testar a adequação de um modelo de distribuição (teste de bondade de ajuste).

### Como calcular o Teste Qui-Quadrado?
1. **Formulação das Hipóteses:**
   - H0 (Hipótese Nula): Não há diferença significativa entre as frequências observadas e esperadas.
   - H1 (Hipótese Alternativa): Existe uma diferença significativa entre as frequências observadas e esperadas.

2. **Cálculo da Estatística do Teste:**
   \[
   χ² = \sum \frac{(O_i - E_i)^2}{E_i}
   \]
   Onde:
   - \( O_i \) = Frequência observada
   - \( E_i \) = Frequência esperada

3. **Determinação do Valor Crítico:**
   - Usar a tabela de distribuição Qui-Quadrado com \( n-1 \) graus de liberdade (onde \( n \) é o número de categorias).

4. **Comparação e Decisão:**
   - Comparar o valor calculado com o valor crítico da tabela. Se \( χ² \) calculado for maior que o valor crítico, rejeita-se a hipótese nula.

### Exemplo Prático
Vamos supor que temos um restaurante que oferece três tipos de sobremesas e queremos testar se a preferência dos clientes por essas sobremesas é independente do gênero.

| Sobremesa | Homens (O) | Mulheres (O) | Total |
|-----------|-------------|--------------|-------|
| Sorvete   | 30          | 20           | 50    |
| Torta     | 10          | 30           | 40    |
| Frutas    | 10          | 10           | 20    |
| **Total** | 50          | 60           | 110   |

Frequências esperadas (E) são calculadas com base nas proporções dos totais:

| Sobremesa | Homens (E) | Mulheres (E) | Total |
|-----------|-------------|--------------|-------|
| Sorvete   | 50 * (50/110) = 22.73 | 60 * (50/110) = 27.27 | 50    |
| Torta     | 50 * (40/110) = 18.18 | 60 * (40/110) = 21.82 | 40    |
| Frutas    | 50 * (20/110) = 9.09  | 60 * (20/110) = 10.91 | 20    |

Calcular \( χ² \):

\[
χ² = \sum \frac{(O_i - E_i)^2}{E_i} = \frac{(30 - 22.73)^2}{22.73} + \frac{(20 - 27.27)^2}{27.27} + \frac{(10 - 18.18)^2}{18.18} + \frac{(30 - 21.82)^2}{21.82} + \frac{(10 - 9.09)^2}{9.09} + \frac{(10 - 10.91)^2}{10.91}
