# 📊 Análise Exploratória da Previsão de Renda

Este projeto realiza uma análise exploratória interativa sobre um conjunto de dados de renda, utilizando **Streamlit**, **Pandas**, **Seaborn** e **Matplotlib**.

## 🚀 Objetivo

O objetivo é permitir a visualização e exploração de dados relacionados à previsão de renda, através de gráficos interativos e segmentações por variáveis demográficas e socioeconômicas.

## 🧪 Tecnologias Utilizadas

- [Python](https://www.python.org/)
- [Streamlit](https://streamlit.io/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)

## 📂 Estrutura Esperada do Arquivo CSV

O arquivo CSV carregado deve conter as seguintes colunas:

| Coluna             | Descrição                                       |
|--------------------|-------------------------------------------------|
| `data_ref`         | Data de referência                              |
| `renda`            | Valor da renda                                  |
| `posse_de_imovel`  | Indica se o cliente possui imóvel               |
| `posse_de_veiculo` | Indica se o cliente possui veículo              |
| `qtd_filhos`       | Quantidade de filhos                            |
| `tipo_renda`       | Categoria do tipo de renda                      |
| `educacao`         | Nível educacional                               |
| `estado_civil`     | Estado civil do cliente                         |
| `tipo_residencia`  | Tipo de residência onde mora                    |

## 📈 Funcionalidades

- Upload de arquivo `.csv` via barra lateral do Streamlit.
- Geração de gráficos de linha com a evolução da renda ao longo do tempo por categorias:
  - Posse de imóvel
  - Posse de veículo
  - Quantidade de filhos
  - Tipo de renda
  - Nível educacional
  - Estado civil
  - Tipo de residência
- Geração de gráficos de barras para análise bivariada da renda média por variável categórica.
- Interface limpa e organizada com visualização fácil via navegador.

## 🎯 Como Usar

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/analise-renda.git
cd analise-renda
```

2. Crie um ambiente virtual e ative:

```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```

3. Instale as dependências:

```bash
pip install -r requirements.txt
```

4. Execute a aplicação:

```bash
streamlit run app.py
```

5. Faça o upload do seu arquivo `.csv` através da barra lateral.

## 🧾 Exemplo de `requirements.txt`

```text
streamlit
pandas
seaborn
matplotlib
```

## 💡 Sugestões de Expansão

- Inclusão de filtros por período de tempo.
- Adição de boxplots para análise de dispersão da renda.
- Exportação dos gráficos gerados.
- Detecção de outliers e análises estatísticas.

## 🧑‍💻 Autor

**Adelson** – Cientista de Dados  
[LinkedIn](https://linkedin.com/in/adelson21)  
[GitHub](https://github.com/Adelson021)

---

> Projeto desenvolvido com ❤️ utilizando Python e Streamlit.


## Streamlit

https://github.com/user-attachments/assets/45aa43c7-a0e1-4087-b663-db0a3dc03374

