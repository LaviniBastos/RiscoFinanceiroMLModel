# Girls Bank — Análise de Risco e Desempenho da Carteira de Crédito

Projeto de análise de dados desenvolvido com foco em Risk Analytics, explorando fatores relacionados à inadimplência, exposição financeira e rentabilidade de uma carteira de crédito.

### O projeto combina:

- Análise exploratória de dados,
- Visualização estratégica no Power BI,
- Consultas analíticas em SQL,
- e modelos de Machine Learning para previsão de risco.

### Objetivo do Projeto:

O principal objetivo deste projeto é identificar:

1. padrões de inadimplência,
2. perfis de maior risco,
3. impacto financeiro das perdas,
4. relação entre risco e rentabilidade,
5. além de investigar variáveis relevantes para previsão de **default**.

A proposta vai além de dashboards descritivos, buscando gerar:

- Insights de negócio,
- Hipóteses analíticas,
- e recomendações estratégicas para gestão de crédito.

## **Análises Realizadas**

Durante a análise foram explorados diversos fatores relacionados ao risco de crédito, incluindo:

#### ✔ Faixa de renda vs inadimplência

Análise da relação entre renda anual e risco de default, utilizando segmentação proporcional para evitar vieses estatísticos.

#### ✔ Taxa de juros vs risco

Investigação sobre a relação entre juros aplicados e inadimplência, identificando que juros elevados isoladamente não apresentaram correlação direta com defaults.

#### ✔ Perda financeira por grade de crédito

Avaliação do impacto financeiro das perdas por classificação de risco (grade), identificando maior exposição em grades mais arriscadas.

#### ✔ Perfil do cliente

**Análise do comportamento de inadimplência considerando:**

- Tipo de moradia,
- Duração do contrato,
- Finalidade do empréstimo,
- entre outros fatores.
  
#### ✔ Receita de juros vs perdas

Estudo sobre a sustentabilidade financeira da carteira, avaliando como a receita de juros pode compensar parcialmente perdas por inadimplência.

## Dashboard

O dashboard foi desenvolvido com foco em:

- Anaálise Geral dos principais KPI's,
- Storytelling analítico,
- Clareza visual,
- Interpretação do negócio,
- Comunicação executiva.

Os painéis incluem:

KPIs financeiros,
distribuição de risco,
análise temporal,
segmentação de clientes,
exposição financeira por grade,
e indicadores de rentabilidade.

Link da apresentação do relatório no Power Bi: https://canva.link/fn1dlwcllif6wl4

## Etapa Machine Learning

Além da análise exploratória, foram desenvolvidos modelos preditivos para classificação de inadimplência utilizando os seguintes modelos:

1. XGBoost
2. Regressão Logística
3. TensorFlow

Os modelos foram utilizados para prever o risco de default com base nas variáveis financeiras e comportamentais dos clientes, identificando possíveis mal pagadores e bons pagadores com base em todo seu histórico financeiro.

## Etapa Análise com SQL

Também foi realizada uma etapa de exploração e análise utilizando SQL, com foco em:

- Consultas analíticas,
- Agregações,
- Filtros de risco,
- Métricas financeiras,
- e extração de insights diretamente da base de dados.

## 🛠️ Tecnologias Utilizadas

- Power BI
- SQL
- Python
- Pandas
- Scikit-learn
- TensorFlow
- XGBoost
- Matplotlib / Seaborn
- StreamLit


## 📌 Principais Insights aprendidos durante o processo de análise:

- Grades de crédito mais arriscadas concentraram maiores perdas financeiras.
- A inadimplência não depende de um único fator isolado.
- Algumas finalidades de empréstimo apresentaram maior propensão ao default.
- Juros elevados não demonstraram relação direta com inadimplência nesta base.
- A receita gerada pelos juros contribui para compensar parte das perdas da carteira.


## Conclusão

Com uma análise orientada por dados, foi possível identificar padrões de risco e oportunidades para otimizar a carteira de crédito.
Embora o banco apresente forte rentabilidade através da receita de juros (que atualmente supera parte das perdas causadas pela inadimplência), a utilização de análises mais profundas e modelos preditivos permite reduzir significativamente o risco de concessão de crédito para clientes com maior probabilidade de default.
Como consequência, a instituição pode diminuir perdas financeiras, melhorar a qualidade da carteira e tornar suas decisões de crédito mais estratégicas e sustentáveis.

## Contribuidoras

- Power Bi: Lavini Bastos
- Modelos: Natállia Neiva
- SQL: Victoria Goold
- StreamLit: Mariane Rodrigues

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/LaviniBastos" title="GitHub">
        <img src="https://avatars.githubusercontent.com/u/160741212?v=4" width="100px;" alt="Foto Lavini"/><br>
        <sub>
          <b>Lavini Bastos </b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/natallia-neiva" title="GitHub">
        <img src="https://avatars.githubusercontent.com/u/235322157?v=4" width="100px;" alt="Foto Natallia"/><br>
        <sub>
          <b>Natállia Neiva</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/vicjaykosz" title="GitHub">
        <img src="https://avatars.githubusercontent.com/u/135620503?v=4" width="100px;" alt="Foto Victoria"/><br>
        <sub>
          <b>Victoria Goold</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/marianecosta" title="GitHub">
        <img src="https://avatars.githubusercontent.com/u/84878947?v=4" width="100px;" alt="Foto Mariane"/><br>
        <sub>
          <b>Mariane Rodrigues</b>
        </sub>
      </a>
    </td>
</table>
