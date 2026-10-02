# AT1 - Perceptron e KNN

Atividade avaliativa da disciplina de Aprendizagem de Máquina (Fatec). O notebook implementa um Perceptron com treinamento automático, um classificador KNN e um recomendador por similaridade, tudo com NumPy.

## Como rodar

```
pip install numpy notebook
```

Depois:

```
git clone https://github.com/Yajoojj/at1-perceptron-knn.git
cd at1-perceptron-knn
jupyter notebook at1_am.ipynb
```
.

## Vídeo de apresentação

Link:[ https://youtu.be/eWxVWCAYgHM?si=UYoDlCBW7lQgDHuk](https://youtu.be/eWxVWCAYgHM)

## Desafios

**1. Perceptron (fraude em transações)**
Treina um perceptron com a regra de Rosenblatt usando valor da transação e frequência de operações, e classifica duas transações novas como legítima ou suspeita.

**2. KNN (risco de churn)**
Classifica clientes em baixo ou alto risco de cancelamento com K=3, usando distância Euclidiana ou Manhattan e votação por maioria. Mostra a classe, os índices dos vizinhos e as distâncias.

**3. Recomendador de servidores cloud**
Recebe um perfil (vCPUs, RAM e SSD) e devolve os 2 servidores do catálogo mais próximos pela distância euclidiana, em forma de ranking.
