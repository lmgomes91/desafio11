# desafio11
 
Nesse desafio, você irá desenvolver mais uma aplicação, a GoRestaurant, só que dessa vez a versão mobile para o cliente. Agora você irá praticar o que você aprendeu até agora no React Native junto com TypeScript, para criar um pequeno app para pedidos de comida. Essa será uma aplicação que irá se conectar a uma Fake API, e exibir e filtrar os pratos de comida da API e permitir a criação de novos pedidos.

**Utilizando uma fake API**

Antes de tudo, para que você tenha os dados para exibir em tela, criamos um arquivo que você poderá utilizar como fake API para te prover esses dados.

Para isso, deixamos instalado no seu package.json uma dependência chamada json-server, e um arquivo chamado server.json que contém os dados para as seguintes rotas:

*Rota /foods*: Retorna todas as comidas cadastradas na API

*Rota /foods/:id*: Retorna um prato de comida cadastradas na API baseado no id

*Rota /categories*: Retorna todas as categorias cadastradas na API

*Rota /orders*: Retorna todas os pedidos que foram cadastrados na API

*Rota /favorites*: Retorna todas as comidas favoritas que foram cadastrados na API

      yarn json-server server.json -p 3333
      
 
