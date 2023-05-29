# Estatística

## Table of Contents
- [Estatística](#estatística)
  - [Table of Contents](#table-of-contents)
  - [O que é](#o-que-é)
    - [Estatística Descritiva](#estatística-descritiva)
    - [Probabilidade e Teoria das Distribuições](#probabilidade-e-teoria-das-distribuições)
    - [Inferência Estatística](#inferência-estatística)
  - [Amostragem](#amostragem)
    - [Tipos de amostragem](#tipos-de-amostragem)
      - [Amostragem Probabilística](#amostragem-probabilística)
      - [Amostragem Não Probabilística](#amostragem-não-probabilística)
    - [Métodos de amostraagem](#métodos-de-amostraagem)
      - [Amostragem Aleatória Simples](#amostragem-aleatória-simples)
      - [Amostragem Estratificada](#amostragem-estratificada)
      - [Amostragem por Conglomerados](#amostragem-por-conglomerados)
      - [Amostragem Sistemática](#amostragem-sistemática)
      - [Amostragem por Conveniência](#amostragem-por-conveniência)
  - [Tipos de dados](#tipos-de-dados)
    - [Numéricos (Quantitativos)](#numéricos-quantitativos)
      - [Dados Discretos](#dados-discretos)
      - [Dados Contínuos](#dados-contínuos)
    - [Categóricos (Qualitativos)](#categóricos-qualitativos)
      - [Dados Nominais](#dados-nominais)
      - [Dados Ordinais](#dados-ordinais)
  - [Tabelas](#tabelas)
  - [Tipos de frequência](#tipos-de-frequência)
  - [Gráficos](#gráficos)
  - [Tipos de gráficos](#tipos-de-gráficos)
  - [Medidas](#medidas)
    - [Medidas de posição](#medidas-de-posição)
    - [Medidas de disperção](#medidas-de-disperção)
  - [Análise de dados bidimensional](#análise-de-dados-bidimensional)
  - [Coeficiente de correlação](#coeficiente-de-correlação)
    - [Formula](#formula)
  - [Regressão Linear Simples](#regressão-linear-simples)
    - [Fórmula](#fórmula)
      - [Equação da regressão linear](#equação-da-regressão-linear)
      - [Equação coeficiente linear](#equação-coeficiente-linear)
      - [Equação coeficiente angular](#equação-coeficiente-angular)
  - [Coeficiente de determinação](#coeficiente-de-determinação)
  - [Probabilidade](#probabilidade)
    - [Espaço amostral](#espaço-amostral)
    - [Eventos](#eventos)
      - [Tipos de eventos](#tipos-de-eventos)
        - [Evento simples](#evento-simples)
        - [Evento composto](#evento-composto)
        - [Evento impossível](#evento-impossível)
        - [Evento certo](#evento-certo)
      - [Operações entre eventos](#operações-entre-eventos)
  - [Análise combinatória](#análise-combinatória)
  - [Probabilidade total, parcial e Teorema de Bayes](#probabilidade-total-parcial-e-teorema-de-bayes)
    - [Probabilidade Total](#probabilidade-total)
    - [Probabilidade Parcial](#probabilidade-parcial)
    - [Teorema de Bayes](#teorema-de-bayes)

## O que é

A estatística é uma disciplina que lida com a coleta, organização, análise, interpretação e apresentação de dados. Ela envolve métodos e técnicas para descrever e resumir informações, extrair insights úteis dos dados e tomar decisões informadas com base em evidências estatísticas.

As três grandes áreas da estatística são:

### Estatística Descritiva

A estatística descritiva envolve a organização, resumo e apresentação dos dados de forma informativa. Ela busca descrever os dados de maneira concisa, apresentando medidas de tendência central, como média, mediana e moda, além de medidas de dispersão, como desvio padrão e variância. A estatística descritiva permite que os dados sejam visualizados e entendidos de forma mais clara, fornecendo uma base sólida para análises posteriores.

### Probabilidade e Teoria das Distribuições

A teoria da probabilidade é fundamental na estatística. Ela estuda a incerteza e a aleatoriedade dos eventos e fornece ferramentas matemáticas para modelar e quantificar essas incertezas. A teoria das distribuições descreve as características e os padrões de distribuição dos dados. As distribuições de probabilidade, como a distribuição normal, a distribuição binomial e a distribuição de Poisson, são amplamente utilizadas na modelagem estatística e na inferência.

### Inferência Estatística

A inferência estatística é a área da estatística que se concentra em fazer inferências e tomar decisões sobre uma população com base em uma amostra limitada de dados. Ela envolve o uso de métodos estatísticos para estimar parâmetros desconhecidos da população, testar hipóteses estatísticas e fazer previsões. A inferência estatística é usada para generalizar as conclusões de uma amostra para a população mais ampla, fornecendo informações úteis para a tomada de decisões e a obtenção de insights sobre fenômenos complexos.

Essas três grandes áreas da estatística estão inter-relacionadas e se complementam. A estatística descritiva fornece uma base sólida para a compreensão e a apresentação dos dados, enquanto a teoria das distribuições e a probabilidade permitem a modelagem adequada dos dados. Por fim, a inferência estatística permite extrapolar as conclusões obtidas a partir de uma amostra para toda a população, permitindo que sejam feitas afirmações mais amplas com base em evidências estatísticas sólidas.

## Amostragem

Amostragem é o processo de seleção de uma parte representativa de uma população maior com o objetivo de realizar inferências sobre a população como um todo. É uma técnica amplamente utilizada na estatística para coletar dados de forma eficiente e obter informações sobre uma população sem a necessidade de examinar todos os elementos dessa população.

### Tipos de amostragem

#### Amostragem Probabilística

Na amostragem probabilística, cada elemento da população tem uma chance conhecida e não nula de ser selecionado para fazer parte da amostra. Isso significa que todos os elementos têm uma oportunidade igual de serem escolhidos. Os métodos de amostragem probabilística são baseados em princípios estatísticos e permitem fazer inferências precisas sobre a população com base nas características da amostra.

Alguns exemplos de métodos de amostragem probabilística são a amostragem aleatória simples, a amostragem estratificada, a amostragem por conglomerados e a amostragem sistemática. Esses métodos utilizam técnicas estatísticas para garantir uma seleção aleatória ou aleatória estratificada dos elementos da população, o que permite generalizar as conclusões obtidas da amostra para a população como um todo.

#### Amostragem Não Probabilística

Na amostragem não probabilística, a seleção dos elementos da amostra não é baseada em princípios estatísticos e não é garantido que cada elemento tenha uma chance conhecida de ser escolhido. A escolha dos elementos é feita com base na conveniência, disponibilidade ou julgamento do pesquisador. Isso significa que certos elementos da população têm maior probabilidade de serem selecionados do que outros, e não é possível calcular a margem de erro ou fazer inferências estatísticas precisas para a população.

Alguns exemplos de métodos de amostragem não probabilística incluem amostragem por conveniência, amostragem de julgamento, amostragem de bola de neve e amostragem por cotas. Esses métodos são frequentemente utilizados quando a acessibilidade à população ou recursos limitados tornam difícil a implementação de uma amostragem probabilística.

É importante observar que a amostragem probabilística geralmente é preferida em estudos científicos e pesquisas, pois permite uma análise estatística mais robusta e resultados mais confiáveis. No entanto, a amostragem não probabilística ainda pode ser útil em certas situações, como estudos exploratórios ou quando a generalização dos resultados não é o objetivo principal.

### Métodos de amostraagem

Existem diferentes métodos de amostragem, cada um adequado para diferentes situações e objetivos de pesquisa. Alguns dos métodos mais comuns incluem:

#### Amostragem Aleatória Simples

Neste método, cada elemento da população tem uma chance igual de ser selecionado. Um exemplo seria o sorteio de nomes de uma lista para formar uma amostra. A amostragem aleatória simples é frequentemente usada quando a população é homogênea e não há informações adicionais disponíveis sobre os elementos.

#### Amostragem Estratificada

Nesse método, a população é dividida em grupos ou estratos com características semelhantes e, em seguida, amostras são selecionadas aleatoriamente de cada estrato proporcionalmente ao tamanho do estrato na população. Isso é útil quando a população possui subgrupos distintos e é importante garantir que cada subgrupo esteja adequadamente representado na amostra.

#### Amostragem por Conglomerados

Nesse método, a população é dividida em conglomerados, que são grupos naturais ou geograficamente definidos. Em seguida, alguns conglomerados são selecionados aleatoriamente e todos os elementos desses conglomerados são incluídos na amostra. Isso é útil quando é difícil obter uma lista completa de elementos da população, mas é possível identificar conglomerados.

#### Amostragem Sistemática

Nesse método, os elementos da população são selecionados em intervalos regulares após a escolha aleatória do primeiro elemento. Por exemplo, em uma população de 1.000 elementos, pode-se selecionar aleatoriamente um número entre 1 e 10 e, em seguida, selecionar a cada 10º elemento subsequente.

#### Amostragem por Conveniência

Esse método envolve a seleção dos elementos mais facilmente disponíveis ou convenientes para formar a amostra. Embora seja rápido e fácil de implementar, pode levar a uma amostra não representativa e enviesada.

A escolha do método de amostragem depende da natureza da população, dos recursos disponíveis, dos objetivos da pesquisa e das restrições de tempo e orçamento. É importante garantir que a amostra seja representativa da população-alvo, a fim de obter resultados válidos e confiáveis ao fazer inferências sobre a população com base nos dados amostrais coletados.

## Tipos de dados

### Numéricos (Quantitativos)

#### Dados Discretos

Os dados discretos são valores que representam contagens ou números inteiros específicos. Esses valores são geralmente resultantes de uma contagem ou contagem de itens. Exemplos de dados discretos incluem o número de estudantes em uma sala de aula, o número de carros em um estacionamento, o número de gols marcados em um jogo de futebol, entre outros. Esses dados são distintos e não podem ser divididos em partes menores. A análise de dados discretos envolve a contagem de frequências e a construção de gráficos de barras ou diagramas de setores.

#### Dados Contínuos

Os dados contínuos são valores numéricos que podem assumir qualquer valor dentro de um intervalo contínuo. Esses valores são geralmente obtidos por meio de medições e podem incluir uma ampla gama de valores possíveis. Exemplos de dados contínuos incluem altura, peso, temperatura, tempo de reação, entre outros. Esses dados podem ser divididos em partes menores e podem assumir valores fracionários. A análise de dados contínuos envolve o uso de técnicas estatísticas como médias, desvio padrão, histogramas e gráficos de linha.

### Categóricos (Qualitativos)

#### Dados Nominais

Os dados nominais são categorias ou rótulos que representam diferentes grupos ou categorias. Eles não possuem uma ordem ou sequência específica. Exemplos de dados nominais incluem o gênero (masculino/feminino), estado civil (solteiro/casado/divorciado), cor dos olhos (azul/verde/castanho), entre outros. Para análise, esses dados podem ser resumidos por meio de frequências e proporções.

#### Dados Ordinais

Os dados ordinais também representam categorias, mas possuem uma ordem ou sequência específica. Essa ordem implica que uma categoria é maior, menor ou igual a outra. Exemplos de dados ordinais incluem classificações em uma escala de preferência (como "muito satisfeito", "satisfeito", "neutro", "insatisfeito", "muito insatisfeito") ou níveis de concordância (como "discordo totalmente", "discordo parcialmente", "neutro", "concordo parcialmente", "concordo totalmente"). Para análise, os dados ordinais podem ser resumidos por meio de medianas ou percentis.

## Tabelas

Uma tabela estatística é composta por diferentes elementos que organizam e apresentam os dados de forma estruturada. Vamos explorar os principais elementos de uma tabela e discutir a distribuição de frequência:

1. Título: O título da tabela descreve o conteúdo geral da tabela e fornece informações sobre o que está sendo apresentado.

1. Cabeçalho de colunas: O cabeçalho de colunas identifica as variáveis ​​ou características que estão sendo analisadas e são listadas na parte superior da tabela. Cada coluna representa uma variável específica.

1. Cabeçalho de linhas: O cabeçalho de linhas contém os rótulos ou categorias para cada linha da tabela. Dependendo da estrutura da tabela, o cabeçalho de linhas pode ser opcional.

1. Corpo da tabela: O corpo da tabela contém os dados propriamente ditos, organizados nas células da tabela. Cada célula representa um valor específico para uma combinação de variáveis.

1. Rodapé: O rodapé da tabela pode ser utilizado para fornecer informações adicionais, como notas explicativas, fontes de dados ou outras informações relevantes.

## Tipos de frequência

Existem três tipos principais de frequência que podem ser usados ​​na análise estatística:

1. Frequência Absoluta: A frequência absoluta é o número de vezes que um determinado valor ou categoria ocorre em um conjunto de dados. Por exemplo, se tivermos uma amostra de 50 pessoas e queremos contar o número de pessoas de cada grupo sanguíneo, a frequência absoluta para cada tipo sanguíneo seria o número de pessoas com aquele tipo específico.

1. Frequência Relativa: A frequência relativa é a proporção ou a porcentagem de vezes que um valor ou categoria ocorre em relação ao total de observações. É calculada dividindo a frequência absoluta pelo tamanho total da amostra. Por exemplo, se em uma amostra de 50 pessoas, 10 têm o tipo sanguíneo A, a frequência relativa do tipo sanguíneo A seria 10/50 = 0,2 ou 20%.

1. Frequência Acumulada: A frequência acumulada é a soma das frequências absolutas ou relativas acumuladas até um determinado valor ou categoria. Ela mostra a quantidade acumulada de ocorrências de um valor específico ou de todas as ocorrências anteriores. A frequência acumulada pode ser crescente (acumulação ascendente) ou decrescente (acumulação descendente). É útil para identificar o percentil de um valor em relação ao total de dados.

## Gráficos

Um gráfico é uma representação visual de dados que ajuda a transmitir informações de forma clara e concisa. Os elementos principais de um gráfico incluem:

1. Eixos: Os eixos são linhas retas que definem as dimensões do gráfico. Geralmente, temos um eixo horizontal (eixo x) e um eixo vertical (eixo y). Os eixos fornecem referência para as posições dos pontos de dados no gráfico.

1. Título: O título do gráfico descreve o conteúdo geral ou a finalidade do gráfico. Ele fornece uma indicação rápida do que está sendo representado no gráfico.

1. Legenda: A legenda é uma área do gráfico que explica o significado das cores, símbolos ou linhas usadas no gráfico. Ela ajuda a identificar as diferentes séries de dados ou categorias representadas no gráfico.

1. Rótulos dos eixos: Os rótulos dos eixos são textos que descrevem o que está sendo medido em cada eixo. Eles indicam as unidades de medida ou as categorias representadas. Por exemplo, no eixo x, pode-se ter "Tempo" e, no eixo y, "Valor".

1. Escala dos eixos: A escala dos eixos define como os valores dos dados são distribuídos ao longo dos eixos. Ela determina a relação de proporção entre os pontos de dados no gráfico.

1. Marcadores de dados: Os marcadores de dados são pontos, símbolos, barras ou linhas que representam os valores dos dados no gráfico. Eles são posicionados de acordo com os valores correspondentes no eixo x e no eixo y. Os marcadores de dados podem ter diferentes formas, cores ou tamanhos para distinguir séries de dados diferentes.

1. Grade: A grade é uma rede de linhas horizontais e verticais que atravessam o gráfico. Ela facilita a leitura e a interpretação dos valores dos dados, fornecendo referências visuais.

1. Título dos marcadores de dados: Em alguns gráficos, é possível adicionar títulos ou rótulos aos marcadores de dados. Esses títulos podem fornecer informações adicionais sobre os valores específicos representados.

Os elementos acima podem variar dependendo do tipo de gráfico utilizado, como gráficos de barras, gráficos de linhas, gráficos de pizza, entre outros. A escolha dos elementos adequados dependerá do objetivo do gráfico e do tipo de dados que estão sendo representados.

## Tipos de gráficos

Existem vários tipos de gráficos que podem ser usados para representar diferentes tipos de dados e transmitir informações de forma visualmente eficaz. Alguns dos tipos mais comuns de gráficos incluem:

1. Gráfico de Barras: Um gráfico de barras exibe os dados usando barras retangulares horizontais ou verticais, onde o comprimento ou a altura das barras representa a magnitude dos valores. É usado para comparar valores entre diferentes categorias ou grupos.

1. Gráfico de Linhas: Um gráfico de linhas conecta pontos de dados com linhas retas, mostrando a tendência ou a mudança ao longo do tempo ou de uma variável para outra. É usado para visualizar tendências, padrões ou relações entre variáveis.

1. Gráfico de Pizza: Um gráfico de pizza (ou gráfico de setores) divide um círculo em fatias, onde cada fatia representa uma categoria e o tamanho da fatia representa a proporção ou a porcentagem dos valores. É usado para mostrar a distribuição proporcional de um conjunto de valores.

1. Gráfico de Dispersão: Um gráfico de dispersão exibe pontos de dados individuais em um plano cartesiano, onde cada ponto representa uma observação em relação a duas variáveis. É usado para visualizar a relação entre duas variáveis contínuas e identificar padrões ou correlações.

1. Gráfico de Histograma: Um histograma é um gráfico de barras usado para representar a distribuição de frequência de uma variável contínua. As barras do histograma representam intervalos de valores e a altura das barras representa a frequência ou a densidade desses valores.

1. Gráfico de Área: Um gráfico de área é semelhante a um gráfico de linhas, mas a área abaixo das linhas é preenchida, criando uma representação visual da magnitude dos valores. É usado para mostrar a tendência e a proporção dos valores ao longo do tempo.

1. Gráfico de Radar: Um gráfico de radar exibe valores em várias dimensões em relação a um ponto central, criando uma forma de "teia". É usado para comparar várias categorias ou grupos em várias métricas e identificar padrões ou pontos fortes/fracos em cada categoria.

1. Gráfico boxplot: é um tipo de gráfico que representa a distribuição estatística de um conjunto de dados. Ele é composto por uma caixa retangular que representa o intervalo interquartil (IQR), uma linha no meio da caixa que indica a mediana e linhas (chamadas de bigodes) que se estendem a partir da caixa para mostrar a amplitude dos dados. O boxplot é útil para identificar a dispersão, a simetria e a presença de valores discrepantes em um conjunto de dados.

Esses são apenas alguns exemplos dos tipos de gráficos mais comuns. A escolha do gráfico adequado dependerá do tipo de dados, da finalidade da visualização e da mensagem que se deseja transmitir. É importante selecionar o tipo de gráfico que melhor representa os dados de maneira clara e compreensível.

## Medidas
As medidas de posição e dispersão são utilizadas na estatística para resumir e descrever conjuntos de dados. Elas fornecem informações sobre a localização central dos dados (posição) e a dispersão ou variabilidade dos valores (dispersão). Aqui estão algumas das principais medidas de posição e dispersão:

### Medidas de posição

1. Média: A média aritmética é a medida de posição mais comum. É calculada somando todos os valores e dividindo pelo número total de observações. A média é sensível a valores extremos.

2. Mediana: A mediana é o valor central em um conjunto de dados quando eles estão organizados em ordem crescente ou decrescente. Ela divide o conjunto de dados ao meio, com metade dos valores acima e metade abaixo.

3. Moda: A moda é o valor ou valores que ocorrem com mais frequência em um conjunto de dados. Pode haver uma moda (unimodal), duas modas (bimodal) ou mais.

4. Quartis: Os quartis dividem um conjunto de dados em quatro partes iguais. O primeiro quartil (Q1) é o valor abaixo do qual 25% dos dados estão localizados, o segundo quartil (Q2) é a mediana e o terceiro quartil (Q3) é o valor abaixo do qual 75% dos dados estão localizados.

### Medidas de disperção

1. Amplitude: A amplitude é a diferença entre o maior e o menor valor em um conjunto de dados. Ela fornece uma ideia geral da variação total dos dados, mas pode ser influenciada por valores extremos.

2. Variância: A variância é uma medida de dispersão que mede o quão longe os valores individuais estão da média. É calculada como a média dos quadrados das diferenças entre cada valor e a média.

3. Desvio Padrão: O desvio padrão é a raiz quadrada da variância. Ele expressa a dispersão dos valores em termos da mesma unidade que os dados originais. O desvio padrão é amplamente utilizado e fornece uma medida da variabilidade em torno da média.

## Análise de dados bidimensional 

A análise de dados bidimensional envolve o estudo da relação entre duas variáveis em um conjunto de dados. Ela busca compreender a associação ou dependência entre as variáveis e identificar padrões ou tendências. A análise bidimensional pode ser realizada por meio de gráficos, tabelas e cálculo de medidas de associação, como o coeficiente de correlação.

1. Correlação Linear Positiva: Refere-se a uma relação entre duas variáveis em que elas têm uma tendência a aumentar juntas. Isso significa que, à medida que os valores de uma variável aumentam, os valores da outra variável também aumentam. Na correlação linear positiva, o coeficiente de correlação (como o coeficiente de correlação de Pearson) terá um valor próximo de +1. Um exemplo disso pode ser a relação entre a quantidade de horas estudadas e as notas dos alunos, onde mais horas de estudo geralmente estão associadas a notas mais altas.

2. Correlação Linear Negativa: É o oposto da correlação linear positiva. Refere-se a uma relação entre duas variáveis em que elas têm uma tendência a se mover em direções opostas. Isso significa que, à medida que os valores de uma variável aumentam, os valores da outra variável diminuem. O coeficiente de correlação (como o coeficiente de correlação de Pearson) terá um valor próximo de -1. Um exemplo disso pode ser a relação entre o número de horas de sono e o nível de fadiga, onde mais horas de sono estão associadas a um nível menor de fadiga.

3. Correlação Não Linear: Refere-se a uma relação entre duas variáveis que não pode ser descrita por uma linha reta. Nesse caso, a relação entre as variáveis pode ser curvilínea ou seguir um padrão diferente de crescimento ou decrescimento. A correlação não linear pode ser positiva (quando as variáveis aumentam juntas, mas não em uma taxa constante) ou negativa (quando as variáveis diminuem juntas, mas não em uma taxa constante). Nesses casos, os coeficientes de correlação linear podem não capturar adequadamente a relação entre as variáveis, e outras medidas de associação, como coeficientes de correlação não linear, podem ser mais apropriadas.

4. Sem Correlação: Refere-se à ausência de uma relação linear entre duas variáveis. Nesse caso, os valores das variáveis não têm uma associação clara e não há uma tendência consistente de aumento ou diminuição à medida que os valores de uma variável mudam. O coeficiente de correlação (como o coeficiente de correlação de Pearson) terá um valor próximo de zero. No entanto, é importante ressaltar que mesmo quando não há uma correlação linear, ainda pode haver outras formas de relação entre as variáveis que não são capturadas pelo coeficiente de correlação linear.

## Coeficiente de correlação

O coeficiente de correlação é uma medida estatística que quantifica a força e a direção da relação linear entre duas variáveis. O coeficiente de correlação mais comumente utilizado é o coeficiente de correlação de Pearson, representado por r. Ele varia de -1 a +1, onde:

- r = +1 indica uma correlação positiva perfeita, ou seja, as variáveis se movem na mesma direção de forma linear.
- r = -1 indica uma correlação negativa perfeita, ou seja, as variáveis se movem em direções opostas de forma linear.
- r = 0 indica uma ausência de correlação linear, ou seja, as variáveis não estão linearmente relacionadas.

O coeficiente de correlação de Pearson é calculado com base nos desvios dos valores das duas variáveis em relação às suas médias. Um valor próximo de +1 ou -1 indica uma relação forte, enquanto um valor próximo de 0 indica uma relação fraca ou inexistente.

É importante ressaltar que o coeficiente de correlação de Pearson mede apenas a associação linear entre as variáveis. Portanto, ele não captura relações não lineares ou causais. Outros tipos de coeficientes de correlação, como o coeficiente de correlação de Spearman ou o coeficiente de correlação de Kendall, podem ser utilizados para avaliar associações não lineares ou ordinais, respectivamente.

### Formula

r = (Σ((X - X̄)(Y - Ŷ))) / sqrt(Σ((X - X̄)²) * Σ((Y - Ŷ)²))

Onde:

r é o coeficiente de correlação de Pearson.
X e Y são as variáveis em estudo.
X̄ é a média dos valores de X.
Ŷ é a média dos valores de Y.
Σ representa a soma, ou seja, somamos os resultados das operações para cada par de valores de X e Y.

## Regressão Linear Simples

A regressão linear simples é uma técnica estatística que busca estabelecer uma relação linear entre duas variáveis, conhecidas como variável dependente (Y) e variável independente (X). A ideia é encontrar uma linha reta que melhor represente a relação entre as variáveis, permitindo fazer previsões ou estimativas com base nos dados disponíveis.

A fórmula para a regressão linear simples, que estima o valor de Y com base no valor de X, é dada por:

### Fórmula

#### Equação da regressão linear
Y = β₀ + β₁X

Onde:

- Y é a variável dependente (variável a ser prevista ou estimada).
- X é a variável independente (variável usada para prever ou estimar Y).
- β₀ é o coeficiente de linear, que representa o valor de Y quando X é igual a zero.
- β₁ é o coeficiente de angular, que representa a mudança esperada em Y para cada unidade de mudança em X.

#### Equação coeficiente linear
β₀ = Ȳ - β₁X̄

Onde:

- Ȳ é a média dos valores de Y.
- X̄ é a média dos valores de X.

#### Equação coeficiente angular
β₁ = Σ((X - X̄)(Y - Ȳ)) / Σ((X - X̄)²)

Onde:

- X e Y são os valores das variáveis independentes e dependentes, respectivamente.
- X̄ é a média dos valores de X.
- Ȳ é a média dos valores de Y.
- Σ representa a soma dos resultados das operações para cada par de valores de X e Y.

Uma vez encontrados os coeficientes, a equação de regressão linear simples pode ser usada para fazer previsões ou estimativas de Y com base em diferentes valores de X.

É importante ressaltar que a regressão linear simples pressupõe uma relação linear entre as variáveis e que existem outras formas de regressão, como a regressão polinomial ou regressão múltipla, que podem lidar com relações não lineares ou com mais de uma variável independente.

## Coeficiente de determinação

O coeficiente de determinação, também conhecido como R², é uma medida estatística que indica a proporção da variabilidade da variável dependente (Y) que pode ser explicada pela regressão linear em relação à variável independente (X). Em outras palavras, o coeficiente de determinação mede o quão bem a reta de regressão se ajusta aos dados.

A fórmula correta para o coeficiente de determinação é:

R² = r²

Onde:

- R² é o coeficiente de determinação.
- r é o coeficiente de correlação de Pearson.

Essa fórmula indica que o coeficiente de determinação é obtido ao elevar ao quadrado o coeficiente de correlação entre as variáveis. O valor de R² varia entre 0 e 1, representando a proporção da variabilidade de Y que pode ser explicada pela relação linear com X.

Um valor de R² próximo a 1 indica que a regressão linear explica uma grande proporção da variabilidade de Y, ou seja, os pontos estão próximos da reta de regressão. Um valor de R² próximo a 0 indica que a regressão linear explica uma pequena proporção da variabilidade de Y, ou seja, os pontos estão espalhados e a reta de regressão não é um bom ajuste.

Portanto, o coeficiente de determinação é uma medida que quantifica a qualidade do ajuste da regressão linear simples e a quantidade de variabilidade de Y explicada pela relação linear com X.

## Probabilidade

A probabilidade é uma área fundamental da estatística que estuda as chances ou a incerteza associada a eventos. Na estatística, a probabilidade é usada para medir a possibilidade de ocorrência de um determinado evento em um conjunto de eventos possíveis.

A probabilidade é geralmente expressa como um número entre 0 e 1, onde 0 indica impossibilidade absoluta do evento ocorrer e 1 indica certeza absoluta de que o evento ocorrerá. Valores entre 0 e 1 representam graus de possibilidade ou chance.

Existem dois tipos principais de probabilidade na estatística:

1. Probabilidade teórica: É baseada em princípios teóricos, como a teoria da probabilidade e a teoria dos conjuntos. Ela é usada quando todas as possíveis ocorrências são conhecidas e podem ser enumeradas. A probabilidade teórica é frequentemente usada em experimentos controlados, como lançamento de dados ou cartas de baralho.

2. Probabilidade empírica: Também conhecida como probabilidade experimental, é baseada na observação de dados reais. Ela é usada quando não é possível determinar todas as possíveis ocorrências de um evento. A probabilidade empírica é obtida coletando dados e analisando sua frequência relativa. Essa abordagem é comumente usada em pesquisas de opinião, estudos de mercado e amostragens.

A probabilidade é amplamente aplicada na estatística para fazer previsões, tomar decisões informadas, analisar riscos e incertezas, além de modelar e compreender eventos aleatórios. Ela desempenha um papel fundamental na interpretação de resultados estatísticos e na tomada de conclusões baseadas em dados.

### Espaço amostral

Na teoria da probabilidade, o espaço amostral é o conjunto de todos os resultados possíveis de um experimento ou evento aleatório. Ele é denotado por Ω e representa todas as possibilidades distintas que podem ocorrer.

A compreensão do espaço amostral e dos eventos é fundamental para o cálculo de probabilidades e para a análise de eventos aleatórios. Esses conceitos são utilizados para modelar e prever a ocorrência de eventos em diversas áreas, como estatística, ciências naturais, finanças e jogos de azar.

Por exemplo, se lançarmos um dado, o espaço amostral consiste nos números de 1 a 6, pois esses são os possíveis resultados do lançamento.

### Eventos

Um evento é um subconjunto do espaço amostral. Ele representa um conjunto de resultados específicos dentro do espaço amostral. Os eventos podem ser classificados em três tipos:

#### Tipos de eventos

##### Evento simples

Consiste em um único resultado específico. Por exemplo, no lançamento de um dado, o evento "obter um 3" é um evento simples.

##### Evento composto

Consiste em dois ou mais resultados. Por exemplo, no lançamento de um dado, o evento "obter um número par" é um evento composto, pois inclui os resultados 2, 4 e 6.

##### Evento impossível

Também conhecido como evento vazio, é um evento que não contém nenhum resultado do espaço amostral. Por exemplo, no lançamento de um dado, o evento "obter um 7" é um evento impossível, pois não há resultado possível nesse caso.

##### Evento certo

É o evento que abrange todo o espaço amostral, ou seja, ocorre sempre. Por exemplo, no lançamento de um dado, o evento "obter qualquer número de 1 a 6" é um evento certo.

#### Operações entre eventos

Os eventos podem ser representados por conjuntos, e a teoria dos conjuntos é amplamente utilizada para descrever as relações entre os eventos. A probabilidade de um evento é uma medida numérica que indica a chance de o evento ocorrer, variando de 0 a 1. A soma das probabilidades de todos os eventos possíveis no espaço amostral é igual a 1.

As operações entre eventos na teoria da probabilidade têm propriedades específicas que nos ajudam a entender e manipular conjuntos de resultados. As principais propriedades das operações entre eventos são:

1. Lei do evento certo e impossível:

    - P(Ω) = 1
    - P(Ø) = 0
2. Complementar:

    - P(A') = 1 - P(A)
3. União:

    - P(A ∪ B) = P(A) + P(B) - P(A ∩ B)
4. Interseção (para eventos independentes):

    - P(A ∩ B) = P(A) * P(B)
5. Diferença:

    - P(A - B) = P(A) - P(A ∩ B)
6. Regra da distribuição:

    - P(A ∪ B ∪ C) = P(A) + P(B) + P(C) - P(A ∩ B) - P(A ∩ C) - P(B ∩ C) + P(A ∩ B ∩ C)
7. Probabilidade condicional:

    - P(A | B) = P(A ∩ B) / P(B)
8. Regra do produto (para eventos dependentes):

    - P(A ∩ B) = P(A) * P(B | A)
9. Regra de Bayes:

    - P(A | B) = (P(B | A) * P(A)) / P(B)
10. Complementar de uma interseção:

    - (A ∩ B)' = A' ∪ B'
11. Complementar da união:

    - (A ∪ B)' = A' ∩ B'
12. Lei de De Morgan:

    - (A ∪ B)' = A' ∩ B'
    - (A ∩ B)' = A' ∪ B'
13. Eventos mutuamente exclusivos:

    - P(A ∩ B) = 0 (não podem ocorrer simultaneamente)
14. Eventos exaustivos:

    - A₁ ∪ A₂ ∪ ... ∪ Aₙ = Ω (cobrem todos os resultados possíveis)

Essas propriedades são úteis na manipulação e cálculo de probabilidades de eventos em situações complexas. Elas nos permitem determinar a probabilidade de eventos combinados e relacionados, bem como calcular probabilidades condicionais e outras quantidades estatísticas importantes.

## Análise combinatória

Análise combinatória é um ramo da matemática que estuda a contagem e organização de diferentes possibilidades ou arranjos que podem ser formados a partir de um conjunto de elementos. Ela é aplicada em situações em que precisamos contar, agrupar ou selecionar elementos de forma específica, sem necessariamente analisar sua ordem.

Existem várias técnicas e conceitos na análise combinatória. Alguns dos principais são:

1. Princípio fundamental da contagem: É utilizado para contar o número de resultados possíveis em uma sequência de eventos independentes. Se um evento A pode ocorrer de m maneiras diferentes e um evento B pode ocorrer de n maneiras diferentes, então o número total de resultados possíveis é dado por m x n.

2. Permutações: São arranjos ordenados de elementos. O número de permutações de n elementos distintos tomados k de cada vez é dado por P(n, k) = n! / (n - k)!, onde n! representa o fatorial de n.

3. Combinações: São agrupamentos não ordenados de elementos. O número de combinações de n elementos distintos tomados k de cada vez é dado por C(n, k) = n! / (k! * (n - k)!).

4. Arranjos: São arranjos ordenados de elementos, mas considerando apenas um subconjunto deles. O número de arranjos de n elementos distintos tomados k de cada vez é dado por A(n, k) = n! / (n - k)!.

5. Binômio de Newton: É uma fórmula utilizada para calcular o desenvolvimento de um binômio elevado a um determinado expoente. A fórmula é dada por (a + b)^n = C(n, 0) * a^n * b^0 + C(n, 1) * a^(n-1) * b^1 + ... + C(n, n) * a^0 * b^n.

Esses são apenas alguns dos conceitos básicos da análise combinatória. Essa área da matemática é amplamente utilizada em problemas de contagem, probabilidades, estatística, teoria dos jogos e outras aplicações que envolvem a análise e a contagem de diferentes possibilidades.

## Probabilidade total, parcial e Teorema de Bayes

Probabilidade total, probabilidade parcial e o Teorema de Bayes são conceitos fundamentais da teoria da probabilidade que envolvem a relação entre eventos e suas probabilidades condicionais. Vamos entender cada um deles:

### Probabilidade Total

A probabilidade total é usada para calcular a probabilidade de um evento ocorrer, levando em consideração diferentes cenários ou condições possíveis. Suponha que existam eventos independentes e exaustivos A₁, A₂, ..., Aₙ que cobrem todas as possibilidades. A probabilidade total de um evento B ocorrer é dada pela fórmula:

P(B) = P(B | A₁) * P(A₁) + P(B | A₂) * P(A₂) + ... + P(B | Aₙ) * P(Aₙ)

Ou seja, a probabilidade de B ocorrer é a soma das probabilidades de B ocorrer em cada cenário A₁, A₂, ..., Aₙ, ponderadas pelas probabilidades desses cenários ocorrerem.

### Probabilidade Parcial

A probabilidade parcial é usada para calcular a probabilidade de um evento ocorrer em um subconjunto específico dos cenários possíveis. Seja C um subconjunto dos eventos A₁, A₂, ..., Aₙ. A probabilidade parcial de um evento B ocorrer em relação ao subconjunto C é dada pela fórmula:

P(B | C) = P(B ∩ C) / P(C)

Ou seja, a probabilidade de B ocorrer dado que o evento C ocorreu é a probabilidade da interseção entre B e C dividida pela probabilidade de C ocorrer.

### Teorema de Bayes

O Teorema de Bayes é uma ferramenta poderosa para atualizar probabilidades com base em novas informações. Ele relaciona as probabilidades condicionais de dois eventos, permitindo que se calcule a probabilidade inversa de um evento dado que o outro ocorreu. O Teorema de Bayes é expresso pela fórmula:

P(A | B) = (P(B | A) * P(A)) / P(B)

Essa fórmula nos permite calcular a probabilidade de um evento A ocorrer dado que o evento B ocorreu, usando as probabilidades condicionais P(B | A) e P(A) e a probabilidade total P(B).

Esses conceitos são fundamentais para entender a relação entre eventos e probabilidades condicionais na teoria da probabilidade, permitindo calcular probabilidades em diferentes cenários e atualizar probabilidades com base em informações adicionais.

















