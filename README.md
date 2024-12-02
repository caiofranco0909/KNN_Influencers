# Analise de influencers com KNN
Projeto Referente à Unidade 9 da Trilha de Ciência de Dados do ResTIC36, Grupo 2.

## **Descrição do Projeto**
Este projeto utiliza o algoritmo **k-Nearest Neighbors (kNN)** para explorar e analisar dados de influenciadores do Instagram, com foco em prever padrões de engajamento e alcance. O trabalho inclui desde o pré-processamento dos dados até a validação do modelo e a análise dos resultados, fornecendo insights sobre variáveis-chave como número de seguidores, média de curtidas e taxa de engajamento.

O principal objetivo é avaliar a eficácia do kNN como modelo preditivo em um cenário real, destacando limitações e melhorias possíveis.

---
## **Como Executar no Google Colab**

### **Passo a Passo**
1. **Acesse o Notebook**:
    - Abra o Google Colab e importe o notebook utilizando o link do repositório ou faça upload manual do arquivo `KNN-Influencers.ipynb`.

2. **Carregue os Dados**:
    - Certifique-se de que o arquivo de dados está disponível no Google Drive ou faça o upload manual. Atualize os caminhos no notebook conforme necessário.
    ```python
        #Dataset
        file_path = 'CAMINHO PARA O ARQUIVO'
        influencers = pd.read_csv(file_path)
      ```
3. **Instale Dependências**:
    - Execute a célula que contém o código para instalar as bibliotecas necessárias no ambiente do Colab

4. **Execute o Notebook**:
    - Siga as células sequencialmente para realizar as análises
---

## **Estrutura dos Arquivos**

- O arquivo .ipynb é o notebook que deve ser aberto no Google Colab
- O arquivo .pdf se refere ao Relatório do Projeto
- O arquivo .csv são os dados utilizados no projeto

---

## **Tecnologias Utilizadas**
- **Ambiente de Desenvolvimento**:
    - Google Colab
- **Bibliotecas**:
    - Pandas
    - Numpy
    - Scikit-Learn
    - Matplotlib
    - Seaborn

## **Autores e Colaboradores**

- **Caio Franco e Camilo Alves Mascarenhas**

Se você tiver dúvidas ou sugestões, sinta-se à vontade para entrar em contato!
