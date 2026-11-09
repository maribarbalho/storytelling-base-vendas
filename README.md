# Base de vendas sintética com storytelling: TechShop

Geração de uma base de dados **fictícia** de vendas para praticar análise e visualização, com uma "história" embutida nos dados.

## A história da base

A **TechShop** é uma loja online fictícia de tecnologia e móveis para home office. A base de 1.000 pedidos de 300 clientes foi construída para que estes padrões apareçam na análise:

- Picos de vendas em **novembro (Black Friday)** e **dezembro (Natal)**.
- Descontos mais agressivos em novembro.
- Preferência por **cartão de crédito e Pix** como meios de pagamento.
- **Cancelamentos mais frequentes em boletos**.
- Notebooks, smartphones e cadeiras gamer entre os produtos mais vendidos.

## O que o notebook faz

1. Gera os pedidos com a biblioteca Faker (pt_BR), aplicando as regras acima.
2. Faz uma análise exploratória com gráficos de evolução mensal das vendas, meios de pagamento, status dos pedidos e produtos.
3. Exporta a base em CSV, pronta para estudos de BI.

**Ferramentas:** Python, Faker, Pandas, Matplotlib.

> Todos os dados são gerados artificialmente. Nenhuma informação real de clientes é usada.
