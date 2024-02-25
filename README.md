<img src="https://hermes.dio.me/lab_projects/badges/87d332d0-5198-4a2f-b159-38c8c2976954.png" alt="Trabalhando com Machine Learning" width="200">


# Estudo sobre Machine Learning Automatizado no Azure Machine Learning ⚙️


Neste exercício, exploraremos o recurso de aprendizado de máquina automatizado no Azure Machine Learning para treinar e avaliar um modelo de aprendizado de máquina. Em seguida, implantaremos e testaremos o modelo treinado.

Este exercício deve levar aproximadamente 30 minutos para ser concluído.

## Criar um espaço de trabalho do Azure Machine Learning

Para utilizar o Azure Machine Learning, é necessário aprovisionar um espaço de trabalho do Azure Machine Learning na sua subscrição do Azure. Depois, você poderá usar o estúdio Azure Machine Learning para trabalhar com os recursos do seu workspace.

1. **Entre no portal do Azure:** Acesse [https://portal.azure.com](https://portal.azure.com) utilizando suas credenciais da Microsoft.

2. **Crie um recurso do Azure Machine Learning:**
   - Selecione + Criar um recurso e pesquise por "Machine Learning".
   - Crie um novo recurso do Azure Machine Learning com as configurações adequadas.

3. **Acesse o Azure Machine Learning Studio:** Após criar o recurso, selecione "Launch Studio" para acessar o Azure Machine Learning Studio.

## Use aprendizado de máquina automatizado para treinar um modelo

O aprendizado de máquina automatizado permite que você experimente vários algoritmos e parâmetros para treinar vários modelos e identificar o melhor para seus dados. Neste exercício, usaremos um conjunto de dados de detalhes históricos de aluguel de bicicletas para treinar um modelo que prevê o número de aluguel de bicicletas esperado em um determinado dia, com base em características sazonais e meteorológicas.

- **Citação:** Os dados usados neste exercício são derivados da Capital Bikeshare e são usados de acordo com o contrato de licença de dados publicado.

Para o passo a passo detalhado deste processo, consulte o [arquivo tutorial.md](tutorial.md).

## Detalhes do Tutorial

O tutorial cria um modelo de previsão com seus devidos pontos de extremidade configurados para obter um resultado em JSON. Ele inclui os seguintes passos:

1. **Crie um espaço de trabalho do Azure Machine Learning:** Provisão de um espaço de trabalho do Azure Machine Learning no portal do Azure.
   
2. **Use aprendizado de máquina automatizado para treinar um modelo:** Crie um novo trabalho de ML automatizado no Azure Machine Learning Studio com as configurações adequadas e envie o trabalho de treinamento.

3. **Avalie o melhor modelo:** Revise o melhor modelo treinado pelo seu trabalho automatizado de aprendizado de máquina e teste o serviço implantado.

Para obter instruções detalhadas, consulte o [tutorial.md](tutorial.md).

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).
