# Descrição
O projeto compara 2 algoritmos - Rede Neural Convolucional (CNN) e Random Forest - no contexto de classificação de resíduos para reciclagem.

# Requisitos
- Python 3.11.9

# Problemática
Classificação dos resíduos sólidos para reciclagem.

# Justificativa
No mundo atual, o consumo desenfreado gera muito resíduos. Desse modo, na maioria das vezes esses resíduos não são descartados corretamente para serem direcionados para uma reciclagem posterior. Com os algoritmos desenvolvidos, poder-se-á automatizar o processo de separação, tornando mais fácil a reciclagem das matérias-primas.

# Relevância
Os algoritmos desenvolvidos podem ser implementados em lixeiras e esteiras de triagem de resíduos, mitigando o acúmulo de resíduos sólidos no meio ambiente e reduzindo a exploração dos recursos ambientes para extração de novas matérias-primas.

# Kaggle Dataset
[Clique aqui](https://www.kaggle.com/datasets/asdasdasasdas/garbage-classification)


# Pré-processamento
### Classes
Os resíduos serão divididos em 5 classes (plástico, papel, metal, vidro e papelão).

### Quantidade de pixels 
A resolução de todas as imagens utilizadas foram padronizadas, sendo 512x384.

### Divisão em grupos de teste e treinamento
Primeiramente serão separadas 400 imagens, de modo aleatório, para cada classe de resíduo. Após, será utilizada a Regra de Pareto com a finalidade de mitigar o overfitting, em que 80% (320 imagens) das imagens separadas serão para treinamento e 20% (80 imagens) serão voltadas para os testes, com o intuito de mensurar o desempenho dos 2 algoritmos.

# Algoritmos utilizados 
- Rede Neural Convolucional (CNN)
- Random Forest
