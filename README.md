# Previsão de Aluguel de Bicicletas com Azure Machine Learning
Este repositório contém um projeto de previsão de aluguel de bicicletas utilizando Azure Machine Learning. O modelo foi criado utilizando a funcionalidade AutoML do Azure.

![BicycleMarketGIF](https://github.com/Camilly-Alveess/Modelo_Previsao_Azure/assets/142948474/84d04cfb-af22-41c7-b1a7-cac19ee3ade8)

<details>
  <summary class="details-summary"><b>Dataset</b></summary>
O dataset utilizado para este projeto é o daily-bike-share.csv, que contém dados diários sobre aluguel de bicicletas.
</details>
<details>
  <summary class="details-summary"><b>Pré-requisitos</b></summary>
Antes de começar, é necessário ter uma conta no Azure.
</details>
<details>
  <summary class="details-summary"><b>Passo a Passo</b></summary>
1. Criação do Ambiente no Azure Machine Learning:

* Acesso ao portal do Azure Machine Learning e criação de um novo ambiente de trabalho.
* Seleção do grupo de recursos e uma instância de computação.

2. Configuração do Experimento AutoML:

* Criação do experimento e opção AutoML.
* Escolha do dataset daily-bike-share.csv carregado como fonte de dados.
* Configuração as opções de treinamento, como métricas de avaliação e duração máxima, nesse caso, selecionei Erro Quadrático Médio (RMSE - Root Mean Squared Error), que é uma medida da diferença entre os valores observados e os valores previstos pelo modelo de regressão e, o tempo de duração de 15 minutos.
* Após a conclusão do experimento, avaliei os resultados obtidos, incluindo as métricas de desempenho do modelo treinado.
</details>
<details>
  <summary class="details-summary"><b>Contribuição</b></summary>
Contribuições são bem-vindas! Sinta-se à vontade para enviar pull requests para melhorar este projeto. =)
</details>

<link rel="stylesheet" type="text/css" href="styles.css">
