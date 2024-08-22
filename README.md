Projeto de Login de Usuário
Descrição

Este projeto é um sistema de login de usuário desenvolvido em Java. O objetivo é permitir que os usuários se registrem e façam login com suas credenciais. O sistema utiliza uma conexão com um banco de dados MySQL para gerenciar e armazenar informações de usuários, incluindo nome, CPF e senha.
Estrutura do Projeto
Classe Usuario

A classe Usuario representa um usuário no sistema de login. Ela contém os atributos e métodos necessários para gerenciar as informações do usuário.
Atributos

    nome: O nome do usuário.
    cpf: O CPF (Cadastro de Pessoa Física) do usuário.
    senha: A senha do usuário.

Métodos

    getNome(): Retorna o nome do usuário.
    setNome(String nome): Define o nome do usuário.
    getCpf(): Retorna o CPF do usuário.
    setCpf(String cpf): Define o CPF do usuário.
    getSenha(): Retorna a senha do usuário.
    setSenha(String senha): Define a senha do usuário.

Dependências

    Java 8 ou superior
    MySQL para gerenciamento de banco de dados

Configuração e Execução
Configuração do Banco de Dados

    Instalar MySQL: Certifique-se de que o MySQL está instalado e em execução em seu ambiente.
    Criar Banco de Dados: Crie um banco de dados para o projeto e configure as tabelas necessárias para armazenar as informações do usuário.
    Configurar Conexão: Certifique-se de que a classe ConexaoMySql está configurada corretamente para conectar ao seu banco de dados MySQL.

Compilação e Execução

    Compilar o Projeto:
        Certifique-se de que o Java está instalado e disponível no seu PATH.
        Compile o código fonte:

        bash

    javac -d bin src/br/com/angeloproject/login_project/model/Usuario.java

Executar o Projeto:

    Execute o projeto com:

    bash

        java -cp bin br.com.angeloproject.login_project.model.Usuario

Contribuição

Se desejar contribuir para o projeto, por favor faça um fork do repositório e envie um pull request com suas alterações.
