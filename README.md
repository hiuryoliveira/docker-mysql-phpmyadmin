### Docker MySQL

Este repositório contém arquivos de configuração para executar o MySQL e o phpMyAdmin usando o Docker.

## Pré-requisitos
Certifique-se de ter o Docker instalado em sua máquina antes de prosseguir.

## Configuração
1. Clone este repositório em sua máquina local.
2. Navegue até o diretório do projeto: `/Users/hiury/Workspace/Docker/MySQL`.
3. Abra um terminal e execute o seguinte comando para iniciar o MySQL:
    ```
    docker-compose up -d mysql
    ```
4. Aguarde até que o MySQL esteja em execução.
5. Em seguida, execute o seguinte comando para iniciar o phpMyAdmin:
    ```
    docker-compose up -d phpmyadmin
    ```
6. Aguarde até que o phpMyAdmin esteja em execução.
7. Agora você pode acessar o phpMyAdmin em seu navegador usando o seguinte URL: `http://localhost:8080`.
8. Faça login com as seguintes credenciais:
    - Servidor: `mysql`
    - Usuário: `root`
    - Senha: `password`

## Personalização
Se desejar personalizar as configurações do MySQL ou do phpMyAdmin, você pode editar os arquivos `docker-compose.yml` e `my.cnf` respectivamente.

## Contribuição
Sinta-se à vontade para contribuir com melhorias para este repositório através de pull requests.

## Licença
Este projeto está licenciado sob a [MIT License](LICENSE).