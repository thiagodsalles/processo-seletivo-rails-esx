# Desafio Ruby on Rails ESX
Olá candidato, estamos muito feliz em saber que você chegou até aqui no processo! Neste momento iremos avalia-lo quanto as capacidades técnicas no desenvolvimento fullstack 
em Ruby on Rails.

Para te ajudar neste desafio, nós criamos este repositório contendo o básico do Ruby on Rails com o Rspec instalado, mas atenção! Nem tudo foi instalado.

Faça uma cópia deste repositório para o seu computador e crie um novo repositório em seu GitHub com o seguinte nome: processo-seletivo-rails-esx-seu-nome-e-sobrenome.

Crie um readme simples mostrando como devemos rodar o sistema, como devemos utiliza-lo e como devemos rodar os testes.

Ao finalizar o desenvolvimento envie o link do seu desafio para o seguinte e-mail: thiago.guimaraes@esx.com.br

# O que iremos avaliar neste desafio?
- O cumprimento dos requisitos abaixo.
- O desenvolvimento de testes com o Rspec.
- O uso do Docker.
- O uso de API.
- Manipulação de dados.
- O uso de boas práticas do Ruby on Rails e do Git.
- O uso de design patterns.
- O uso de clean code

# Qual é o propósito do sistema?
O sistema tem como objetivo receber uma URL e verificar o status do certificado SSL da mesma. O sistema irá salvar o histórico de cada consulta que poderá ser consultada 
via API ou tela posteriormente.

# Requisitos não funcionais
- Utilizar o Ruby 2.6.9.
- Utilizar o Rails 4.2.11.3.
- O sistema deverá rodar em Docker.
- O front deverá ser em Bootstrap.

# Requisitos funcionais
- O usuário irá acessar a página de consulta do certificado via URL. Esta página será o root do sistema.
- O usuário irá inserir a URL desejada em um text field e irá consultar o status do certificado SSL.
- O sistema deverá trazer o status do certificado nesta mesma tela e também irá salvar os dados da requisição no banco de dados para manter o histórico.
- Na tela de históricos deve-se apresentar uma tabela com as seguintes informações: Data e hora da requisição (DD/MM/AAAA - HH:MM), status do certificado, URL do 
certificado.
- Cada linha do histórico deverá ter um botão de apagar dado, o qual irá apagar a linha.
- A tabela de históricos deverá ter como ordenação padrão os mais recentes primeiros.
- A tabela de históricos poderá ser ordenada pelas seguintes formas via parâmetro: data de criação das mais antigas primeiro ou somente pela URL X (www.foo.com.br) ou 
somente pelo status X.
- O histórico também poderá ser retornado por um JSON caso fizermos uma consulta via API.

# Dicas!
Para testar os certificados você pode usar a gem: https://github.com/jarthod/ssl-test

O site https://badssl.com/ vai te ajudar também.
