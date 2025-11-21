# Medidas de Dispersão e de Associação 

## 1. Medidas de Dispersão (Risco e Volatilidade)
- As medidas de dispersão indicam o quão espalhados os dados estão em relação à média.

#### Variância ($\sigma^2$)
- Definição: É a média dos quadrados dos desvios de cada valor em relação à média aritmética do conjunto.
- Interpretação: Quanto maior a variância, maior a dispersão dos dados e, consequentemente, maior a volatilidade (risco) do ativo.
- Limitação: O resultado é dado em unidade ao quadrado (por conta do cálculo), o que dificulta a comparação direta com os dados originais.

#### Desvio Padrão ($\sigma$)
- Definição: É a raiz quadrada da variância, resolvendo o problema da unidade ao quadrado.
- Cálculo: $\text{Desvio Padrão} = \sqrt{\text{Variância}}$.
- Interpretação: Permite avaliar o quão dispersos os dados estão na mesma unidade de medida da média. Por exemplo, se a média é 1% e o desvio padrão é 2%, espera-se uma variação de -1% a 3% em determinado período.

### 2. Medidas de Associação (Relação entre Variáveis)
- Usadas para entender como dois grupos de dados se relacionam linearmente.

#### Covariância
- Definição: Medida que indica a direção da relação linear entre duas variáveis (X e Y).
- Interpretação:
  - Covariância Positiva: As variáveis se movimentam na mesma direção (ex: uma sobe e a outra tende a subir).
  - Covariância Negativa: As variáveis se movimentam em direções opostas (ex: uma sobe e a outra tende a cair).
  - Covariância Nula (próximo de zero): Não há uma relação linear entre as variáveis.

#### Coeficiente de Correlação Linear de Pearson ($\rho$)
- Definição: Estipula um valor adimensional (entre -1 e +1) que mede a força e a direção da relação linear entre duas variáveis, permitindo a comparação entre diferentes séries de dados.
- Cálculo: $\rho = \frac{\text{Covariância (X, Y)}}{\text{Desvio Padrão de X} \times \text{Desvio Padrão de Y}}$
- Interpretação:
  - +1 (Correlação Perfeita Positiva): Variáveis se movem na mesma direção e na mesma proporção.
  - -1 (Correlação Perfeita Negativa): Variáveis se movem em direções opostas e na mesma proporção.
  - 0 (Correlação Nula): Não há relação linear entre as variáveis.

#### Coeficiente de Determinação ($R^2$)
- Definição: Mostra o percentual da variação de uma série (Y) que é explicada pela variação de outra série (X).
- Cálculo: Basta elevar ao quadrado o Coeficiente de Correlação de Pearson: $R^2 = \rho^2$.
- Interpretação: O resultado varia de 0 a 1 (ou 0% a 100%). Se $R^2$ é 0,58 (58%), significa que 58% das alterações em Y são explicadas pelas alterações em X.

## 3. Distribuição Normal (Curva de Sino)
- Conceito: Função estatística que descreve como os dados se distribuem de maneira simétrica em torno de uma média.
- Intervalos de Confiança (Regra Empírica): No contexto de investimentos (onde a média é o Retorno Médio e o Desvio Padrão é o Risco), a curva de sino permite estabelecer:
  - $\pm 1$ Desvio Padrão: Cobre $\approx 68,26\%$ dos retornos esperados.
  - $\pm 2$ Desvios Padrões: Cobre $\approx 95,44\%$ dos retornos esperados.
  - $\pm 3$ Desvios Padrões: Cobre $\approx 99,73\%$ dos retornos esperados.
- Aplicação: Se um fundo tem retorno médio de 3% e desvio padrão de 2%, o investidor pode esperar que em $95,44\%$ das vezes o retorno estará entre $-1\%$ e $7\%$ (3% $\pm$ 2x2%).