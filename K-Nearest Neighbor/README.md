# K-Nearest Neighbor (KNN)
É um dos muitos algoritmos (de aprendizagem supervisionada) usado no campo de data mining e machine learning, ele é um classificador onde o aprendizado é baseado “no quão similar” é um dado (um vetor) do outro. O treinamento é formado por vetores de n dimensões.

## Como ele funciona
1. Carregar os dados.
2. Inicializa K para o número escolhido de vizinhos.
3. Para cada exemplo nos dados: <br>
    3.1 Calcula a distância entre o exemplo de consulta e o exemplo atual dos dados. <br>
    3.2 Adiciona a distância e o índice do exemplo a uma coleção ordenada.
4. Classifica a coleção ordenada de distâncias e índices do menor para o maior (em ordem crescente) pelas distâncias.
5. Escolhe as primeiras K entradas da coleção ordenada.
6. Obtém os rótulos das K entradas selecionadas.
7. Se for regressão, retorna a média dos K rótulos.
8. Se for classificação, retorna o modo dos K rótulos.

Lembrando que há uma explicação mais detalhada na [documentação](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html).
