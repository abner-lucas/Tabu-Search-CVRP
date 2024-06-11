# Pesquisa Tabu no Problema de Roteamento de Veículos (CVRP)
![Tabu Search](imagem.png)
Resolução do Problema de Roteamento de Veículos através da Meta-heurística Pesquisa Tabu que guia o algoritmo de busca local na exploração contínua dentro de um espaço de busca, a partir de uma solução inicial válida aleatória, avançando para outra solução na sua vizinhança até satisfazer o critério de parada.

## Funcionalidades
- Implementação do algoritmo de Pesquisa Tabu para CVRP
- Carregamento e manipulação de dados de entrada
- Visualização dos resultados obtidos

## Instalação
Para instalar as dependências, execute:
```bash
pip install -r requirements.txt
```

## Uso
Para executar o algoritmo, utilize os notebooks:
- `tabu_search_cvrp.ipynb`: Implementação principal da Pesquisa Tabu para CVRP.
- `tabu_search_2_cvrp.ipynb`: Implementação alternativa da Pesquisa Tabu para CVRP.

## Estrutura do Projeto
```
dataset/            # Conjuntos de dados utilizados
results/            # Resultados das execuções do algoritmo
tabu_search_cvrp.ipynb # Notebook principal
tabu_search_2_cvrp.ipynb # Notebook alternativo
requirements.txt    # Dependências do projeto
```

## Requisitos
- `requests`
- `json`
- `numpy`
- `pandas`
- `IPython`
- `matplotlib`
- `folium`

## Licença
Este projeto está licenciado sob a licença MIT. Veja o arquivo [MIT](https://choosealicense.com/licenses/mit/) para mais detalhes.
