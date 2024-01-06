# Task List

O **Task List** é um projeto que se concentra na criação, atualização, exclusão e leitura de tarefas, formando um CRUD completo. Desenvolvido utilizando Laravel, Blade Template, Tailwind, Docker e MySQL, o projeto oferece uma experiência prática e abrangente no desenvolvimento web.

## Tecnologias Utilizadas

- Laravel
- Blade Template
- Tailwind
- Docker
- MySQL

## Funcionalidades do Projeto

O projeto foi estruturado para explorar diversas funcionalidades do Laravel, proporcionando um aprendizado abrangente. Abaixo estão alguns dos conceitos e técnicas estudados e aplicados:

- **Rotas:** Configuração e utilização de rotas para mapear as diferentes ações e funcionalidades do CRUD.

- **Templates Blade:** Desenvolvimento de templates Blade para estruturação e renderização de views de maneira eficiente e reutilizável.

- **Layouts:** Utilização de layouts para garantir uma consistência visual em toda a aplicação.

- **Docker:** Configuração e utilização do Docker para facilitar o ambiente de desenvolvimento, incluindo a execução de um banco de dados MySQL.

- **MySQL:** Integração de um banco de dados MySQL para armazenar e gerenciar as tarefas do CRUD.

- **Models e Migrations:** Criação e utilização de modelos e migrações para definir a estrutura do banco de dados e interagir com ele.

- **Forms e CSRF Protection:** Implementação de formulários para entrada de dados, garantindo a proteção contra ataques CSRF.

- **Validação de Input:** Aplicação de validações para garantir a integridade dos dados inseridos no sistema.

- **Mensagens Flash com Alpine.js:** Utilização de Alpine.js para exibição de mensagens flash, proporcionando uma experiência mais interativa ao usuário.

## Como Executar o Projeto

Para executar o projeto, siga os passos abaixo:

1. Clone o repositório para o seu ambiente local.
2. Certifique-se de ter o Docker instalado em sua máquina.
3. Execute o comando `docker-compose up -d` para iniciar os containers.
4. Acesse a aplicação em [http://localhost](http://localhost) em seu navegador.

## Restaurando Dependências e Executando o Laravel

Para garantir que todas as dependências do projeto estejam instaladas e o Laravel esteja pronto para ser executado, 
siga os passos abaixo:

### 1. Restaurar Dependências com Composer

No diretório do seu projeto, execute o seguinte comando para instalar as dependências do Composer:

composer install

### 2. Executar as Migrações

php artisan migrate 

### Em seguida, poderá utilizar o servidor embutido para rodar o projeto, com o comando:

php artisan serve

Agora, você está pronto para explorar e interagir com o **Task List**!
