# Mercado de Opções (Derivativos)

## 1. Conceito e Terminologia
- Definição: Negociação do direito de comprar (Call) ou de vender (Put) um ativo por um Preço Fixo (Strike/Preço de Exercício) em uma Data Futura (Vencimento).
- Prêmio (Remuneração): Valor pago pelo Titular ao Lançador para adquirir o direito da opção.
- Titular (Comprador):
  - Tem o direito, mas não a obrigação, de exercer a opção.
  - Prejuízo Máximo: Limitado ao prêmio pago.
  - Garantias: Não precisa depositar garantias.
- Lançador (Vendedor):
  - Tem a obrigação de atender ao exercício do titular.
  - Lucro Máximo: Limitado ao prêmio recebido.
  - Garantias: Precisa depositar margem ou o próprio ativo (Opção Coberta).

## 2. Tipos de Opções

#### Opção de Compra (Call)

| POSIÇÃO               | AÇÃO                               | LUCRO MÁXIMO                          | PREJUÍZO MÁXIMO                       |
|:----------------------|:-----------------------------------|:--------------------------------------|:--------------------------------------|
| Titular (Compra Call) | Direito de comprar no vencimento.  | Infinito (se o preço do ativo subir). | Limitado ao Prêmio pago.              |
| Lançador (Vende Call) | Obrigação de vender no vencimento. | Limitado ao Prêmio recebido.          | Infinito (se o preço do ativo subir). |

#### Opção de Venda (Put)

| POSIÇÃO              | AÇÃO                                | LUCRO MÁXIMO                                | PREJUÍZO MÁXIMO                             |
|:---------------------|:------------------------------------|:--------------------------------------------|:--------------------------------------------|
| Titular (Compra Put) | Direito de vender no vencimento.    | Limitado (se o preço do ativo cair a zero). | Limitado ao Prêmio pago.                    |
| Lançador (Vende Put) | Obrigação de comprar no vencimento. | Limitado ao Prêmio recebido.                | Limitado (se o preço do ativo cair a zero). |

## 3. Classificação por Vencimento (Estilo de Opção)

| TIPO                                                                            | EXERCÍCIO                                                      | LIQUIDAÇÃO ANTECIPADA        |
|:--------------------------------------------------------------------------------|:---------------------------------------------------------------|:-----------------------------|
| Americana                                                                       | Pode ser exercida a qualquer momento até a data de vencimento. | Sim, por decisão do titular. |
| Europeia                                                                        | Só pode ser exercida na data de vencimento.                    | Não.                         |
| Na Bovespa: O vencimento das opções ocorre na terceira sexta-feira de cada mês. |                                                                |                              |

## 4. Moneyness (Relação entre Preços)
- Classificação que descreve a relação entre o Preço de Exercício (Strike) e o Preço de Negociação Atual do ativo:

| CLASSIFICAÇÃO (MONEYNESS) | CONDIÇÃO (CALL)                           | CONDIÇÃO (PUT)                            |
|:--------------------------|:------------------------------------------|:------------------------------------------|
| In The Money (ITM)        | Preço de Exercício abaixo do Preço Atual. | Preço de Exercício acima do Preço Atual.  |
| At The Money (ATM)        | Preço de Exercício igual ao Preço Atual.  | Preço de Exercício igual ao Preço Atual.  |
| Out Of The Money (OTM)    | Preço de Exercício acima do Preço Atual.  | Preço de Exercício abaixo do Preço Atual. |

## 5. Fatores de Precificação do Prêmio
- O valor do prêmio de uma opção é influenciado por diversos fatores:

| FATOR                        | EFEITO NA CALL (COMPRA) | EFEITO NA PUT (VENDA) |
|:-----------------------------|:------------------------|:----------------------|
| Taxa de Juros (Aumento)      | Aumenta o Prêmio.       | Diminui o Prêmio.     |
| Tempo (Aumento)              | Aumenta o Prêmio.       | Aumenta o Prêmio.     |
| Volatilidade (Aumento)       | Aumenta o Prêmio.       | Aumenta o Prêmio.     |
| Preço do Ativo (Aumento)     | Aumenta o Prêmio.       | Diminui o Prêmio.     |
| Preço de Exercício (Aumento) | Diminui o Prêmio.       | Aumenta o Prêmio.     |

## 6. Tributação (Imposto de Renda)
- Alíquota: 15% sobre o ganho líquido na negociação/liquidação do contrato.
- Fato Gerador: O ganho líquido.
- Recolhimento na Fonte: Retenção de 0,005% ("Dedo-duro").
- Responsabilidade: Do Contribuinte (investidor), apurado em períodos mensais (DARF).
- Compensação de Perdas: Permitida com ganhos em operações realizadas nos mercados a termo, futuro, ou opções (exceto day-trade).