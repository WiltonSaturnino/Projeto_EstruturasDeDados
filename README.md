# Projeto_EstruturasDeDados
Projeto desenvolvido na disciplina de Estutura de Dados da Universidade UEPB



Atualmente existem vários datasets que disponibilizam os dados gerais sobre a situação da COVID-19 para várias cidades do Brasil. Entre eles, podemos destacar o Brasil.IO (Links para um site externo.) . Neste site são disponibilizados vários datasets, entre eles um painel da situação atual da COVID-19 para todas as cidades. Os dados podem ser adiquiridos diretamente através do link (Links para um site externo.).

Neste contexto, o primeiro projeto da disciplina de Estrutura de dados visa utilizar os dados da COVID-19 do Brasil.IO para estudarmos o desempenho dos algoritmos de ordenação.

O projeto consiste das seguintes fases:

Preparação do dataset > O dataset (Links para um site externo.) (link (Links para um site externo.) para descrição do dataset) compreende um registro histórico de ocorrência de COVID-19 para todas as cidades e estados do Brasil.
Você deve baixar a planilha localmente para poder processá-la no seu código Java. Atenção, quando descompacta se torna algo bem maior.
Você deve tratar apenas com os dados mais atuais (tem um campo chamado "É a última atualização?" ou "is_last" que deve eestar marcado como True). Valores antigos não interessam
Você deve utilizar apenas dados não repetidos( existe um campo que indica isso "Dado repetido?")
Gerar um arquivo formatado para ser processado na próxima fase
Análise dos algoritmos de ordenação
Implemente e utilize todos os algoritmos de ordenação estudados (Selection Sort, Insertion Sort, Merge Sort, Quick Sort, QuickSort com Mediana de 3, counting, e HeapSort) para ordenar os registros de acordo com os seguintes parâmetros:
Ordenação crescente por quantidade acumulada de óbitos;
Ordenação crescente por quantidade acumulada de casos;
Ordenação crescente por ordem alfabética pelo nome das cidades.
Cada arquivo de saída de ordenação deve ser gerado com base no método de ordenação e no elemento ordenado. Por exemplo, para o quick sort devem ser gerado 3 arquivos: qSort_ordena_obitos.csv e qSort_ordena_casos.csv, qSort_ordena_cidades.csv. Isso deve continuar para cada um dos métodos de ordenação.
Para cada algoritmo, registre o tempo necessário para ordenar o vetor de senhas (em milissegundos).
Elabore uma tabela para comparar o tempo de execução dos algoritmos.
Opcional: Para a elaboração dos comparativos devem ser usados ferramentas de code profiling, como por exemplo o https://visualvm.github.io/ (Links para um site externo.). Elabore gráficos mostrando o consumo de tempo e memória quando da execução do algoritmo.

Entrega deste milestone:

Entrega de um relatório descrevendo os casos de testes, ambiente de execução completo e análise comparativa dos algoritmos.
Você deve subir o projeto no GitHub e mandar o link do projeto e o link de uma versão para eu baixar no meu computador e executar com todas as instruções (arquivo readme).

Instruções:

Executar: 

Ao rodar o programa será gerado arquivos filtrados pelos algoritmos de maneira que será eles serão os resultados do aruivos brutos tratados. 
Ao final tem-se um arquivo em texto que contém o comparativo de tempo entre os algoritmos de ordenação dos diferentes casos de complexidade
(Melhor, Pior e médio caso). Estes dados são direcionados ao excel para que os gráficos sejam plotados. 
Você deve adicionar a pasta chamada CovidAnalyser, insira o arquivo caso.csv na pasta de dadosbrutos, você pode achá-la seguindo esta estrutura CovidAnalyser > data > dadosbrutos.   
