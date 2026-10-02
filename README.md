# Análise de Campanhas de Marketing | Power BI

> 1.999 clientes · 7 países · 4 dashboards · 10+ visuais

Análise do perfil de clientes, do comportamento de compra e da efetividade de campanhas de Marketing, para entender **quem compra, como compra e quais perfis respondem melhor às campanhas**. Projeto desenvolvido no curso **Microsoft Power BI Para Business Intelligence e Data Science**, da Data Science Academy (DSA), com uma base de dados fictícia customizada pelo curso.

## Dashboards

### Visão Cliente
Perfil da base por escolaridade, estado civil e país.

![Visão Cliente](imagens/visao-cliente.png)

### Visão Comportamento de Compra
Dispersão de gasto por salário, árvore de decomposição do gasto total e gastos por filhos e adolescentes em casa.

![Visão Comportamento](imagens/visao-comportamento.png)

### Visão Performance das Campanhas
Efetividade por número de filhos, resultado geral, matriz por estado civil, país e escolaridade, e salário médio por resultado.

![Visão Campanhas](imagens/visao-campanhas.png)

### Visão Ponto de Venda
Gasto por categoria e país, e evolução do gasto por país entre 2018 e 2023.

![Visão Ponto de Venda](imagens/visao-ponto-de-venda.png)

## Principais insights

**Performance das campanhas**
- **16% dos clientes (cerca de 320) compraram nas campanhas**, contra 84% que não compraram.
- Quem comprou tem **salário médio maior**: 59 mil contra 51 mil (cerca de 15% a mais).
- A adesão **cai conforme aumenta o número de filhos em casa**: 18% entre clientes sem filhos, 13,5% com 1 filho e 5% com 2 filhos (este último grupo tem apenas 39 clientes).

**Comportamento de compra**
- Clientes **sem filhos em casa concentram cerca de 85% do gasto total** (1,03 Mi de 1,21 Mi). Eles são 57% da base, mas o gasto médio por cliente é cerca de 4x maior que o de clientes com 1 filho.
- O mesmo padrão aparece com adolescentes: quem não tem adolescentes em casa gasta 0,71 Mi, contra 0,47 Mi de quem tem 1.
- O gasto **cresce com o salário até cerca de 100 mil**. Clientes de renda muito alta (150 mil ou mais) aparecem com gasto baixo.
- **Solteiros respondem por 59% do gasto** (707 mil), seguidos por casados (319 mil) e divorciados (178 mil).

**Padrões por país**
- Os **Estados Unidos concentram quase metade da base** (977 clientes) e têm o maior gasto, seguidos por Espanha (302) e Chile (245).
- O gasto dos EUA passou de **49 mil em 2018 para 159 mil em 2023**, com pico em 2020 (142 mil) e queda em 2021 (69 mil).

**Recomendações**
- Priorizar nas campanhas clientes sem filhos em casa e com maior renda, que mais compram e mais aderem.
- Criar ofertas específicas para famílias com filhos, que hoje respondem pouco.
- Investigar o crescimento dos EUA e a queda geral de 2021.

## Desenvolvimento

- Tratamento e correção dos dados no **Power Query**
- Criação de medida em **DAX** (`TotalGasto`, gasto total por cliente)
- 4 dashboards interativos com mais de 10 visuais: dispersão, árvore de decomposição, gráficos combinados, colunas, pizza, linhas e matriz
- Segmentadores e cruzamento do perfil dos clientes com o resultado das campanhas

## Limitações

- Os dados são **fictícios e customizados para o curso**, então os resultados servem como exercício de análise, não como conclusões de negócio reais.
- As análises mostram **associações**, não causalidade.
- A unidade monetária não está indicada na base.


## Arquivo Power BI

[Baixar o arquivo `.pbix`](./Campanha_Marketing.pbix)

## Ferramentas

Power BI · Power Query · DAX

## Curso

**Microsoft Power BI Para Business Intelligence e Data Science** · Data Science Academy
