# SVM (Support Vector Machine)

## O que é SVM?
É um algoritmo de aprendizado de máquina supervisionado que pode ser usado para desafios de classificação ou regressão. Seu foco maior é no treinamento e classificação de um dataset. Também pode ser usada na detecção de outliers.

Nesse algoritmo, plotamos cada item de dados como um ponto no espaço n-dimensional (onde n é o número de recursos que você tem), com o valor de cada
recurso sendo o valor de uma determinada coordenada. Então, nós executamos a classificação encontrando o hiperplano que melhor diferencia as duas classes.

<img src='https://hands-on.cloud/wp-content/uploads/2021/12/Overview-of-supervised-learning-SVM.png' width=450></img>

## Vantagens do SVM
- Eficaz em espaços de alta dimensão.
- Ainda eficaz nos casos em que o número de dimensões é maior que o número de amostras.
- Usa um subconjunto de pontos de treinamento na função de decisão (chamados vetores de suporte), portanto, também é eficiente em termos de memória.

## As desvantagens do SVM
- Se o número de recursos for muito maior que o número de amostras, evite o overfitting na escolha das [funções do Kernel](https://scikit-learn.org/stable/modules/svm.html#svm-kernels) e o termo de regularização é crucial.
- Os SVMs não fornecem estimativas de probabilidade diretamente, elas são calculadas usando a técnica expensive five-fold cross-validation.

[Documentação SVM](https://scikit-learn.org/stable/modules/svm.html)

A base de dados usada pode ser encontrada no repositório de [Pre-Processamento](https://github.com/Gregory-JP/Pre-Processamento).
