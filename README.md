# Library Manager

![Node.js](https://img.shields.io/badge/node-%3E%3D18-green)
![CLI](https://img.shields.io/badge/type-CLI-blue)
![JSON](https://img.shields.io/badge/storage-JSON-orange)
![ESModules](https://img.shields.io/badge/modules-ESM-yellow)
![License](https://img.shields.io/badge/license-MIT-informational)

## Descrição

O **Library Manager** é uma aplicação de linha de comando desenvolvida em Node.js para gerenciamento de uma biblioteca pessoal.

O projeto permite cadastrar, listar, atualizar e remover livros diretamente pelo terminal através de um menu interativo, armazenando todas as informações em um arquivo JSON para persistência de dados.

A aplicação foi criada com foco em prática de conceitos fundamentais de JavaScript moderno e Node.js, incluindo manipulação de arquivos, operações CRUD, modularização, recursão e interação via terminal utilizando o módulo `readline`.

---

## Tecnologias utilizadas

| Tecnologia | Versão | Função |
|---|---|---|
| [Node.js](https://nodejs.org/) | >= 18 | Ambiente de execução JavaScript |
| `readline` | Nativo | Entrada e interação via terminal |
| JSON | Nativo | Persistência de dados |
| ES Modules | Nativo | Sistema moderno de módulos (`import/export`) |
| `fs/promises` | Nativo | Manipulação assíncrona de arquivos |

A aplicação utiliza persistência local através de arquivos JSON e arquitetura modular utilizando ES Modules.

---

## Estrutura do projeto

```bash
library_manager/
├── index.js            # Ponto de entrada da aplicação
├── app.js              # Gerenciamento do menu e fluxo da aplicação
├── utils.js            # Funções utilitárias e operações CRUD
├── livros.json         # Persistência dos dados da biblioteca
└── README.md
```

---

## Funcionalidades

| Funcionalidade | Descrição |
|---|---|
| Adicionar livros | Cadastro de novos livros |
| Listar livros | Exibição de todos os livros cadastrados |
| Atualizar status | Marcar livros como lidos ou não lidos |
| Remover livros | Exclusão de livros da biblioteca |
| Menu interativo | Navegação amigável via terminal |
| Persistência local | Armazenamento dos dados em JSON |

---

## Funcionalidades e diferenciais

- **CLI interativa** — Navegação amigável através de menus no terminal.
- **Persistência em JSON** — Dados armazenados localmente em arquivo JSON.
- **Operações CRUD completas** — Criação, leitura, atualização e remoção de livros.
- **Arquitetura modular** — Separação entre fluxo da aplicação e regras utilitárias.
- **Programação assíncrona** — Manipulação de arquivos utilizando recursos assíncronos.
- **Tratamento de erros** — Implementação de `try/catch` para maior robustez.
- **Recursão** — Utilização de funções recursivas para fluxo de entrada de dados.
- **ES Modules** — Utilização de `import/export` nativamente.
- **Manipulação de JSON** — Uso de `JSON.parse()` e `JSON.stringify()`.
- **Aplicação multiplataforma** — Compatível com Windows, Linux e macOS.

---

## Como executar o projeto

### Pré-requisitos

- [Node.js](https://nodejs.org/) v18 ou superior

### Passo a passo

**1. Clone o repositório e acesse a pasta do projeto:**

```bash
git clone <url-do-repositorio>
cd library_manager
```

---

**2. Execute a aplicação:**

```bash
node index.js
```

Após iniciar a aplicação, o menu interativo será exibido no terminal.

---

## Observações

- O projeto foi desenvolvido com foco em prática de JavaScript moderno e Node.js.
- Os dados da biblioteca são armazenados localmente no arquivo `livros.json`.
- A aplicação utiliza o módulo nativo `readline` para interação via terminal.
- O projeto implementa operações CRUD completas para gerenciamento dos livros.
- O código utiliza modularização com ES Modules e manipulação de arquivos JSON.
- O menu da aplicação funciona de forma totalmente interativa no terminal.

---

## Licença

Este projeto está sob a licença [MIT](https://opensource.org/licenses/MIT).

---

*Desenvolvido por **Ygor Santos** — [LinkedIn](https://www.linkedin.com/in/ygor-santos-869152325/) | [GitHub](https://github.com/ygorzz)*
