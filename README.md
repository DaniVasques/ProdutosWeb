# ProdutosWeb

Projeto front-end desenvolvido em *Angular* para simular a interface de um *sistema de controle de produtos*.

O objetivo deste projeto é praticar conceitos de desenvolvimento web com Angular, componentização, rotas e organização de páginas, criando a base visual de um sistema com foco em cadastro, consulta e edição de produtos.

---

## Sobre o projeto

O *ProdutosWeb* foi criado como um projeto de estudo prático para reforçar conhecimentos em *Angular, **TypeScript, **HTML, **CSS* e *Bootstrap*.

A aplicação foi estruturada com páginas separadas para:

- *Cadastro de produtos*
- *Consulta de produtos*
- *Edição de produtos*

Além disso, o projeto possui uma *navbar de navegação*, deixando a interface mais organizada e próxima de um sistema real.

---

## Funcionalidades atuais

- Estrutura inicial de um sistema de produtos
- Navegação entre páginas com rotas
- Componente de menu/navbar
- Tela de cadastro de produtos
- Organização por componentes e páginas
- Estrutura preparada para evolução do projeto

---

## Tela de cadastro

A página de cadastro já possui a estrutura de formulário com os seguintes campos:

- Nome do produto
- Preço
- Quantidade
- Categoria

Essa tela foi criada para representar o início de um fluxo de gerenciamento de produtos no front-end.

---

## Tecnologias utilizadas

- Angular
- TypeScript
- HTML5
- CSS3
- Bootstrap

---

## Estrutura do projeto

```bash
src/
 └── app/
     ├── components/
     │   ├── pages/
     │   │   ├── cadastro-produtos/
     │   │   ├── consulta-produtos/
     │   │   └── edicao-produtos/
     │   └── shared/
     │       └── navbar/
     ├── app.component.*
     ├── app.config.ts
     └── app.routes.ts

projeto Feito por Daniela Vasques
