# 📊 Análise de Desempenho da Rede de Supermercados: O Foco na Conversão

**(Projeto de Data Analysis)**

Este projeto visa diagnosticar os desafios de rentabilidade de uma rede de supermercados, movendo o foco de problemas percebidos (como falta de clientes ou espaço) para a **eficiência operacional** de cada filial.

## Contexto e Objetivo do Projeto

  * **Problema Central:** A rede enfrentava um momento de incerteza operacional e de rentabilidade. A análise confrontou a percepção de que a falta de espaço (`Store_Area`) ou de variedade (`Items_Available`) era o principal gargalo.
  * **Objetivo da Análise:** Mapear a performance de vendas (`Store_Sales`) em função de pilares operacionais, especialmente o fluxo de clientes (`Daily_Customer_Count`), para identificar onde o esforço não estava se convertendo em receita.
  * **Conclusão Principal (Insight):** Os problemas da rede não são de falta de clientes ou espaço, mas sim de **ineficiência na conversão de tráfego em receita**.

## Metodologia e Dados

  * **Ferramentas:** Python (foco em manipulação e visualização de dados), Jupyter Notebook.
  * **Conjunto de Dados:** Base robusta cobrindo centenas de filiais, contendo métricas como vendas, área física, itens disponíveis e contagem diária de clientes.
  * **Abordagem:** Análise exploratória de dados (EDA) para identificar correlações, seguido de uma análise de *clustering* ou classificação de performance para isolar lojas com alto fluxo e baixo **Ticket Médio**.

## Resultados e Principais Insights

A análise apontou para uma disparidade na capacidade de conversão das lojas:

  * **Baixo Ticket Médio:** Foi identificado que diversas filiais, apesar de um alto fluxo de clientes, apresentavam um baixo desempenho em vendas, indicando ineficiência no ponto de venda.
  * **Benchmarking Interno (Lojas Campeãs):** Foram isoladas **Lojas Campeãs em Conversão** (ex: Loja 433, Loja 167) que conseguem gerar vendas altíssimas com um fluxo de clientes moderado. Estas lojas devem se tornar o novo *benchmark* para toda a rede.

## Recomendações Estratégicas (Próximos Passos)

O futuro da empresa foi atrelado à transformação de clientes em compradores eficientes, gerando as seguintes ações:

### 1\. Ação Imediata: Auditoria de Conversão (Foco no Gargalo)

Realizar auditoria urgente nas lojas com baixo Ticket Médio (ex: Loja 32, Loja 353 12) para entender os gargalos no ponto de venda.

  * **Investigação Detalhada de:**
      * **Layout e Jornada do Cliente:** O cliente está encontrando o que precisa?
      * **Mix de Produtos:** O alto tráfego está sendo gerado por produtos de baixo valor, desequilibrando o faturamento?
      * **Precificação/Promoções:** Há uma estratégia que inadvertidamente afasta a compra de itens de maior valor agregado?

### 2\. Ação Estratégica: Replicar o Sucesso

Estudar e replicar as melhores práticas das **Lojas Campeãs em Conversão** (gestão de estoque, treinamento, layout) para elevar a performance de toda a rede.

## Estrutura do Repositório

  * `Analise_de_Supermarkets_Sales.ipynb`: Notebook Jupyter contendo o código Python, a análise completa, visualizações e o relatório final.
  * `README.md`: Este arquivo.
  * *Data set: `supermarket_data.csv`*

## Como Rodar o Projeto

1.  Clone este repositório:
    ```bash
    git clone [SEU_LINK_DO_REPOSITORIO]
    ```
2.  Instale as dependências Python necessárias (ex: `pandas`, `matplotlib`, `seaborn`).
3.  Abra o notebook `Analise_de_Supermarkets_Sales.ipynb` em um ambiente Jupyter (Jupyter Lab/Notebook) e execute as células.

-----

**Desenvolvido por:** [[Carlos Andrés Soto Espinosa](https://github.com/AndresEspinosa307)] - Analista de Dados

