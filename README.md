# <img src="https://github.com/user-attachments/assets/caabfdf0-0f9e-44a3-8200-c6579fe87887" alt="Ícone de descrição" width="28"> Descrição
O projeto compara 2 algoritmos - **Rede Neural Convolucional (CNN)** e **Random Forest** - no contexto de classificação de resíduos para reciclagem.

# <img src="https://img.icons8.com/?size=100&id=yo0i7M1LcJf3&format=png&color=000000" alt="Ícone de requisitos" width="28"> Requisitos
- Python 3.11.9

# <sub><img src="https://img.icons8.com/?size=100&id=12116&format=png&color=000000" alt="Ícone de problema" width="34"></sub> Problemática
Classificação dos **resíduos sólidos para reciclagem**.

# <img src="https://img.icons8.com/?size=100&id=LHCJqL3jnCpK&format=png&color=000000" alt="Ícone de justificativa" width="32"> Justificativa
No mundo atual, o **consumo** desenfreado gera muito resíduos. Desse modo, na maioria das vezes esses resíduos não são descartados corretamente para serem direcionados para uma reciclagem posterior. Com os algoritmos desenvolvidos, poder-se-á **automatizar** o processo de separação, tornando mais fácil a reciclagem das matérias-primas.

# <img src="https://github.com/user-attachments/assets/3b41eaf5-bdff-4ef8-a2cf-eb4e4f206000" alt="Ícone de relevância" width="32"> Relevância
Os algoritmos desenvolvidos podem ser implementados em **lixeiras inteligentes** e **esteiras de triagem de resíduos**, mitigando o acúmulo de resíduos sólidos no meio ambiente e reduzindo a exploração dos recursos ambientes para extração de novas matérias-primas.

# <sub><img src="https://img.icons8.com/?size=100&id=bMncK0wGFANA&format=png&color=000000" alt="Ícone do Kaggle" width="42"></sub> Kaggle Dataset
[Clique aqui](https://www.kaggle.com/datasets/asdasdasasdas/garbage-classification)

# <img src="https://img.icons8.com/?size=100&id=RFsDMYLkvkcO&format=png&color=000000" alt="Ícone de pré-processamento" width="28"> Pré-processamento
### Classes
Os resíduos serão divididos em **5 classes (plástico, papel, metal, vidro e papelão)**.

### Quantidade de pixels 
A resolução de todas as imagens utilizadas foram padronizadas, sendo **512x384**.

### Divisão em grupos de teste e treinamento
Primeiramente serão separadas 400 imagens, de modo aleatório, para cada classe de resíduo. Após, será utilizada a **Regra de Pareto** com a finalidade de mitigar o *overfitting*, em que 80% (320 imagens) das imagens separadas serão para treinamento e 20% (80 imagens) serão voltadas para os testes, com o intuito de mensurar o desempenho dos 2 algoritmos.

# <img src="https://img.icons8.com/?size=100&id=66365&format=png&color=000000" alt="Ícone dos algoritmos" width="32"> Algoritmos utilizados 
- Rede Neural Convolucional (CNN)
- Random Forest
