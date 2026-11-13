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

1. Abrir `relatorio.ipynb` no JupyterLab.
2. Confirmar que a pasta `dados/brutos/` contém os cinco CSVs.
3. Reiniciar o kernel.
4. Executar todas as células na ordem.

Bibliotecas principais: `pandas`, `plotnine`, `mizani`, `statsmodels` e `scikit-learn`.

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
