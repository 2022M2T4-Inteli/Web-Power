# Inteli - Instituto de Tecnologia e Liderança 

<p align="center">
<a href= "https://www.inteli.edu.br/"><img src="https://www.inteli.edu.br/wp-content/uploads/2021/08/20172028/marca_1-2.png" alt="Inteli - Instituto de Tecnologia e Liderança" border="0"></a>
</p>

# Antecipação de Parceiros

## Web Power

## Integrantes: 
- <a href="https://www.linkedin.com/in/allan-casado-6339a9177/">Allan Casado</a>
- <a href="">Giovane Andreussi</a>
- <a href="https://www.linkedin.com/in/jackson-aguiar/">Jackson Aguiar</a> 
- <a href="https://www.linkedin.com/in/jo%C3%A3o-lucas-delistoianov-gonzalez-b0501922a/">João Gonzales</a> 
- <a href="https://www.linkedin.com/in/carvalholari/">Larissa Carvalho</a>
- <a href="https://www.linkedin.com/in/vitoraugustobarros/">Vitor Augusto</a> 

## 📝 Descrição

Descrição curta sobre o que seu projeto faz:

Durante o decorrer desse módulo, foi solicitado que fosse desenvolvido um projeto em grupo, que trata-se de uma aplicação web, em que nosso cliente é a Hurb - maior agência de viagens online sediada no Brasil. O problema se dá pelo fato de que atualmente, as antecipações de parceiros dessa agência ocorrem de maneira não muito eficaz, processo realizado pela equipe do contas a pagar. Com isso, visando melhorar esse processo, esse sistema atual, o tornando mais rápido e eficaz, criamos uma solução que trata-se de uma aplicação web, na qual tanto o Hurb como os hotéis parceiros terão acesso totalmente digital. Sendo assim, nessa plataforma, os hotéis parceiros poderão realizar a solicitação da antecipação de pagamento e acompanhar o status dessa solicitação, como diversos outros serviços que também serão oferecidos. Durante o desenvolvimento desse projeto, foi levado em consideração: as regras de negócio, tendo como base os tipos de demanda (D2, D7 e D12), como também os componentes necessários de se ter no site.

De um a dois parágrafos sobre o que é seu projeto e o que ele faz:

O projeto desse módulo trata-se de um desenvolvimento web, na qual temos o Hurb como o nosso cliente. Foi solicitado que criássemos uma aplicação web, com o objetivo de realizar antecipações de pagamento para os hotéis parceiros da empresa Hurb, uma vez que esse processo de antecipação ocorria com um sistema pouco desenvolvido tecnologicamente. 

Sendo assim, com o nosso web site, é possível que os hotéis parceiros da Hurb tenham acesso a sua página correspondente a sua conta de acesso, e então, após o login ter sido efetuado, conseguem ter acesso a plataforma para fazer a solicitação da antecipação de pagamento, escolhendo primeiramente para qual hotel quer solicitar, qual o valor que quer antecipar (consequentemente aparece quantas reservas são equivalentes a esse valor) e por último qual o tipo de demanda o usuário quer, podendo escolher entre (D+2, D+7, D+15). Caso ele escolha D+2, terá um desconto de 12% do total devido ao fornecedor, se for D+7, terá um desconto de 9% do total e se for D+15, terá um desconto de 6% do total devido ao fornecedor. Além de os hotéis parceiros conseguirem fazer o cadastro na plataforma para receber esse serviço, conseguem editar seus dados, adicionar os seus hotéis, podem solicitar como também acompanhar o status da solicitação das antecipações e podem visualizar seus histórico, o qual mostra o tipo da demanda escolhido, a data, o valor solicitado e o valor total.

