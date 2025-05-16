# Orion CRUD Clients - app4.v2

Aplicação web PHP para gerenciamento de clientes utilizando Amazon DynamoDB para armazenamento de dados, Amazon S3 para armazenamento de fotos e o SDK da AWS para PHP.

**Tecnologias:**

*   Amazon EC2
*   AMI Linux
*   AWS CLI
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
4. Implementar a aplicação usando conteiners do ECS no fargate.


![Diagrama da Arquitetura](https://github.com/ralexandrecode/Orion-Applicacao-de-Registros-com-Foto/blob/main/digrama1-app4.v2.png)
# Conecte-se comigo: 🤝🏽
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ricardoalexandreprofissional/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ralexandrecode)
[![AWS](https://img.shields.io/badge/AWS-000.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)](https://www.credly.com/users/ricardoalexandre.profissional/badges)
[![My profile DIO](https://img.shields.io/badge/-Meu%20Perfil%20na%20DIO-30A3DER?style=for-the-badge)](https://www.dio.me/users/ricardoalexandre_profissional)
