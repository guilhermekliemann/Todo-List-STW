# # Todo List feito em Vue e Laravel

Desafio era completar a sequência de vídeos para fazer um todo list para a empresa STW Automação, o desafio foi proposto para aprimorar as minhas habilidades técnicas, pois não tinha conhecimento em ambas as linguagens, o sistema contem um CRUD de um Todo List e tem autenticação de usuário.

O sistema contém as seguintes funcionalidades:

- Uma página "Home" só com uma imagem;
- Página "App" com o Todo List, com a opção de adicionar nova tarefa, remover, listar e editar;
- Página "About" só com uma imagem;
- Página de "Login" para logar um usuário cadastrado, para ter acesso ao "App";
- Página de "Register" para cadastrar um novo usuario;
- E um botão de "Logout" para deslogar da conta e tirar o acesso ao "App".

Para rodar tem que dar um "git clone" no repositório, colocar a pasta "todo-laravel" dentro da pasta "www" do laragon para linkar com o banco de dados, após isso é só cria um ".env" do laravel e colocar um database local, e no laravel rodar o comando "php artisan migrate" para realizar a criação das tabelas, a e ai no front-end é só rodar o comando "npm run dev", que tudo irá funcionar corretamente.
