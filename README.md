# covid_classification
**Rede Neural que utiliza chapas de raio X do pulmão para fazer a classificação entre Normal, Covid e Não Covid**
Os arquivos necessários para treinamento da rede podem ser obtidos a partir da base Kaggle. No código, necessário trocar os campos USERNAME e KEY para conseguir acesso a base.
O código foi otimizado para ser rodado em nuvem, como o Google Colab, fazendo uso da GPU gratuita com 12 GB de RAM T4, disponível ao alterar o ambiente de execução.

**Adendo**
É necessário inicializar o ambiente de execução como GPU, pois o treinamento da rede só é viabilizado pelo uso da mesma.
No caso de utilização em modo local, tenha certeza que sua GPU está sendo utilizada. Se não possuir uma GPU, é recomendável utilizar o código a partir do Google Colab.

O arquivo utiliza dois tipos de rede, uma baseada em tipo LeNet e outra que utiliza transfer learning a partir de um modelo pré-treinado, do tipo ResNet.

