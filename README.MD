# DATA SCIENCE
> K-Nearest Neighbors (KNN)  - Modelos Supervisionados 06

![preview](/Knn.png)

### Projeto construido para complementar meu portifólio de projetos em Data Science!  

Neste projeto de machine learning foi utilizado o algoritmo K-Nearest Neighbors (KNN), aplicado ao clássico dataset Iris. Esse conjunto de dados contém informações sobre três espécies de flores – Setosa, Versicolor e Virginica – com quatro características físicas: comprimento e largura de pétalas e sépalas. O objetivo do projeto foi criar um modelo capaz de classificar corretamente a espécie de cada flor com base nessas características. Comecei explorando os dados e visualizando as relações entre as variáveis, o que ajudou a entender como as diferentes espécies se distinguem entre si. Depois, realizei o pré-processamento dos dados, normalizando as variáveis para garantir que a escala não afetasse a performance do modelo.

Apesar de ser um algoritmo poderoso em muitas aplicações de classificação, o K-Nearest Neighbors (KNN) tem algumas limitações importantes. Uma das principais desvantagens é sua sensibilidade ao volume de dados, pois sua eficiência diminui à medida que o tamanho do conjunto de dados aumenta, já que o KNN precisa calcular a distância de cada novo ponto em relação a todos os pontos de treinamento. Além disso, ele é sensível à presença de ruído e outliers, já que pontos isolados podem influenciar negativamente as classificações. Outro ponto crítico é a necessidade de normalização dos dados, uma vez que o KNN se baseia na distância euclidiana, o que significa que variáveis em escalas diferentes podem distorcer os resultados.

Apesar dessas limitações, o KNN também pode ser utilizado de forma criativa, como no tratamento de valores faltantes em um conjunto de dados. Quando faltam valores em determinadas variáveis, o KNN pode ser aplicado para encontrar as observações mais próximas com base nas outras variáveis conhecidas e, a partir dessas observações vizinhas, substituir os valores ausentes com a média, mediana ou moda dessas observações. Esse método é particularmente útil quando a ausência de dados não é aleatória e existe uma relação clara entre as variáveis disponíveis e os dados que estão faltando, aproveitando a simplicidade e flexibilidade do algoritmo para a imputação de valores faltantes.



## 🔧 Tecnologias 🔧

- pandas 
- matplotlib.pyplot 
- seaborn 
- sklearn
    - K-Nearest Neighbors (KNN)
    - Metrics 
    - Train test split

## ❤️ Contato ❤️
 
- Email: Rafaelssm7@gmail.com
- LinkedIN: https://www.linkedin.com/in/rssms/