# A Microvan e o Desafio da Segmentação de Mercado
<img src="https://i.namu.wiki/i/OWOzE3u1R6SxTWDN9GkLLDgO_sTkyTGzI6zHQj3lpSb6ONtRYpzmz7bFlWs8BwNuQE1Lt7GadbKHiDuLhQj74qV7IwNBXbvACu3iapkNTzbKtnQZHWXn34LTmgD_RXKeWg8ke9_Uau8IXNMvdJILfg.webp" />

### **Motivação:**

Uma empresa que deseja lançar um novo produto costuma realizar pesquisas para entender com mais precisão as necessidades e os desejos dos clientes. Essas informações são fundamentais para orientar as estratégias de marketing no momento do lançamento.

No entanto, questionários que geram dezenas ou até centenas de variáveis podem ser desafiadores de analisar, especialmente quando o objetivo é identificar grupos de clientes com características semelhantes. É nesse contexto que o PCA (Análise de Componentes Principais) se torna uma ferramenta valiosa: ele reduz a dimensionalidade dos dados, tornando mais fácil interpretar os resultados e aplicar técnicas de clusterização de forma eficiente.

Esse tipo de abordagem não se limita a um único setor — é altamente aplicável em diversas áreas da economia!

### **Objetivo:**

A Empresa esta desenvolvendo um novo conceito de veículo — uma microvan, que é maior que um SUV, porém mais compacta que uma minivan. Nosso objetivo é identificar qual é o público ideal para direcionar as primeiras campanhas de marketing.

O principal método para identificar tendências e preferências dos consumidores é por meio de pesquisa primária, que geralmente começa com grupos focais e evolui para pesquisas de média e grande escala. Esse processo tem, basicamente, dois objetivos principais:

Entender os desejos e necessidades de um determinado grupo ou nicho de consumidores.

Aliar essas informações aos dados demográficos para traçar o perfil de quem demonstrou interesse no conceito da microvan desenvolvida pela Empresa.

As principais perguntas de negócio que buscamos responder são:

Qual é o segmento-alvo ideal para esse novo veículo?

Quais são as principais necessidades e desejos desse público?

Para isso, a Empresa conduziu vários grupos focais com potenciais compradores do novo conceito de microvan — um veículo maior que um SUV, mas mais compacto que uma minivan. A equipe de marketing também avaliou uma ampla lista de atributos que poderiam ser relevantes para os consumidores, além de declarações relacionadas a estilo de vida, todas validadas por pesquisas anteriores no setor automotivo.

A partir das anotações feitas durante os grupos focais, foi definido um conjunto de 30 atributos considerados fundamentais, além de variáveis demográficas importantes. O objetivo é usar esses atributos para compreender as principais dimensões que caracterizam os potenciais compradores e, a partir disso, segmentar o mercado para direcionar as campanhas de marketing.

Como parte do estudo, também foi apresentado um protótipo do carro, e os participantes foram convidados a avaliar seu grau de interesse em uma escala de 1 a 9.

No entanto, utilizar diretamente esses 30 atributos em uma análise de clusterização geraria resultados pouco claros e difíceis de interpretar. Para resolver esse problema, aplicamos a técnica de PCA (Análise de Componentes Principais), que permite reduzir a dimensionalidade dos dados, agrupando variáveis que compartilham padrões de variância semelhantes. Isso facilita a interpretação e torna a análise mais eficiente.

O PCA, por si só, já permite observar agrupamentos naturais de perfis de respostas. No entanto, a avaliação da homogeneidade dentro dos grupos é feita de forma mais precisa através da clusterização, aplicada sobre os componentes principais resultantes do PCA.

Esse tipo de abordagem é extremamente útil e aplicável em diversos setores além da indústria automotiva, como bancos, telecomunicações, varejo e qualquer empresa que ofereça serviços e possua bases de dados sobre seus clientes. A análise de questionários combinada com redução de dimensionalidade via PCA se mostra uma ferramenta poderosa para entender melhor o comportamento dos consumidores e aprimorar estratégias de segmentação.

Este estudo de caso real — “Grosse Pointe Associates and The Microvan” — está disponível no excelente livro “Modern Marketing Research: Concepts, Methods, and Cases”, ISBN 1133188966.


-----------------------

### **Dados:**

Os dados estão disponíveis para download [aqui](https://github.com/reisricardo1/unsupervised_learning/new/master/data/microvan.csv) no repositório.

-----------------------
## Notebooks
Nesse repositório você encontrará o notebook de Aprendizado Não Supervisionado com  técnica de PCA (Análise de Componentes Principais) e  Clusterização com K-means.

[**unsupervised_learning**](https://github.com/reisricardo1/unsupervised_learning/new/master/unsupervised_learning_v001.ipynb)

#### Questões de Negócio:
**Pergunta 1:** Qual é o segmento-alvo ideal para esse novo veículo?

**Pergunta 2:** Quais são as principais necessidades e desejos desse público?

------------

## Requisitos e Replicações:

Neste projeto, foi utilizada a versão 3.12.3 do Python

A versão do pip utilizada é a 25.1.1

A versão do git utilizada é a 2.43.0

Demais requisitos se encontram no arquivo requirements.txt

<details>
  <summary>Para utilizar este projeto, siga as instruções abaixo:</summary>

  <details>
    <summary>Passo 1: Clonar o repositório</summary>

    git clone https://github.com/reisricardo1/unsupervised_learning.git

  </details>

  <details>
    <summary>Passo 2: Instalar os pacotes nas versões utilizadas</summary>

    pip install -r requirements.txt
    
  </details>

</details>

