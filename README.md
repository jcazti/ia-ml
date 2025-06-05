# IA – Aprendizado de Máquina

Este repositório contém os trabalhos práticos da disciplina de **Aprendizado de Máquina** (Mestrado em IA, UFF).

## Estrutura Geral

```
/Trabalho01_Classificacao_Iris_BreastCancer
/Trabalho02_Classificacao_Iris_Versao2
```

### Trabalho 01 – Classificação Iris e Breast Cancer
- **Local**: `Trabalho01_Classificacao_Iris_BreastCancer/`
- **Descrição**:
  - `iris.py`: script que carrega o conjunto Iris, treina uma Decision Tree e exibe métricas de acurácia, matriz de confusão e curva ROC.
  - `cancer.py`: script que carrega o conjunto WDBC (Wisconsin Breast Cancer), treina uma Decision Tree e exibe métricas.
  - **Dados**:
    - Pasta `breastCancer/`: contém `wdbc.data` e `wdbc.names`.
    - Pasta `iris/`: contém `iris.data`, `iris.names`, `bezdekIris.data`.
- **Como executar**:
  ```bash
  cd Trabalho01_Classificacao_Iris_BreastCancer
  pip install -r requirements.txt
  python iris.py
  python cancer.py
  ```
- **Requisitos** (`requirements.txt`):
  ```
  numpy
  pandas
  scikit-learn
  matplotlib
  ```

### Trabalho 02 – Classificação Iris (Versão 2)
- **Local**: `Trabalho02_Classificacao_Iris_Versao2/`
- **Descrição**:
  - `iris.py`: versão alternativa para classificação Iris, comparando diferentes hiperparâmetros da árvore de decisão.
  - **Dados**:
    - Pasta `iris/`: contém `iris.data`, `iris.names`, `bezdekIris.data`.
- **Como executar**:
  ```bash
  cd Trabalho02_Classificacao_Iris_Versao2
  pip install -r requirements.txt
  python iris.py
  ```
- **Requisitos** (`requirements.txt`):
  ```
  numpy
  pandas
  scikit-learn
  matplotlib
  ```

## Como clonar este repositório
```bash
git clone https://github.com/<SEU_USUARIO>/ia-ml.git
```
