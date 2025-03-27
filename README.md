<a href="https://www.redeparcerias.com">
  <img width="200" src="https://redeparcerias.com/wp-content/uploads/2023/09/rede-parcerias-vertical.svg"/>
</a>

# 🚀 Desafio: Fullstack Pleno - Rede Parcerias  

Bem-vindo ao  **Desafio Dev Fullstack Pleno da Rede Parcerias!**  🐱‍💻

Seu objetivo é desenvolver um  **sistema de controle de estoque**, criando um backend em  **Laravel**, um frontend com  **React + Inertia.js**, e utilizando um  **Banco de Dados Relacional**.

## 🎯 Requisitos do Desafio
   🔐 **Autenticação e Controle de Acesso (ACL)**  

-   Implementar  **cadastro e login de usuários**.
-   Criar diferentes  **níveis de acesso**:
    -   **Administrador**: pode criar, editar e excluir produtos.
    -   **Operador**: pode visualizar e atualizar o estoque, mas não pode criar ou excluir produtos.
    -   **Usuário comum**: pode apenas visualizar os produtos.

📦 **CRUD de Estoque**  

-   Deve ser possível cadastrar, visualizar, atualizar e excluir itens do estoque.
-   Cada item deve conter as seguintes informações:
    -   **ID**  (gerado automaticamente)
    -   **Nome do produto**
    -   **Descrição**
    -   **Quantidade disponível**
    -   **Preço**
    -   **Categoria**
    -   **Código SKU**  (único por produto)
    -   **Data de criação e atualização**

🛰️ **API de Estoque**  

-   Garantir  **versionamento da API**  (exemplo:  `/api/v1/produtos`).
-   A API de consulta ao estoque deve exigir **autenticação via JWT**.

🖥️ **Frontend**  

-   Criar uma interface amigável e responsiva utilizando  **React + Inertia.js**.
-   O usuário deve conseguir:
    -   **Visualizar a listagem dos produtos**
    -   **Filtrar produtos por categoria, nome ou faixa de preço**
    -   **Cadastrar novos produtos**  (se tiver permissão)
    -   **Editar e excluir produtos**  (se tiver permissão)
    -   **Atualizar a quantidade de produtos no estoque**

🎨 **Estilização**  

-   O layout deve ser desenvolvido com  **Styled-components**  e  **Tailwind CSS**.
-   A interface deve ser  **responsiva e intuitiva**.


## 🧐 O que será avaliado

Queremos avaliar a sua capacidade de construir um sistema completo e escalável. Os principais pontos que serão analisados:

- Estrutura do projeto bem organizada seguindo boas práticas do Laravel.
- Arquitetura REST deve seguir corretamente os princípios RESTful.
- Uso do Git com commits bem organizados e mensagens claras para um histórico compreensível.
- Documentação explicando detalhadamente como rodar e utilizar o sistema.
- Testes unitários e/ou de integração para garantir a confiabilidade do software.
- Banco de dados com modelagem eficiente e queries otimizadas para melhor desempenho.
- Tratamento de erros garantindo mensagens claras e apropriadas, além de códigos de status corretos para cada situação.
- Observabilidade através de logs e métricas bem definidos para facilitar manutenção e depuração.

## 🎩 Diferenciais (Quer se destacar? Faça isso!!)
- Código limpo e organizado, com nomeação adequada de variáveis, estrutura bem definida e boas práticas.
- Implementação de **migrations e seeders** no Laravel para facilitar a configuração do ambiente.
- Conhecimento e aplicação de SOLID.
- Uso eficiente de cache para melhorar a performance.
- Deploy do projeto para demonstração.
- Assegurar a proteção dos dados e do sistema contra vulnerabilidades como SQL Injection e XSS.
