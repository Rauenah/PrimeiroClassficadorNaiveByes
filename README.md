# PrimeiroClassficadorNaiveByes
Criar um classificador baseado no modelo probabilístico de 
Naive Bayes, ao usar a linguagem Python com o Jupyter Notebook e a biblioteca Sklearn.
Primeiramente, você entenderá o problema que será tratado na classificação para, então, 
entender o código Python gerado para criar o classificador. O problema em questão é para 
decidir quando as crianças devem brincar fora de casa a partir de duas características: o 
clima e a temperatura externa. Se está muito quente, não é aconselhável que elas brinquem 
na parte externa; se está fazendo sol, também não é recomendado, por conta dos raios UV, 
e assim por diante. A partir de alguns casos, foi construído um banco de dados contendo 
as características e a variável que armazena se as crianças devem ou não brincar na parte 
externa. 
O clima (variável weather) pode ser: Sol, Ensolarado ou Nublado (ensolarado é um meio 
termo  entre  o  sol  aberto  e  o  nublado).  A  temperatura  (variável  temp)  pode  ser:  Ameno,  
Gelado ou Quente. O resultado (variável play), também chamado de label, dirá se as crianças devem brincar do lado externo ou não.
Após realizar o pré-processamento dos dados e criar um vetor com as características clima 
e temperatura com seu valor associado de resultado é possível iniciar o treinamento do 
classificador. Em seguida, é possível usar o modelo criado para classificar novos dados de 
forma facilitada.
Na etapa de pré-processamento, você pode usar os números que desejar 
para representar as strings, mas deve tomar muito cuidado para não se 
confundir e interpretar os resultados de forma errada. Para evitar esse 
problema, use sempre números simples e que representem de forma 
clara os valores associados.
