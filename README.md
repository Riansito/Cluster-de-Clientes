# 📊 Segmentação de Clientes para Produtos Financeiros

## 📝 Descrição do Projeto

Este projeto tem como objetivo **realizar uma segmentação de clientes** com base no comportamento de uso do cartão de crédito nos últimos 6 meses. A segmentação busca identificar diferentes perfis de clientes para recomendar produtos financeiros personalizados, como:

* **Planos de poupança**
* **Empréstimos personalizados**
* **Gestão de patrimônio (wealth management)**

Através de análises detalhadas e técnicas avançadas de clusterização, foram identificados padrões de comportamento em grupos distintos, fornecendo insights para estratégias personalizadas.

---

## 🔍 Principais Insights

* **4 clusters principais** foram identificados, sendo que:

  * Os clusters **0 e 2** possuem a menor porcentagem de clientes.
  * Os clusters **1 e 3** possuem a maior concentração de clientes.

* **Recomendações personalizadas** foram desenvolvidas para cada cluster:

  * **Cluster 0:** Empréstimos personalizados devido à alta utilização de adiantamentos.
  * **Cluster 1:** Planos de poupança, ideal para clientes equilibrados.
  * **Cluster 2:** Gestão de patrimônio, para clientes com maior poder aquisitivo.
  * **Cluster 3:** Produtos básicos e educação financeira, devido ao perfil conservador.

---

## 📌 Etapas do Projeto

### 1. 📥 Pré-processamento dos Dados

* Normalização das variáveis para padronização.
* Redução da dimensionalidade com **PCA** (4 componentes principais).

### 2. 🤖 Clusterização

* Teste de diferentes algoritmos de agrupamento:

  * **K-Means** (modelo final escolhido).
  * **DBSCAN**.
  * **Gaussian Mixture**.
* Avaliação do número ideal de clusters com o **método do cotovelo** e métricas como:

  * **Silhouette Score**.
  * **Calinski-Harabasz Score**.
  * **Davies-Bouldin Score**.
* Definição do modelo final com **4 clusters** baseando-se no balanço entre granularidade e interpretabilidade dos grupos.

### 3. 📊 Análise dos Clusters

* **Cluster 0:**

  * Clientes com alta utilização de adiantamentos e saldo disponível elevado.
  * **Recomendação:** Empréstimos personalizados para atender necessidades imediatas.

* **Cluster 1:**

  * Perfil equilibrado em compras e pagamentos.
  * **Recomendação:** Produtos de poupança para incentivar reservas financeiras.

* **Cluster 2:**

  * Alta taxa de pagamentos completos e maior limite de crédito.
  * **Recomendação:** Produtos de gestão de patrimônio (wealth management).

* **Cluster 3:**

  * Clientes com baixo engajamento financeiro e uso moderado do cartão.
  * **Recomendação:** Educação financeira e produtos básicos.

---

## 🔧 Ferramentas Utilizadas

* **Python**: Para análise, modelagem e visualização.
* **Principais bibliotecas**:

  * `Pandas` e `NumPy`: Manipulação e análise de dados.
  * `Scikit-learn`: Clusterização e métricas de avaliação.
  * `Matplotlib` e `Seaborn`: Visualização gráfica.

---

## 🎯 Conclusão

Este projeto demonstrou a eficácia de aplicar técnicas de clusterização para segmentação de clientes. Com base nos padrões comportamentais identificados, é possível oferecer soluções financeiras personalizadas, maximizando o valor entregue ao cliente e melhorando a estratégia comercial da empresa.

---

## 🚀 Como Executar o Projeto

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/seu-usuario/segmentacao-clientes.git
   ```

2. **Instale as dependências:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Execute o script principal:**

   ```bash
   python main.py
   ```

---

## ✉️ Contato

Em caso de dúvidas ou sugestões:

* **Autor:** Rian Freires da Costa Silva
* **E-mail:** [rianfreires@gmail.com](mailto:rianfreires@gmail.com)
* **LinkedIn:** [linkedin.com/in/rianfreires](https://linkedin.com/in/rianfreires)

Contribuições são bem-vindas! 😊
