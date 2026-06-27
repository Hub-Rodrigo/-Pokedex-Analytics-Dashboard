# 🏆 Pokedex Analytics Dashboard

Um dashboard interativo construído em **Python** utilizando o **Streamlit** e consumindo dados reais da **PokeAPI**. 

Este projeto foi desenvolvido como parte do meu portfólio de Análise de Dados, demonstrando habilidades em consumo de APIs RESTful, manipulação de dados em formato JSON e criação de interfaces web interativas para visualização de dados.

## 🚀 Funcionalidades

- **Ranking Interativo:** Gráfico de barras exibindo o ranking dos Pokémon com maior Experiência Base (XP).
- **Filtros Dinâmicos:** Barra lateral (sidebar) onde o usuário pode definir o tamanho da amostragem (de 10 a 150 Pokémon).
- **Motor de Busca:** Aba dedicada para pesquisar um Pokémon específico pelo nome.
- **Exibição de Mídia:** Retorno da imagem oficial (sprite) e dos status detalhados (peso, altura, XP) direto do banco de dados da API.
- **Sistema de Cache:** Utilização do `@st.cache_data` para otimizar requisições e não sobrecarregar a PokeAPI.

## 🛠️ Tecnologias Utilizadas

- [Python](https://www.python.org/) - Lógica principal.
- [Pandas](https://pandas.pydata.org/) - Transformação e tratamento dos dados.
- [Requests](https://requests.readthedocs.io/) - Requisições HTTP para a API.
- [Streamlit](https://streamlit.io/) - Framework para construção do frontend web e dos gráficos.
- [PokeAPI](https://pokeapi.co/) - Fonte de dados abertos.

  👨‍💻 Autor
Desenvolvido por [Rodrigo Souza] - LinkedIn

Portfólio/GitHub


### O que você acabou de criar:
Se você colocar o código `app.py` e esse `README.md` no seu GitHub, qualquer recrutador que entrar verá:
1. Que você entende de requisições web (API).
2. Que você sabe tratar dados estruturados (Pandas/JSON).
3. Que você sabe criar um produto visual entregável (Streamlit).
4. Que você sabe documentar seu próprio código (README).

Faça o teste do novo app no Colab. O que achou do visual com a busca de imagens? Se qui

## ⚙️ Como executar este projeto localmente


Pré-requisitos: Ter o Python instalado na sua máquina.

1. Clone este repositório:
```bash
git clone [https://github.com/Hub-Rodrigo/-Pokedex-Analytics-Dashboard/edit/main/README.md](https://github.com/Hub-Rodrigo/-Pokedex-Analytics-Dashboard/edit/main/README.md)

Acesse a pasta do projeto:

Bash
cd SEU_REPOSITORIO
Instale as bibliotecas necessárias:

Bash
pip install streamlit pandas requests
Execute o aplicativo:

Bash
streamlit run app.py
O site será aberto automaticamente no seu navegador padrão no endereço http://localhost:8501.




