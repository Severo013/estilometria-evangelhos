# Estilometria Aplicada aos Evangelhos

Este projeto realiza uma **análise estilométrica** dos Evangelhos — Mateus, Marcos, Lucas e João — utilizando técnicas de **Processamento de Linguagem Natural (NLP)** e **Aprendizado de Máquina (ML)**.

## 📖 Objetivo
Identificar padrões de escrita e semelhanças estilísticas entre os textos bíblicos, explorando a interseção entre **ciência de dados** e **estudos teológicos**.

## 🛠️ Tecnologias Utilizadas
- **Linguagens**: Python
- **Bibliotecas principais**:
  - `nltk` e `spacy` para NLP
  - `scikit-learn` para vetorização, redução de dimensionalidade e clustering
  - `matplotlib` e `seaborn` para visualização
- **Outras ferramentas**: Jupyter Notebook

## 📂 Estrutura do Projeto
- `data/`: Contém os textos dos evangelhos em formato `.txt`.
- `results/`: Resultados gerados, como métricas e gráficos.
- `Estilometria_Evangelhos.ipynb`: Notebook principal com todas as etapas da análise.

## 🚀 Como Executar
1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/estilometria-evangelhos.git
   cd estilometria-evangelhos
   ```

2. **Crie e ative um ambiente virtual**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # No Windows: venv\Scripts\activate
   ```

3. **Instale as dependências**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Baixe os modelos necessários**:
   - `nltk`:
     ```python
     import nltk
     nltk.download('punkt')
     nltk.download('stopwords')
     ```
   - `spacy`:
     ```bash
     python -m spacy download pt_core_news_sm
     ```

5. **Execute o notebook**:
   Abra o arquivo `Estilometria_Evangelhos.ipynb` no Jupyter Notebook ou VSCode e execute as células.

## 📊 Etapas da Análise
1. **Importação e configuração do ambiente**.
2. **Coleta e estruturação dos dados**: Carregamento e divisão dos textos em _chunks_.
3. **Pré-processamento**: Limpeza e normalização dos textos.
4. **Extração de métricas estilométricas**: Diversidade lexical, comprimento médio das palavras, etc.
5. **Vetorização com TF-IDF**.
6. **Redução de dimensionalidade e clustering**: Agrupamento com K-Means.
7. **Visualização dos clusters**.
8. **Análise das palavras representativas de cada cluster**.
9. **Considerações finais**.

## 📈 Resultados Esperados
- Identificação de padrões estilísticos entre os evangelhos.
- Gráficos e métricas que destacam as diferenças e semelhanças entre os textos.

## 📝 Licença
Este projeto está licenciado sob a [MIT License](LICENSE).

---
**Autor**: Gabriel Severo  
Disciplina: Mineração de Dados e Aprendizado de Máquina
