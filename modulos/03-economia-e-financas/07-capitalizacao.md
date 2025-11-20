# 💰 Resumo: Capitalização Simples e Composta (Aula 26 - CPA 20)

---

## I. Capitalização Simples (Juros Simples)

Na capitalização simples, o valor de referência para o cálculo dos juros é **sempre o montante inicial**.

* **Cálculo:** Os juros são calculados apenas sobre o capital principal, e o valor do juro não muda ao longo do tempo.
* **Crescimento:** O montante inicial cresce de forma **linear**, seguindo uma progressão aritmética.
* **Taxas Proporcionais:** É possível converter a taxa de um período para outro (ex: de mensal para anual) utilizando-se apenas multiplicação ou divisão. As taxas resultantes são chamadas de **Taxas Proporcionais**.

## II. Capitalização Composta (Juros Compostos)

No regime de capitalização composta, a taxa de juros incide sobre o **valor presente acrescido dos juros acumulados** (juros sobre juros).

* **Cálculo:** A cada novo período, a base de cálculo dos juros é atualizada (capital inicial + juros acumulados).
* **Crescimento:** O montante inicial cresce de forma **exponencial**, seguindo uma progressão geométrica. Quanto maior o prazo e a taxa de juros, maior o efeito exponencial.
* **Importância:** É o regime de capitalização adotado pela maioria das instituições financeiras no Brasil para empréstimos, financiamentos e aplicações financeiras.

## III. Taxas Equivalentes (Juros Compostos)

Nos juros compostos, não se pode usar apenas multiplicação ou divisão para converter taxas entre diferentes períodos (como se faz na taxa proporcional), pois o resultado não seria exato. É necessário encontrar as **Taxas Equivalentes**.

* **Função:** Comparar taxas de juros que operam em períodos diferentes, determinando uma única taxa que resultaria no mesmo montante final.
* **Fórmula de Equivalência de Taxas (Juros Compostos):**

$$\text{R2} = \left[ (1 + \text{R1})^{\frac{\text{N2}}{\text{N1}}} - 1 \right] \times 100$$

| Variável | Significado |
| :--- | :--- |
| **R2** | Taxa de juros que se busca obter. |
| **R1** | Taxa de juros conhecida (expressa em decimal). |
| **N2** | Período da taxa desejada. |
| **N1** | Período da taxa conhecida. |
| *N1 e N2* | Devem estar na mesma unidade de tempo (ex: meses). |

## IV. Comparações entre os Regimes

| Operação | Taxa Proporcional (Simples) | Taxa Equivalente (Composta) | Conclusão |
| :--- | :--- | :--- | :--- |
| **Capitalização** (Período menor $\to$ maior) | Menor | Maior | O juro composto é melhor para quem **investe**. |
| **Descapitalização** (Período maior $\to$ menor) | Maior | Menor | O juro simples (proporcional) é maior, sendo pior para o investidor (e melhor para quem **paga**). |
| **Um Período Apenas** | Coincidem | Coincidem | O resultado é o mesmo, pois o efeito dos juros compostos não se manifesta. |

* **Nota sobre Renda Fixa:** Títulos de renda fixa costumam remunerar em **dias úteis**. Para calcular o rendimento diário a partir da taxa anual (expressa no contrato), é necessário realizar a descapitalização utilizando a fórmula de taxas equivalentes, considerando que o ano financeiro possui **252 dias úteis**.

---
Link do vídeo: https://youtu.be/Fy_Iw7eT5EQ?si=ecnR583GqtINgAXq