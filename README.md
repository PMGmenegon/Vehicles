# Análise de Anúncios de Veículos

## Descrição do Projeto

Este projeto consiste em um aplicativo web desenvolvido com **Streamlit** para explorar e visualizar dados de anúncios de vendas de veículos.

O aplicativo permite criar gráficos interativos para facilitar a análise dos dados, utilizando a biblioteca Plotly Express.

## Funcionalidades

- Visualização de um histograma da quilometragem dos veículos (`odometer`).
- Criação de um gráfico de dispersão relacionando o preço (`price`) e a quilometragem (`odometer`).
- Gráficos interativos para facilitar a exploração dos dados.

## Tecnologias Utilizadas

- Python
- Pandas
- Plotly Express
- Streamlit

## Estrutura do Projeto

```text
Vehicles/
│
├── notebooks/
│   ├── EDA.ipynb
│   └── vehicles.csv
│
├── app.py
├── requirements.txt
├── README.md
└── LICENSE
```

## Como Executar o Projeto

1. Clone o repositório:

```bash
git clone URL_DO_REPOSITORIO
```

2. Entre na pasta do projeto:

```bash
cd Vehicles
```

3. Instale as dependências:

```bash
pip install -r requirements.txt
```

4. Execute o aplicativo:

```bash
streamlit run app.py
```

5. Abra o endereço local exibido no terminal para acessar o aplicativo.

## Base de Dados

O projeto utiliza o arquivo `vehicles.csv`, localizado na pasta `notebooks`, contendo os dados utilizados para a criação das visualizações.

## Autor

Projeto desenvolvido como parte das atividades do curso de Data Science da TripleTen.