Além do painel dos parceiros da Hurb, tem também o próprio painel de controle da Hurb, em que a equipe responsável pelas finanças e contas da Hurb terão acesso e poderão ter uma visão geral de todo o processo de antecipação, sendo possível visualizar qual tipo de demanda está sendo mais escolhida. Três colunas serão mostradas nessa tela, cada uma correspondente às demandas, apresentando qual foi a quantidade de vezes que ela foi escolhida, o valor solicitado nos últimos meses, a média anual do valor, a data e o valor dos próximos pagamentos, além de ser apresentado um ranking, o qual mostrará em 1º lugar o hotel que realizou a maior quantidade de solicitações. Por fim, um gráfico será apresentado para a equipe de contas a pagar, mostrando a rentabilidade anual.

## 📁 Estrutura de pastas

```
-Raiz
|
|-->documentos —> contém todos os documentos do projeto, principalmente o WAD.
 |-->antigos
   | T4_G3_V01_Web_application_document.pdf 
 |WAD.docx —> Trata-se de uma documentação da nossa aplicação web, em que mencionamos a visão geral do projeto, a empresa que é nossa cliente, o problema, que é o fato das antecipações estarem ocorrendo de forma manual, portanto, com a nossa plataforma web, será possível realizar as antecipações de pagamento de forma digital. Nessa documentação também citamos os objetivos gerais, descrevemos a solução, mencionamos as partes interessadas, analisamos a indústria, o produto, o cenário, entre outros. É nessa documentação que contém a nossa Matriz SWOT, nossa Proposta de Valor, Matriz de Risco, Requisitos do Sistema, nossos Personas, Histórias dos usuários (user stories), Tecnologias Utilizadas, Análise de Dados, Manual do Usuário e do Administrador, Referências, entre outros.
|-->imagens —> Nesta pasta temos as imagens do projeto, portanto todas as capturas de tela da nossa aplicação web, desde quando se inicia o login, até o relatório final estão nessa pasta.
|-->src —> Contém todo o código fonte do sistema. Existem duas pastas, Backend (código do servidor) e Frontend (código da página web.mj).
 |-->Backend 
         |--> controllers
             | index
         |--> database
            | cli
                  |--> mock.data
                  |--> show.data
                  |--> start
             | database
             | index 
         |--> node_modules
         |--> routes
            | index
        |--> services
            | index
        |--> views
            | Assets
                 |--> hurb-icon
                 |--> hurb-logo
                 |--> image1
                 |--> image2
                 |--> image3
            | Authentication
                 |--> index
                 |--> script
                 |--> styles
            | Dashboard
                 |--> index
                 |--> script
                 |--> solicitationCard
                 |--> styles
            | HurbControl
                 |--> index 
                 |--> script
                 |--> styles
            | Profile
                 |--> index
                 |--> script
                 |--> styles
            | global.styles
        |--> index 
        |--> package
        |--> package-lock
        |--> yarn,lock
 |-->Frontend
        |--> Assets
        |--> Authentication
        |--> Dashboard
        |--> HurbDashboard
        |--> Profile
        |--> global.styles
| README.md —> Arquivo que serve como guia e explicação geral sobre seu projeto.

```

## 💻 Configuração para desenvolvimento

Aqui encontram-se todas as instruções necessárias para a instalação de todos os programas, bibliotecas e ferramentas imprescindíveis para a configuração do ambiente de desenvolvimento.

1. Baixar e instalar o node.js: https://nodejs.org/pt-br/ (versão 16.15.1 LTS)
2. Clone o repositório em questão.
3. No modo administrador, abra o "prompt de comando" ou o "terminal" e, após, abra a pasta "src/backend" no diretório raiz do repositório clonado e digite o segundo comando:

npm install

Isso instalará todas as dependências definidas no arquivo package.json que são necessárias para rodar o projeto. Agora o projeto já está pronto para ser modificado. Caso ainda deseje iniciar a aplicação, digite o comando abaixo no terminal:

npm start

5. Agora você pode acessar a aplicação através do link http://localhost:1234/
6. O servidor está online.

## 🗃 Histórico de lançamentos

* 0.0.1 - 22/04/2022
    * Primeiro Commit do grupo;
    * Organização da pasta Github, contendo as pastas necessárias, cuja cópia foi feita, com isso, foi direto para a máquina de cada membro do grupo.
