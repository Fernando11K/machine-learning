# Projeto Trabalhando com Machine Learning na Prática no Azure ML

## Modelo de Previsão - Dupla Sena

Este projeto tem como objetivo construir um modelo de previsão utilizando Machine Learning para prever os próximos números da Dupla Sena, um jogo da Loterias Caixa. O modelo será desenvolvido utilizando o Azure Machine Learning, uma plataforma de Machine Learning baseada em nuvem fornecida pela Microsoft.

## Etapas do Projeto:

1. **Coleta de Dados:**
   - Os dados históricos da Dupla Sena serão coletados do site da Loterias Caixa, onde a própria disponibiliza uma planilha dos últimos resultados para download.

2. **Pré-processamento de Dados:**
   - Serão removidas as colunas irrelevantes, mantendo apenas a data do sorteio e os números sorteados no primeiro e segundo sorteios.

3. **Criação do Workspace do Azure Machine Learning:**
   - Será necessário criar um workspace no Azure Machine Learning para o desenvolvimento do projeto.

4. **Configuração dos Modelos e Conjunto de Dados:**
   - Após a criação do workspace, será necessário configurar os modelos e conjuntos de dados. Será utilizado o ML automatizado, onde o campo "Nome do Trabalho" será preenchido com "mslearn-dupla-sena-auto" e o campo "Nome do Experimento" com o mesmo nome anterior. Na descrição, preencher "Aprendizado de máquina automatizado para previsão de números da dupla sena" e selecionar o tipo de tarefa como regressão.



## Ferramentas Utilizadas:

- Azure Machine Learning: Para desenvolvimento, treinamento e implantação do modelo.


## Autor:

Este projeto está sendo desenvolvido por [Fernando11000](https://github.com/Fernando11K/) , como parte do curso "Trabalhando com Machine Learning na Prática no Azure ML" da  [Digital Innovation One (DIO)](https://www.dio.me/).

## Observação:

Este projeto é apenas para fins educacionais e de demonstração. Os resultados de previsão da Dupla Sena não devem ser utilizados para jogos de azar reais. Lembre-se de fazer o upload do arquivo "Dupla Sena.csv" no store do blob, etc.
