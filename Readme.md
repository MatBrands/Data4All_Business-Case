# Data4All - Business Case
...

## Conteúdo
- Machine Learning Canvas
- Tecnologias
- Base de dados
- Instalação
- Organização do projeto
- Commits
- Contribuições
- License

## Machine Learning Canvas
...

## Tecnologias
...

## Base de dados
...

## Instalação
Foi utilizado o [Python](https://www.python.org/) v3.11.

### Conda
No desenvolvimento foi utilizado o gerenciador de pacotes e ambientes [Conda](https://docs.conda.io/en/latest/). Portanto para prosseguir necessita-se de sua instalação.

Navegar até a pasta de destino
```sh
cd utils
```

Instalar dependências
```sh
conda env create -f environment.yml
```

Ativar
```sh
conda activate data4all_venv
```

Desativar
```sh
conda deactivate
```

### Requirements
Pode-se utilizar o arquivo requirements.txt para criar o ambiente virtual.

Criar ambiente virtual
```sh
python -m venv data4all_venv
```

Ativar
```sh
source ./data4all_venv/bin/activate
```

Navegar até a pasta de destino
```sh
cd utils
```

Instalar dependências
```sh
pip install -r requirements.txt
```

Desativar
```sh
deactivate
```

## Organização do projeto
```sh
.
├── License
├── Readme.md
├── main
│   ├── datasets
│   │   └── raw.csv
│   ├── media
│   │   └── data_analytics.png
│   └── notebooks
│       └── Desafio_Ciencia_de_Dados_Gerdau.ipynb
└── utils
    ├── environment.yml
    └── requirements.txt
```

## Commits
Neste projeto foi adotado o uso de Commits Semânticos para padronização:

- Feat: Nova feature do projeto
- Refactor: Refatoração de alguma parte do código
- Fix: Correção de erros que estão causando bugs
- Chore: Mudanças que não influenciam o sistema nem arquivos de testes
- Style: Mudanças de formatação ou estilos de códigos que não influenciam na lógica do sistema
- Test: Criação ou alteração de algum código de teste
- Perf: Alterações feitas para melhorar a performance do projeto
- Docs: Alterações na documentação do projeto

## Contribuições
...

## License
MIT.