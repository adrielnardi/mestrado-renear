##### Trabalho 01 - Comparação de Perceptron criterion com hinge-loss
##### Professor: Francisco de Assis Boldt
##### Disciplina: Redes Neurais Artificiais

Considere um dataset de 2 dimensões em que todos os pontos com x1 > x2 pertencem à classe positiva, e todos os pontos com x1 <= x2 pertencem à classe negativa. Assim, o separador entre as duas classes é um hiperplano linear definido por x1 - x2 = 0. Agora crie um dataset com 20 pontos aleatoriamente gerados dentro de uma unidade quadrada no quadrante positivo. Rotule cada ponto dependendo se x1 é maior do que x2, ou não.

1. Implemente o algoritmo perceptron sem regularização. Treino-o com os 20 pontos gerados, e teste sua acurácia com 1000 pontos gerados aleatoriamente dentro da unidade quadrada. Gere os pontos de teste usando o mesmo procedimento usado para gerar os dados de treino.
2. Mude o critério do perceptron para hinge-loss na sua implementação. Repita o treino e a estimativa de acurácia com os mesmo pontos do item anterior.
3. Em qual caso você obteve a melhor acurácia, e por quê?
4. Em qual caso você acha que a classificação dos mesmos 1000 pontos de teste não será significativamente diferente se o algoritmo for treinado com 20 pontos diferentes, também gerados aleatoriamente?

Coloque jupyter notebook com a tarefa em seu GitHub e envie o link.
