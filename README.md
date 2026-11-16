# Acidentes em rodovias federais brasileiras (2021–2025)

Atividade Prática Supervisionada da disciplina **Python para Ciência de Dados**.

## Integrantes

- Camille Souza
- Elora Rocha
- Gabriela Afif
- Maria Luiza Sevilha

## Dados

O projeto utiliza os arquivos de acidentes agrupados por ocorrência, disponibilizados no [Portal de Dados Abertos da Polícia Rodoviária Federal](https://www.gov.br/prf/pt-br/acesso-a-informacao/dados-abertos/dados-abertos-da-prf).

Os cinco arquivos CSV devem permanecer em `dados/brutos/`, com os nomes:

- `datatran2021.csv`
- `datatran2022.csv`
- `datatran2023.csv`
- `datatran2024.csv`
- `datatran2025.csv`

## Execução

O projeto foi validado com:

- Python 3.10.12
- NumPy 2.2.6
- SciPy 1.15.3
- pandas 2.3.3
- plotnine 0.15.7
- mizani 0.14.4
- statsmodels 0.14.6
- scikit-learn 1.7.2

Para executar:

1. Manter `relatorio.ipynb` e a pasta `dados/` na estrutura indicada abaixo.
2. Confirmar que `dados/brutos/` contém os cinco CSVs.
3. Abrir `relatorio.ipynb` no JupyterLab.
4. Reiniciar o kernel.
5. Executar todas as células na ordem.

Caso necessário, instalar as bibliotecas com:

```bash
python -m pip install pandas plotnine mizani statsmodels scikit-learn jupyterlab
```

## Estrutura

```text
.
├── relatorio.ipynb
├── README.md
└── dados/
    └── brutos/
        ├── datatran2021.csv
        ├── datatran2022.csv
        ├── datatran2023.csv
        ├── datatran2024.csv
        └── datatran2025.csv
```
