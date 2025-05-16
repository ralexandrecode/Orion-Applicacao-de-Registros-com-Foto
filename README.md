# Orion CRUD Clients - app4.v2

Aplicação web PHP para gerenciamento de clientes utilizando Amazon DynamoDB para armazenamento de dados, Amazon S3 para armazenamento de fotos e o SDK da AWS para PHP.

**Tecnologias:**

*   Amazon EC2
*   AMI Linux
*   PHP 8.4
*   AWS SDK for PHP
*   Amazon DynamoDB
*   Amazon S3
*   HTML, CSS

**Objetivo**

O objetivo é desenvolver um projeto final de formação do curso de arquiteto de soluções que simula a migração e modernização de uma aplicação CRUD em PHP/MySQL rodando em uma máquina virtual na rede local para nuvem utilizando armazenamento altamente escalável e disponível.

**Instalação e Configuração:**

1.  **Pré-requisitos:**
   
    *   PHP 8
    *   Composer
    *   Conta AWS com permissões para DynamoDB, S3 e EC2.
    *   Instância EC2 rodando com um servidor web (Apache ou Nginx) e PHP.

3.  **Instalação das Dependências:**

    ```bash
    composer install
    ```

4.  **Configuração da AWS:**
   
    *   Crie uma tabela no DynamoDB chamada `Clientes`.
    *   Crie um bucket S3 chamado `new-bkt2027`.
    *   Configure as credenciais da AWS na sua instância EC2 (através de um perfil IAM)

5.  **Implantação:**
   
    *   Copie os arquivos do projeto para o diretório raiz do seu servidor web (ex: `/var/www/html`).

**Como Usar:**

1.  Acesse a aplicação através do seu navegador (ex: `http://<seu_ip_publico>/index.php`).
2.  Use as funcionalidades de cadastro, listagem, edição, exclusão e exportação.
3.  Verifique os arquivos de texto complementares com passos e comandos detalhados.

**Sugestões de melhoria**

1. Implementar criptografia em trânsito do protocolo HTTPS através do AWS ACM
3. Instalar os seguintes recursos essenciais: WAF, NACL, ASG, ALB, R53, IAC, 
