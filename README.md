#### PT/BR
# Trabalho de Conclusão de Curso - Engenharia Mecânica UFMG

Trabalho realizado com o objetivo de avaliar e comparar o desempenho de três mecanismos de busca: Pesquisa em Largura, Algoritmo de Dijkstra e Algoritmo A*. O estudo utilizou a representação do mapa da Região Central de Belo Horizonte em grafos, onde as ruas são arestas, os comprimentos das ruas representam os pesos das arestas e os cruzamentos das ruas formam os nós. Foi utilizada a notação Big O para auxiliar na análise do tempo de execução.

## Objeto de Estudo

Os mecanismos de busca foram aplicados no mapa da cidade de Belo Horizonte, representado por grafos. Nesse mapa, foram marcadas todas as Drogarias Araújo em suas respectivas localizações nos nós dos grafos.

Feito isso, os modelos foram executados de forma a determinar, para cada nó do grafo completo (ou seja, para cada localização no mapa de BH), qual era a Drogaria Araújo mais próxima desse ponto e qual a distância necessária para chegar até ela.

O tempo necessário para encontrar as drogarias mais próximas de cada ponto da cidade foi registrado, e isso foi testado no modelo em várias escalas, para verificar como o tempo de execução aumentava à medida que o número de nós crescia.

### Conceitos utilizados:
- Algoritmos de Pesquisa
- Pesquisa em Largura
- Dijkstra
- A* (A estrela)
- Big O
- Grafos
- Web Scraping

### Ferramentas utilizadas
- Python
- QGIS
- OpenStreetMap
- Matplotlib
- Pandas/Numpy

## Resultados

Link da apresentação: https://docs.google.com/presentation/d/1sucBi9_i33S0cbvXDI8fA2kKA7T1pq20/edit?usp=sharing&ouid=112530819681451686565&rtpof=true&sd=true

O tempo de execução de cada modelo foi registrado no gráfico abaixo, que representa o tempo no eixo y e o número de nós no modelo no eixo x. Cada série representa um modelo.

![results](https://github.com/vfernandes7/TCC/blob/main/Desempenho%20Mecanismos%20de%20Busca.jpg)

O estudo permitiu também a criação do seguinte gráfico do mapa da cidade de Belo Horizonte, registrando a distância necessária para alcançar a Drogaria Araújo mais próxima de cada ponto da cidade.

![map](https://github.com/vfernandes7/TCC/blob/main/Mapa%20BH%20-%20Drogarias%20Araujo.jpg)

---

#### EN
# Final Paper - Mechanical Engineering, UFMG

This project aims to evaluate and compare the performance of three search algorithms: Breadth-First Search, Dijkstra's Algorithm, and A* Algorithm. The study used a graph representation of the Central Region of Belo Horizonte, where streets are edges, street lengths are edge weights, and intersections form the nodes. Big O notation was applied to support the analysis of execution time.

## Object of Study

The search algorithms were applied to a graph representation of the city of Belo Horizonte. In this map, all Drogaria Araújo locations were marked at their respective nodes.

Once marked, the models were executed to determine, for each node in the complete graph (i.e., for each location on the map of BH), which Drogaria Araújo was the closest to that point and the distance required to reach it.

The time required to find the closest drugstores from each point in the city was recorded, and the model was tested at various scales to observe how execution time increased as the number of nodes grew.

### Concepts Used:
- Search Algorithms
- Breadth-First Search
- Dijkstra's Algorithm
- A* (A star)
- Big O
- Graphs
- Web Scraping

### Tools Used
- Python
- QGIS
- OpenStreetMap
- Matplotlib
- Pandas/Numpy

## Results

Presentation link https://docs.google.com/presentation/d/1sucBi9_i33S0cbvXDI8fA2kKA7T1pq20/edit?usp=sharing&ouid=112530819681451686565&rtpof=true&sd=true

The execution time of each model was recorded in the graph below, where the y-axis represents time and the x-axis represents the number of nodes in the model. Each series represents a model.

![results](https://github.com/vfernandes7/TCC/blob/main/Desempenho%20Mecanismos%20de%20Busca.jpg)

The study also enabled the creation of the following map graph of the city of Belo Horizonte, showing the necessary distance to reach the nearest Drogaria Araújo from each point in the city.

![map](https://github.com/vfernandes7/TCC/blob/main/Mapa%20BH%20-%20Drogarias%20Araujo.jpg)
