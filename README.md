# Desafio1_Lojas-_Alura
Curso de Praticando Python para Data Science: Challenge Alura Store

1. Propósito da Análise
Este repositório apresenta uma análise exploratória de dados sobre o desempenho de quatro lojas da Alura Store. O projeto tem como objetivo analisar os dados de vendas da Alura Store, para extrair insights valiosos sobre o desempenho das lojas, categorias de produtos mais vendidas e padrões de consumo.  a im de fornecer uma base analítica sólida para apoiar a decisão estratégica de qual loja deve ser vendida, com base em métricas quantitativas extraídas dos dados.

Principais Métricas Analisadas: 

* Análise do Faturamento por loja
* Vendas por Categoria de produtos
* Média de Avaliação das lojas
* Produtos Mais e Menos Vendidos
* Frete Médio por loja
* Distribuição Geográfica das lojas

2. Estrutura do Projeto

AluraStore/

├── dados/ # Dataset utilizado na análise

├── graficos/ # Visualizações geradas

├── notebook/ # Código de análise

│   └── AluraStoreBrCARA.ipynb  # Notebook principal

└── README.md            # Documentação do projeto



3. Exemplos de gráficos e insights obtidos.


3.1 Insights com referência aos resultados da análise de faturamento das lojas:

![image](https://github.com/user-attachments/assets/1dbfdcb2-f0af-49a5-b24c-03d81dff53d5)


Liderança da Loja 1 Maior faturamento é da loja 1, com R 1,53mi,superandoasegundalojaemvendas,(loja2)emR 46.050,06 e 9,8% acima da loja 4, indicando uma diferença significativa entre o topo e a base.

Desempenho Relativo A loja 2 e a loja 3 têm resultados próximos, apresentando uma diferença de apenas 1,7% entre elas, sugerindo que estratégias similares podem estar sendo aplicadas. A loja 4 está R$ 100.011,48 abaixo da loja 3, o que justifica uma investigação mais profunda do que está acontecendo.

Distribuição do Faturamento As duas melhores lojas com relação a faturamento (loja 1 e loja 2) representam 62% do faturamento total, enquanto as duas últimas (loja 3 e loja 4) respondem por 38%.


3.2 Insights com referência aos resultados das vendas por categoria:

![image](https://github.com/user-attachments/assets/ef6283a5-245b-4039-9de4-3cb6945e42e8)


Categorias Mais Vendidas (Destaques)

Os móveis lideram em volume de vendas (1.886 unidades), com a loja 3 sendo a melhor (499 vendas).

Os eletrônicos têm desempenho forte (1.772 unidades), com loja 3 e loja 4 empatadas (451 vendas cada).

Os brinquedos têm vendas equilibradas, mas a Loja 4 se destaca (338 unidades).

Categorias com Baixo Desempenho

Instrumentos Musicais e Livros são as menos vendidas (753 e 742 unidades, respectivamente).

A loja 4 vende menos instrumentos musicais (170 unidades), enquanto a loja 2 tem o melhor desempenho nessa categoria (224).

Comportamento por Loja

A loja 3 domina em móveis (499) e tem bom desempenho em eletrônicos (451).

A loja 4 lidera em brinquedos (338) e utilidades domésticas (201), mas tem baixo desempenho em eletrodomésticos (254).

A loja 2 se destaca em instrumentos musicais (224) e livros (197), categorias onde as outras lojas têm resultados menores.


3.3 Insights com referência aos resultados da média das avaliações por loja:

![image](https://github.com/user-attachments/assets/251cee67-0810-441d-9765-b62d26645c2d)


A loja 3 tem a melhor avaliação (4.048), seguida de perto pela loja 2 (4.037).

A diferença entre elas é mínima (0.011 pontos), indicando que ambas mantêm padrões similares de satisfação.

A loja 1 tem a pior avaliação (3.977), ficando 1.8% abaixo da loja 3. Nesse caso, vale investigar se há problemas

A loja 4 está na média (3.996), mas abaixo das lojas 2 e 3. A diferença para a Loja 3 (-0.053 pontos) sugere oportunidades de ajustes.

Em termo gerais, todas as lojas estão acima de 3.9, o que indica um bom nível de satisfação. Porém, nenhuma atinge 4.5+ (excelência), mostrando espaço para melhorias.


3.4 Insights com referência aos resultados produtos mais e menos vendidos por loja:

![image](https://github.com/user-attachments/assets/57e13270-12bc-49f7-b560-3f507fd4b3f3)


Produtos Mais Vendidos (Destaques Gerais)

Móveis lideram com 1.886 unidades, sendo a loja 3 a maior vendedora (499 unidades).

Eletrônicos vêm em segundo lugar (1.772 unidades), com loja 3 e loja 4 empatadas (451 unidades cada).

Brinquedos têm desempenho sólido (1.290 unidades), com Loja 4 se destacando (338 unidades).

![image](https://github.com/user-attachments/assets/330e3b2a-d8aa-4fff-842a-a1d1870243ff)



Produtos Menos Vendidos (Oportunidades)

Instrumentos Musicais (753 unidades) e Livros (742 unidades) são os menos vendidos.

Exceção: A Loja 2 vende significativamente mais instrumentos musicais (224 unidades) que as outras.

Utilidades Domésticas (730 unidades) também têm baixo volume, exceto na Loja 4 (201 unidades).

![image](https://github.com/user-attachments/assets/9f4451a1-e093-449c-8161-680585d670ae)


Desempenho por Loja

Loja 3: Líder em móveis (499) e eletrônicos (451). Desempenho mediano em outras categorias.

Loja 4: Destaque em brinquedos (338) e utilidades domésticas (201). Fraco desempenho em eletrodomésticos (254) e instrumentos musicais (170).

Loja 2: Melhor em instrumentos musicais (224) e livros (197). Resultados equilibrados nas demais categorias.

Loja 1: Nenhum liderança em absoluto, mas o desempenho é consistente.


Padrões e Anomalias

Loja 2 vs. Outras em Instrumentos Musicais: Vende 26% mais que a média das outras lojas. Pode ter melhor posicionamento ou promoções.


3.5 Insights com referência aos resultados da análise de frete por loja:

![image](https://github.com/user-attachments/assets/3be9093b-6ca6-4fb0-8175-3fb689754a55)


A Loja 1 tem o maior custo com frete (total e médio)

Frete médio de R$ 34,69 (até 10,9% mais caro que a Loja 4).

A Loja 4 tem o menor frete médio (R$ 31,28) 9,8% mais barato que a Loja 1, indicando eficiência logística.

As Lojas 2 e 3 têm fretes intermediários Diferença pequena entre elas (apenas 1,6% no frete médio). Loja 3 tem o segundo menor frete total, sugerindo gestão eficiente.

Discrepância nos fretes totais

A Loja 1 gasta R$ 8.082,09 a mais que a Loja 4 em frete no período analisado.

![image](https://github.com/user-attachments/assets/1c9ce1c1-a200-43ef-90ac-1f0b98d8a3e4)


Relatório: Análise Estratégica para Fechamento de Loja

Objetivo

Identificar qual das 4 lojas apresenta o pior desempenho combinado (faturamento, vendas, avaliações e custos logísticos) para sugerir seu fechamento, otimizando recursos e mantendo a saúde financeira do negócio.

Critérios de Avaliação

Foram analisados os seguintes dados:

Faturamento (receita total).
Vendas por categoria (desempenho por produto).
Avaliação dos clientes (satisfação).
Custos logísticos (frete total e médio).
Análise por Loja

Loja 1

o Pontos Fortes: Segundo maior faturamento, vendas sólidas em móveis/eletrônicos.

o Pontos Fracos: Pior avaliação (3.976), frete mais caro (R$ 34,69).

o Risco: Custos logísticos elevados podem corroer margens.

Loja 2

o Pontos Fortes: Boa avaliação (4.037), destaque em categorias nichadas (instrumentos/livros).

o Pontos Fracos: Faturamento médio, desempenho irregular em categorias principais.

Loja 3

o Pontos Fortes: Melhor avaliação (4.048), líder em vendas de móveis/eletrônicos.

o Pontos Fracos: Frete médio não é o mais baixo (R$ 33,07).

Loja 4

o Pontos Fortes: Frete mais barato (R$ 31,28), bom desempenho em brinquedos/utilidades.

o Pontos Fracos: Menor faturamento (R$ 1,38 mi), baixo desempenho em eletrodomésticos/instrumentos.

Indicação para Fechamento: Loja 4

Motivos

Menor faturamento: Gera 9,8% menos receita que a Loja 1 e tem desempenho fraco em categorias estratégicas (eletrodomésticos).

Impacto limitado: Seu fechamento afetaria menos o faturamento total (apenas ~10% do total).

Custos logísticos baixos: Apesar de ser um ponto positivo, não compensa o baixo retorno financeiro.

Desempenho médio em avaliações: Não se destaca em satisfação do cliente (Loja 3 é melhor).

Alternativas Consideradas

• Loja 1: Apesar do frete caro, tem faturamento alto e vendas sólidas. Pode melhorar com ajustes logísticos.

• Loja 2: Desempenho equilibrado, mas não é a pior em nenhum critério.

• Loja 3: Melhor em avaliações e vendas; deve ser mantida.

Conclusão

A Loja 4 é a melhor candidata para fechamento devido ao faturamento mais baixo, impacto limitado no mix de produtos e ausência de vantagens competitivas (exceto frete barato, insuficiente para justificar sua operação). A economia gerada pode ser reinvestida em melhorias nas lojas restantes



4. Instruções para executar o notebook.

Tecnologias Utilizadas:

* Google Colab: Ambiente de execução em nuvem

* Python: Linguagem principal


Bibliotecas:

* pandas: Manipulação de dados

* matplotlib: Visualizações gráficas

* folium: Mapeamento geográfico

Como Executar

* Pré-requisitos:

pip install pandas matplotlib numpy folium jupyter

* Executar o notebook:

jupyter notebook AluraStoreBrCARA.ipynb

* Analisar os resultados:

Todas as visualizações são geradas automaticamente

Dados são carregados diretamente de URLs públicas
