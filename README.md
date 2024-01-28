# [Projeto SIN492] - Reconhecimento de Padrões

## Descrição

Este repositório abriga o código-fonte e o conjunto de dados empregados no projeto elaborado durante a disciplina de verão SIN492 - Reconhecimento de Padrões. O escopo do projeto envolve a implementação e avaliação de um modelo de aprendizado de máquina e uma rede neural, ambos aplicados a uma base de dados fictícia. 

O objetivo principal é explorar e analisar as capacidades desses modelos no contexto do reconhecimento de padrões, proporcionando uma experiência prática e aprofundada aos participantes da disciplina. O código disponível aqui oferece uma visão transparente do processo de desenvolvimento, permitindo revisão, replicação e compreensão mais aprofundada do trabalho realizado.

## Arquivos

1. **Converter a Base de Dados**: Pasta que contem o aqruivo Jupyter Notebook na qual tem o propósito em converter o Banco de Dados dado. 

2. **Bayseano**: Pasta que contem o aqruivo Jupyter Notebook contendo o código do Algoritmo Bayseano juntamente com o dataset convertido. 

3. **Modelo-MLP**: Pasta que contem o aqruivo Jupyter Notebook contendo o código do Modelo da Rede Neural MLP juntamente com o dataset convertido.

4. **Regressão**: Pasta que contem o aqruivo Jupyter Notebook contendo o código do Classificador de Regressão juntamente com o dataset convertido.

## Executando Notebook

Passo a passo para abrir o codigo usando o [Anaconda](https://www.anaconda.com/download), certifique-se tambem que possua o ambiente [Python](https://www.python.org/downloads/) instalado.

1. Crie um ambiente virtual (opcional, mas recomendado):
  Para garantir um ambiente isolado, recomenda-se criar um ambiente virtual. Utilize o seguinte comando para criar um ambiente virtual usando o Conda:
    ```bash
        conda create --name nome_do_seu_ambiente python=3.8
    ```

2. Ative o ambiente virtual:
  Ative o ambiente virtual recém-criado com o seguinte comando:
  ```bash
    conda activate nome_do_seu_ambiente
  ```

3. Instale o Jupyter Notebook:
  Instale o Jupyter Notebook no ambiente virtual com o seguinte comando:
    ```bash
      conda install jupyter
    ```

4. Instale as Bibliotecas Necessárias:
    * Use o comando abaixo para instalar as Dependências:

    ```bash
        conda install numpy pandas matplotlib seaborn tensorflow scikit-learn pyarrow
    ```
5. Certifique-se que esta tudo atualizado:
    Certifique-se de que tudo está atualizado executando o seguinte comando:
        ```bash
        conda update --all
        ```

6. Inicie o Jupyter Notebook:
  Depois de instalado, inicie o Jupyter Notebook com o comando:
  ```bash
    jupyter notebook
  ```

Isso abrirá uma nova janela ou guia no navegador padrão, onde você poderá navegar até o diretório do projeto e abrir o notebook associado.

## Participantes

- [Bernardo Teixeira de Miranda](https://github.com/BTMiranda)
- [Marcus Vinicius Diniz dos Reis](https://github.com/Allinvila) 
- [Moisés José Moreira Ribeiro](https://github.com/MMoreira020)

## Agradecimentos

Queremos expressar nossa gratidão aos professores Leandro Henrique Furtado, Larissa Ferreira Rodrigues e Pedro Moises de Sousa pelo valioso conhecimento compartilhado conosco, bem como pelo suporte contínuo ao longo da execução do projeto. A contribuição deles foi fundamental para o sucesso e aprendizado durante essa etapa.
