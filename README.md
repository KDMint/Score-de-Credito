# 📊 **Previsão de Score de Crédito com IA**

Este projeto utiliza algoritmos de **Inteligência Artificial** (IA) para prever o **score de crédito** de clientes com base em dados históricos. A IA é treinada com um conjunto de dados, e depois aplicada para fazer previsões sobre novos clientes.

---

## 📝 **Descrição**

O objetivo deste projeto é prever o score de crédito dos clientes (avaliado como "Good", "Ok", "Poor") com base em várias informações, como:
- **Profissão**
- **Mix de Crédito**
- **Comportamento de Pagamento**

A previsão é feita por meio de dois algoritmos de aprendizado de máquina:
- **Random Forest Classifier**: Um modelo baseado em árvores de decisão.
- **K-Nearest Neighbors (KNN)**: Um modelo baseado na proximidade de dados.

---

## 🛠️ **Tecnologias Utilizadas**
- **Python**: Linguagem utilizada para implementar o modelo de IA.
- **Pandas**: Biblioteca usada para manipulação e análise dos dados.
- **Scikit-learn**: Biblioteca usada para a criação e treinamento dos modelos de IA (Random Forest e KNN).

---

## 🚀 **Como Usar**

### ✅ **Pré-requisitos**
1. **Python**: Certifique-se de ter o Python instalado em sua máquina.
2. **Instalar as dependências**:
```
pip install pandas scikit-learn
```

### ▶️ **Executando o Projeto**
1. Baixe os arquivos **`clientes.csv`** e **`novos_clientes.csv`**.
2. Execute o código Python para treinar o modelo e fazer previsões.

#### **Passos**:
- **Leitura de dados**: O código começa carregando os dados de clientes históricos e novos clientes.
- **Pré-processamento**: As colunas de texto (como profissão, mix de crédito e comportamento de pagamento) são convertidas para valores numéricos usando o `LabelEncoder`.
- **Divisão dos dados**: O conjunto de dados é dividido em dados de treino e dados de teste.
- **Treinamento da IA**: O modelo é treinado utilizando os dados de treino.
- **Avaliação do modelo**: O modelo é avaliado com base na acurácia utilizando os dados de teste.
- **Previsão**: A IA faz previsões para novos clientes usando o modelo treinado.

---

## 📊 **Como Funciona**

- **Label Encoding**: As colunas de texto (como profissão e comportamento de pagamento) são transformadas em valores numéricos para que a IA consiga aprender com os dados.

- **Random Forest**: Utiliza múltiplas árvores de decisão para classificar os dados.
- **K-Nearest Neighbors (KNN)**: Classifica os dados com base na proximidade de outros pontos de dados.

- **Avaliação de Acurácia**: O modelo de maior precisão (baseado na acurácia) é escolhido como o melhor para fazer previsões.

- **Previsões**: Depois de treinar o modelo com dados históricos, ele faz previsões para novos clientes.

---

## 📝 **Arquivos do Projeto**

- **`clientes.csv`**: Conjunto de dados com informações sobre clientes existentes, incluindo a profissão, mix de crédito, comportamento de pagamento e o score de crédito.
- **`novos_clientes.csv`**: Conjunto de dados com informações de novos clientes para os quais o modelo irá prever o score de crédito.

---

## 📬 **Contato**

Para dúvidas ou sugestões, entre em contato via:
- **E-mail**: khadijalima2005@gmail.com

---

## 📜 **Licença**
Este projeto está licenciado sob a Licença MIT. Consulte o arquivo `LICENSE` para mais informações.
