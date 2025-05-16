# Orion CRUD Clients - app4.v2

Aplicação web PHP para gerenciamento de clientes utilizando Amazon DynamoDB para armazenamento de dados, Amazon S3 para armazenamento de fotos e o SDK da AWS para PHP.

**Tecnologias:**

*   PHP 8.1
*   AWS SDK for PHP
*   Amazon DynamoDB
*   Amazon S3
*   HTML, CSS
*   Bootstrap (Opcional, se você usar)

**Instalação e Configuração:**

1.  **Pré-requisitos:**
    *   PHP 8.1+
    *   Composer
    *   Conta AWS com permissões para DynamoDB, S3 e EC2.
    *   Instância EC2 rodando com um servidor web (Apache ou Nginx) e PHP.

2.  **Instalação das Dependências:**

    ```bash
    composer install
    ```

3.  **Configuração da AWS:**
    *   Crie uma tabela no DynamoDB chamada `Clientes`.
    *   Crie um bucket S3 chamado `new-bkt2027`.
    *   Configure as credenciais da AWS na sua instância EC2 (através de um perfil IAM)

4.  **Implantação:**
    *   Copie os arquivos do projeto para o diretório raiz do seu servidor web (ex: `/var/www/html`).

**Como Usar:**

1.  Acesse a aplicação através do seu navegador (ex: `http://<seu_ip_publico>/index.php`).
2.  Use as funcionalidades de cadastro, listagem, edição, exclusão e exportação.
3.  Verifique os arquivos de texto complementares com passos e comandos detalhados.
