# ANALISE DE DADOS BANCARIOS PARA MARKETING

Esse projeto utiliza a base de dados disponível [aqui](https://archive.ics.uci.edu/ml/machine-learning-databases/00222/bank.zip). E a partir dele visa responder as seguintes perguntas:
1. Qual profissão tem mais tendência a fazer um empréstimo ? De qual tipo ?
2. Fazendo uma relação entre número de contatos e sucesso da campanha quais são os pontos relevantes a serem observados ?
3. Baseando-se nos resultados de adesão desta campanha qual o número médio e o máximo de ligações que você indica para otimizar a adesão ?
4. O resultado da campanha anterior tem relevância na campanha atual ?
5. Qual o fator determinante para que o banco exija um seguro de crédito ?
6. Quais são as características mais proeminentes de um cliente que possua empréstimo imobiliário ?


## INSTALAÇÃO
Para conseguir rodar a analise você deve ter instalados em sua maquina o seguinte:
1. Python 3
2. jupyter Notebook
3. As bibliotecas no arquivo [requirements](./requirements.txt).

## OBSERVAÇÕES
Não existe nenhuma informação na base que fale explicitamente sobre seguro de crédito ou inadimplência. Portanto irei utilizar a premissa de que clientes que não possuem crédito pré aprovado (utilizando a coluna `default` para isso) seriam em que o banco deveria exigir um seguro de crédito.
