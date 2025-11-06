# 🌸 Projeto AG2 — Classificação de Íris (Inatel)

Este repositório contém o trabalho prático **AG2** da disciplina de Engenharia de Software.
O objetivo é treinar, avaliar e disponibilizar um modelo de Machine Learning capaz de classificar flores do gênero *Iris* com base em suas medidas.

---

## 🚀 Tecnologias utilizadas

- Python 3.12+
- pandas 2.3.3
- numpy 1.26.4
- scikit-learn 1.7.2
- matplotlib 3.8.1
- seaborn 0.12.2
- Jupyter Notebook

---

## ⚙️ Configuração do ambiente (venv)

Siga os passos abaixo no terminal para criar um ambiente virtual, instalar dependências e executar o notebook.

### 1) Criar o ambiente virtual

Windows (cmd.exe):

```cmd
python -m venv venv
```

### 2) Ativar o ambiente virtual

Windows (cmd.exe):

```cmd
venv\\Scripts\\activate
```

PowerShell:

```powershell
venv\\Scripts\\Activate.ps1
```

Linux / macOS:

```bash
source venv/bin/activate
```

Após ativar, o prompt ficará parecido com:

```
(venv) C:\Users\yourName\...
```

### 3) Instalar dependências

Com a venv ativa, execute:

```cmd
pip install -r requirements.txt
```

Conteúdo mínimo do `requirements.txt` usado neste projeto:

```
pandas==2.3.3
numpy==1.26.4
scikit-learn==1.7.2
matplotlib==3.8.1
seaborn==0.12.2
```

### 4) Instalar Jupyter e registrar o kernel (opcional, mas interessante essa interação)

```cmd
pip install jupyter ipykernel
python -m ipykernel install --user --name=venv --display-name "Python (venv)"
```

### 5) Iniciar o Jupyter Notebook

```cmd
jupyter notebook
```

O navegador abrirá em algo como `http://localhost:8888/tree`. Abra o notebook do projeto (`iris_classification.ipynb`) e selecione o kernel `Python (venv)` se necessário. Dessa forma, você poderá navegar pelo projeto em uma interface parecida com o GitHub, porém, interativa!!! 🤩

## ▶️ Execução do projeto

No notebook principal (ex.: `iris_classification.ipynb`) as etapas executadas são, tipicamente:

1. Carregamento do dataset (`data.csv`).
2. Pré-processamento e mapeamento das espécies.
3. Treinamento e avaliação do modelo (por exemplo, KNN).
4. Exibição de métricas e matriz de confusão.
5. Testes de predição em amostras arbitrárias.

## 👨‍💻 Autores

- Dimitri Schulz
- Felipe Souza

Engenharia de Software — Inatel
Novembro / 2025

Contato LinkedIn (Felipe Souza): https://www.linkedin.com/in/felipesouza-softwareeng
