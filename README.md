<h1 align="center">Projeto Rossmann Sales Predict</h1>

<p align="center">Projeto Rossmann Predict utilizando dados do Kaggle e ferramentas Python, Heroku, Telegram(bot)</p>

Tabela de conteúdos
=================
<p align="center">
 <a href="#sobre">Sobre</a> •
 <a href="#objetivo">Objetivo</a> •
 <a href="#premissas">Premissas</a> •
 <a href="#tecnologias">Tecnologias</a> • 
 <a href="#solução">Solução</a> • 
 <a href="#Lições_Aprendidas">Lições Aprendidas</a> • 
 <a href="#proximos_passos">Próximos Passos</a> • 
 <a href="#referências">Referências</a> • 
 <a href="#autor">Autor</a> • 
 <a href="#contribuidores">Contribuidores</a>  • 
 <a href="#licenc-a">Licença</a> • 
</p>

### Sobre
O Projeto House Rocket foi um estudo realizado para identificar insights através da análise de dados. Foi utilizado um dataset, do setor imobiliário, disponibilizado na plataforma Kaggle que contém as datas da compra, preço, qtd de quartos, qtd de banheiros, tamanho do imóvel, latidute/longitude, código postal, entre outros dados. 

A House Rocket é uma empresa fictícia do setor imobiliário com o objetivo de comprar imóveis com potencial de valorização, revendê-los para obter lucro nas transações.


### Objetivo
O Objetivo na exploração dos dados é analisar e identificar:
 1. Imóveis que estejam abaixo da mediana da região de localização
 2. Imóveis com boas condições e vista para a água
 3. Identificar a sazonalidade da data da compra (summer or winter)
 4. Analisar e confirmar as hipóteses:
    - H1: Imóveis que possuem vista para água, são 30% mais caros, na média.
    - H2: Imóveis com data de construção menor que 1955, são 50% mais baratos, na média.
    - H3: Imóveis sem porão possuem área total 50% maiores do que com porão.
    - H4: O crescimento do preço dos imóveis YoY (Year over Year) é de 10%
    - H5: Imóveis com 3 banheiros tem um crescimento MoM (Month over Month) de 15%


### Premissas

- Na limpeza dos dados:
   - Retirados os ID´s duplicados
   - Retirado o ID com número de quartos igual a 33 (possível erro de digitação)  
- Imóveis em bom estado foram considerados como condition igual 3 ou 4
- O crescimento anual foi calculado com o valor médio dos imóveis por ano, pois a base de dados só possuia o período de 13 meses.


### Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [Python](https://www.python.org/)
- [Streamlit](https://streamlit.io/)
- [Pandas](https://pandas.pydata.org/)

### Features

- [x] Cadastro de usuário
- [x] Cadastro de cliente
- [ ] Cadastro de produtos

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/). 
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

### 🎲 Rodando o Back End (servidor)

```bash
# Clone este repositório
$ git clone <https://github.com/tgmarinho/nlw1>

# Acesse a pasta do projeto no terminal/cmd
$ cd nlw1

# Vá para a pasta server
$ cd server

# Instale as dependências
$ npm install

# Execute a aplicação em modo de desenvolvimento
$ npm run dev:server

# O servidor inciará na porta:3333 - acesse <http://localhost:3333>
```


### Solução

- [HC_App_final_Streamlit.pdf](https://github.com/mbouhid/project_house_rocket/blob/main/hc_app_final_Streamlit.pdf)
- [HC_App_final_Streamlit_Menu.pdf](https://github.com/mbouhid/project_house_rocket/blob/main/hc_app_final_Streamlit_Menu.pdf)

### Lições Aprendidas

- A base de dados tem que estar limpa
- As afirmações devem ser bem claras para que a solução da análise confirme ou não as hipóteses
- Nem toda afimação/hipótese tem solução ou será respondida
- Identificar claramente as premissas para alinhamento das expectativas
- Importante saber exatamente o que o cliente precisa.
- Identificar as necessidades mesmo que não esteja no pedido do cliente.


### Referências

[Kaggle](https://www.kaggle.com/)

[Github](https://github.com/)

[Comunidade Data Science](https://www.comunidadedatascience.com/)

[Blog Seja Um Data Scientist](https://medium.com/@meigarom/os-5-projetos-de-data-science-que-far%C3%A1-o-recrutador-olhar-para-voc%C3%AA-c32c67c17cc9)


### Autor

<img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/41192466?v=4" width="100px;" alt=""/>

[![Linkedin Badge](https://img.shields.io/badge/-MarcioBouhid-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/marciobouhid/)](https://www.linkedin.com/in/marciobouhid/) 


### Contribuidores

O projeto não teve contribuidores oficiais. A Comunidade Data Science foi consultada em determinados momentos.


### Licença

GNU General Public License v3.0