* 0.1.0 - 01/05/2022
    * Adicionado a versão 1.1 do WAD;
* 0.1.1 - 07/05/2022
    * Adicionado o modal de introdução;
* 0.1.2 - 09/05/2022
    * Adicionado o padrão de design do projeto e o código Frontend;
* 0.1.3 - 12/05/2022
    * Painel do Hurb finalizado;
* 0.1.4 - 13/05/2022
    * Adicionado a versão 1.2 do WAD em pdf;
* 0.1.5 - 14/05/2022
    * Recurso javascript de currículo adicionado;
* 0.1.6 - 18/05/2022
    * Update README.md;
* 0.1.7 - 24/05/2022
    * Iniciado o servidor do projeto e uma nova tela;
* 0.1.8 - 24/05/2022
    * Adicionado a tela de autenticação da aplicação web;
* 0.1.9 - 24/05/2022
    * Ajustes do conteúdo do script de autenticação;
* 0.2.0 - 26/05/2022
    * Adicionado as rotas da aplicação web (routes app);
* 0.2.1 - 26/05/2022
    * Adicionado o banco de dados e aplicativo de serviços (database and services app);
* 0.2.2 - 26/05/2022
    * Adicionado a camada de controle (controllers);
* 0.2.3 - 27/05/2022
    * Ajuste nas rotas da aplicação web;
* 0.2.4 - 31/05/2022
    * Adicionado a versão 1.3 do WAD em pdf;
* 0.2.5 - 01/06/2022
    * Adicionado novas rotas da aplicação web;
* 0.2.6 - 07/06/2022
    * Tratamento de cors adicionado;
* 0.2.7 - 07/06/2022
    * Adicionado proprietário da atualização (added update owner);
* 0.2.8 - 08/06/2022
    * Adicionado o painel vinculado (dashboard);
* 0.2.9 - 08/06/2022
    * Adicionado Frontend de solicitação de atualização de perfil;
* 0.3.0 - 08/06/2022
    * Adicionado os últimos endpoint;
* 0.3.1 - 08/06/2022
    * Adicionado cartão de solicitação;
* 0.3.2 - 09/06/2022
    * Adicionado as rotas estáticas;
* 0.3.3 - 09/06/2022
    * Página de autenticação com Backend concluído;
* 0.3.4 - 10/06/2022
    * Done mcv arch, and done bind front-end routes;

## 📋 Licença/License

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/Spidus/Teste_Final_1">MODELO GIT INTELI</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://www.yggbrasil.com.br/vr">Inteli, Allan Casado, Giovane Andreussi, Jackson Aguiar, João Gonzales, Larissa Carvalho, Vitor Augusto</a> is licensed under <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>

## 🎓 Referências

Aqui estão as referências usadas no projeto:

1. https://www.nngroup.com/articles/user-story-mapping/
2. https://aelaschool.com/designdeinteracao/wireframe-o-que-e-como-desenhar/
3. https://getbootstrap.com/docs/5.1/components/accordion/
4. https://integrada.minhabiblioteca.com.br/reader/books/9788536533100/pageid/44
5. https://www.youtube.com/watch?v=C2pPCRGQcl0
6. https://www.youtube.com/watch?v=5tIU5mmL6Vw
7. https://www.youtube.com/watch?v=Kz6PjB5s4W8
8. https://www.devmedia.com.br/tutorial-sql/2973
9. https://integrada.minhabiblioteca.com.br/reader/books/9786556900186/pageid/30
10. https://www.youtube.com/watch?v=mRqe3ShlQtA
11. https://integrada.minhabiblioteca.com.br/reader/books/9788595157552/epubcfi/6/28[%3Bvnd.vst.idref%3Dchapter2]!/4
12. https://www.youtube.com/watch?v=cQoGow-UwDc
13. https://github.com/Intelihub/Tutorial_M2/tree/main/SEMANA_09/02_TUTORIAL
14. https://getbootstrap.com/ 
