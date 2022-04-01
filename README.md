# roB3rta
Qualificação submetida ao Programa de Engenharia Elétrica da Universidade Federal do Maranhão para a obtenção do título de Doutor em Engenharia Elétrica.

```BrInvesting_WebScraper.ipynb```: Notebook para extração das headlines do site BrInvesting.com

```Evaluation_Dataset_Generation.ipynb```: Notebook para geração do dataset formado pela combinação dos datasets SemEval 2017 Task 5 - Subtask 2, FiQA e FinancialPhraseBank.

```FastText_RNN.ipynb```: Notebook com análise de sentimentos performada por redes neurais recorrentes (LSTM e GRU) usado o word embedding FastText.

```FinText_RNN.ipynb```: Notebook com análise de sentimentos performada por redes neurais recorrentes (LSTM e GRU) usado o word embedding FinText.

```FinalDataset_Classificator.ipynb```: Notebook para geração do dataset a ser usado para a comparação do RoB3RTa com outros modelos pré-treinados em língua portuguesa.

```FinalDataset_SentenceAndWordCount.ipynb```: Notebook para aferição de média de tamanho e número de palavras por headline do dataset a ser usado para a comparação do RoB3RTa com outros modelos pré-treinados em língua portuguesa.

```GloVe_RNN.ipynb```: Notebook com análise de sentimentos performada por redes neurais recorrentes (LSTM e GRU) usado o word embedding GloVe.

```MergerTwitterFiles.ipynb```: Notebook para junção de todos os tweets extraídos de usuários e hashtags especificados no trabalho, com posterior filtragem (todas as menções são trocadas pela expressão ```@USER``` e todas as URLs são trocadas pela expressão ```HTTPURL```).

```RoB3RTa_Training.ipynb```: Notebook do treinamento do RoB3RTa com o corpus resultante da junção dos tweets com os textos da Leipzig Corpora Collection.

 ```Sentence_Histogram.ipynb```: Notebook para geração dos histogramas com a distribuição do número de palavras e caracteres nas manchetes do dataset

```TransformerModels_TrainTest.ipynb```: Notebook do treinamento e cross-validation dos modelos baseados na arquitetura Transformer.

```TwitterUserAndHashtag_Downloader.ipynb```: Notebook para extração dos tweets de uma determinada hashtag ou conta no Twitter.

```Word2Vec_RNN.ipynb```: Notebook com análise de sentimentos performada por redes neurais recorrentes (LSTM e GRU) usado o word embedding FastText.
