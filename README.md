# Analisando os dados do Meio Circulante - out/2022

**Meio Circulante** é a soma do total de cédulas e moedas em circulação em um país, que está em posse do público e dos bancos. Inclui aquelas com poder liberatório (inclusive comemorativas).

Diariamente, são feitas movimentações que alteram a  quantidade e composição do numerário em circulação. O presente notebook faz uma análise exploratória de dados fornecidos pelo Banco Central, que tem por objetivo apresentar as quantidades diárias por Valor da Denominação e Família (espécie e categoria). O arquivo CSV contendo os dados possui as seguintes colunas:

- **Data**: formato ano-mês-dia - indica a data a que se refere o registro de quantidade daquela denominação e família;
- **Família**: Agrupamento da espécie (cédulas, moedas e peças comuns e comemorativas) e característica da espécie;
- **Denominação**: valor do numerário; 
- **Quantidade**: montante em circulação.

Os dados foram obtidos [aqui](https://dados.gov.br/dataset/dinheiro-em-circulacao) e baixados em outubro de 2022.



**Obs: Futuramente este conjunto de dados será descontinuado. Um novo conjunto de dados foi criado para substituí-lo:**  https://dadosabertos.bcb.gov.br/dataset/dinheiro-em-circulao
