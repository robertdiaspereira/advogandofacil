# Advogando Fácil

![Badge de Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)

## 🎯 Sobre o Projeto

**Advogando Fácil** é um sistema de gestão para advogados e escritórios de advocacia, projetado para simplificar a rotina jurídica, otimizar o tempo e centralizar as informações importantes de processos e clientes.

O objetivo é fornecer uma ferramenta intuitiva para o controle de prazos, faturamento, documentos e comunicação com o cliente.

---

## ✨ Funcionalidades Planejadas

-   [ ] **Gestão de Processos:** Cadastro e acompanhamento detalhado de cada caso.
-   [ ] **Cadastro de Clientes:** Mantenha um registro completo dos seus clientes.
-   [ ] **Controle de Prazos:** Agenda e calendário para não perder nenhuma data importante.
-   [ ] **Faturamento:** Geração de cobranças e integração com pagamentos online (via Stripe).
-   [ ] **Gestão de Documentos:** Armazene e organize os arquivos de cada processo de forma segura.
-   [ ] **Dashboard:** Visão geral com os principais indicadores e próximos prazos.

---

## 🛠️ Tecnologias Utilizadas

O projeto está sendo construído com as seguintes tecnologias:

-   **Backend:** PHP
-   **Banco de Dados:** MySQL / MariaDB
-   **Servidor Web:** Apache (utilizando XAMPP para desenvolvimento)
-   **Gateway de Pagamento:** [Stripe](https://stripe.com/br)
-   **Gerenciador de Dependências:** [Composer](https://getcomposer.org/)
-   **Frontend:** HTML, CSS, JavaScript

---

## 🚀 Como Executar o Projeto

Siga os passos abaixo para configurar o ambiente de desenvolvimento.

### Pré-requisitos

-   [Git](https://git-scm.com/)
-   [XAMPP](https://www.apachefriends.org/pt_br/index.html) (ou um ambiente similar com Apache, MySQL e PHP)
-   [Composer](https://getcomposer.org/)

### Instalação

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/robertdiaspereira/advogandofacil.git
    cd advogandofacil
    ```

2.  **Instale as dependências do PHP:**
    ```bash
    composer install
    ```

3.  **Configure o Banco de Dados:**
    -   Inicie o Apache e o MySQL no seu painel XAMPP.
    -   Crie um novo banco de dados (ex: `advogandofacil`) através do `phpMyAdmin`.

4.  **Configure as Variáveis de Ambiente:**
    -   *Recomenda-se criar um arquivo `.env` para armazenar as credenciais do banco de dados e as chaves da API do Stripe.*

5.  **Acesse o projeto:**
    -   Abra seu navegador e acesse `http://localhost/advogandofacil`.

---

## 🤝 Como Contribuir

Contribuições são bem-vindas! Se você tem alguma ideia para melhorar o projeto, sinta-se à vontade para criar um *fork* e abrir um *Pull Request*.

1.  Faça um Fork do projeto
2.  Crie uma Branch para sua feature (`git checkout -b feature/MinhaFeature`)
3.  Faça o Commit de suas mudanças (`git commit -m 'feat: Adiciona MinhaFeature'`)
4.  Faça o Push para a Branch (`git push origin feature/MinhaFeature`)
5.  Abra um Pull Request