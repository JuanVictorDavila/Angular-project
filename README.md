# JuanVictorEnerginAngula

Este projeto foi criado usando [Angular CLI](https://github.com/angular/angular-cli) versão 14.2.9.

## About

Este projeto foi idealizado para uma solução para uma corretora de imovéis fictícia, no qual o sistema deve possuir um login com autenticação JWT para poder obter o acesso ao painel principal em que o corretor de imovéis poderar cadastrar um imovél, editar as informações do seu usuário, obter informações dos imovéis cadastrados e alterar seu status(vendido, alugado ou em estoque).

OBS: Entendo a real importância dos testes, porém, como foi o meu primeiro contato com o framework Angular 2+(até o momento só havia trabalhado com React) eu fui desenvolvendo conforme fui estudando. Mas em breve vou implementar os testes unitários e de integração.

## Development planning

No desenvolvimento deste projeto tentei adotar ao máximo o manifesto ágil, realizando um planejamento do que iria precisar para concluir as tarefas e estabelecendo o backlog. Infelizmente o projeto teve muitos contratempos por ter que parar constantemente para procurar os conhecimentos para superar os desafios e aprender mais sobre Angular .

Na minha próxima sprint eu vou trabalhar na construção de um backend definitivo, pois por motivo de tempo eu fiz um arquivo de mock para simular um backend na pasta `app/_helpers/fake-backend` para realizar o login quardando as informações do usuário em LocalStorage.

Com o backend criado em NodeJs eu vou dar continuidade no desenvolvimento implementando o painel para o CRUD de imovéis e edição de informações de usuário.

## Development status

Neste momento o projeto ainda está incompleto e em desenvolvimento, com a tela de login funcionando com autenticação JWT e armazenado as informações de cadastro de usuário em LocalStorage. Estou em busca de conhecimentos para conluir a montagem do Front usando Angular 2+ após terminar a construção do backend definitivo para este projeto com NodeJs em conjunto com o Express.js para montar o servidor.

## Development server

Rodar o comando `npm start` para o servidor de desenvolvimento. Navegar para o endereço `http://localhost:8080/`. A aplicação irá recarregar automaticamente se houver qualquer mudança nos arquivos da raiz(source files).

## Code scaffolding

Rodar comando `ng generate component component-name` para gerar um novo componente. Você também pode usar o comando `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Rodar comando `ng build` para fazer a nuild do projeto. A build vai ser armazenada no diretório `dist/`.

## Running unit tests

Rodar comando `ng test` para executar os testes unitários via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Rodar comando `ng e2e` para executar os testes end-to-end via plataforma escolhida por você. Para usar este comando, você precisa primeiramente adicionar um pacote que tem a capacidade de implementar os testes end-to-end.

## Further help

Para ter mais informações de Angular CLI use o comando `ng help` ou visite a página [Angular CLI Overview and Command Reference](https://angular.io/cli).