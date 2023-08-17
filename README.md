## Pensamento Analítico de Dados - Previsão de Demanda
Participantes: Amir Youssef, Alberto Lucas, Enzo Lemes, João Pedro Soares, Pedro Oliveira

**Projeto FMF:** parte de uma competição do Kaggle, cujo a pergunta que será respondida, o **ASK** é prever a quantidade total de produtos vendidos em cada loja para o conjunto de teste. O **GET**, os dados nescessários para responder a pergunta, são basicamente 6 arquivos CSV, contendo informações sobre as lojas, vendas, categorias de produtos e outros. O **EXPLORE**, a exploração dos dados para melhorar o entendimento e possibilitar a descobertas de novas features, foi realizada com gráficos de dispersão, analisando a relação entre volume, vendas e preços; analisando dados de forma dinâmica, mostrando uma têndencia de queda das vendas de intens unicos, e mostrando tambem para nós dois períodos com picos de vendas, que podem ser sazonais ou que houve alguma promoção; e outras diversas análises que podem ser feitas. O **MODEL**, a criação de modelos para fazermos a maquina preditiva, foi realizada com vária abordagens, algumas básicas como: média móvel suavizada (SMMA), ARIMA e Exponential Smoothing de Holt Winter; abordagens com aprendizado de máquina: XGBoost, CatBoost e H20 AML; e abordagens de aprendizado profundo: Keras, Fastai e Pytorch Forecasting; e por fim o **COMMUNICATE**, que é onde você comunica seus resultados, no projeto FMF não foi exposto de maneira clara.


**Projeto ORIGINAL:** Após todo grupo ter reunido e dabatido sobre o PROJETO FMF disponibilizado decidimos que seremos originais desde o início do projeto.
O **ASK** que iremos responder será: "Predição de preços de casas dos EUA**. o **GET** será 2 arquivos CSV"s, contendo informações internas (nº banheiros, quartos, andares),externas (rua, ano_construção, cidade) e o valor individual de cada casa. Ao obter os dados e de fato começarmos o **EXPLORE** foram removidas colunas "inúteis", mudança de nomes e substituídos alguns dados vazios no dataset. Após padronização e a Transformação das variáveis, foi possível analisar a tabela de correlação, juntamente com gráficos de dispersão, onde nota-se que o "tamanho em metros quadrados" de uma casa é a maior relação que se tem com o preço, junto com "nº de banheiros" e "vagas de garagem", ainda, apesar que as casas mais valiosas estão presentes nos anos 2000+, a média de preço não tem uma variação considerável ao longo dos anos 1870-2010. Após essas análises podemos começar o **MODEL**, utilizamos basicamente dois modelos: RandomForest e CatBoost, treinamos os modelos e ajustamos os hiperparâmetros dando no melhor caso uma probabilidade 82% no RandomForest e e uma probabilidade de 87% no CatBoost. Por fim nosso **COMMUNICATE** será uma apresentação sobre todo o processo na aula de pensamento analítico de dados.
