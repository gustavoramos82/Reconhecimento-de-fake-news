# Reconhecimento de Fake news

Neste projeto de nlp, a partir de um dataset do kaggle (que pode ser obtido [aqui](https://www.kaggle.com/datasets/ronikdedhia/fake-news)) vai ser aplicado tecnicas de machine learning para classificar se o texto é fake ou não, podendo ser através do titulo, ou do texto (que segundo está explicado no kaggle o text o está incompleto).

O dataset está bem balaceado, pelo que podemos ver no gráfico abaixo:

![image](https://user-images.githubusercontent.com/39843884/186402918-37f9b54b-3ae8-4767-b3e5-7a55efa4b701.png)

Depois de um pré processamento dos dados, não teve uma diferença muito significativa dos titulos para o texto, em que o que tiveram as melhores perfomace foram:

- Regressão logistica

![image](https://user-images.githubusercontent.com/39843884/186403267-0522e7ec-30e5-4877-842f-fa3f22edb170.png)

- Random Forest

![image](https://user-images.githubusercontent.com/39843884/186403408-0b95c0c5-3ee8-4e33-a885-2945b914e162.png)

- Extra tree

![image](https://user-images.githubusercontent.com/39843884/186403499-41fd382b-3e5a-417c-aef2-ae2f0314f3f0.png)

Podemos ver que a maioria dos modelos tiveram métrica acima de 90% mostrando a efetividade em reconhecer fake news, muito importante para os tempos atuais.
