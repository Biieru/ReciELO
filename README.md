# ReciELO

**Protótipo de plataforma de participação comunitária e interação entre cidadãos.**

Projeto acadêmico desenvolvido com HTML, CSS e modelagem de banco de dados MySQL, com foco na construção de interfaces e na estruturação de uma plataforma de participação social.

## Sobre o projeto

O ReciELO nasceu da proposta de criar um ambiente digital para aproximar cidadãos e estimular a participação comunitária.

A ideia é oferecer um espaço em que usuários possam compartilhar informações, contribuir com discussões, participar de votações e interagir com assuntos de interesse coletivo.

Nesta etapa, o projeto contempla protótipos das interfaces de autenticação, cadastro e perfil, além de uma proposta inicial de estrutura relacional para o banco de dados.

## Tecnologias

| Tecnologia | Aplicação |
|---|---|
| HTML5 | Estrutura das interfaces |
| CSS3 | Estilização e layout |
| Bootstrap 4 | Componentes e estilização da tela de perfil |
| MySQL | Modelagem do banco de dados relacional |
| SQL | Definição de tabelas e relacionamentos |
| Git e GitHub | Versionamento do projeto |

## Interfaces desenvolvidas

### Login

Tela de entrada com campos de CPF e senha, opção de lembrar dados e links para cadastro e recuperação de acesso.

### Registro

Formulário de cadastro com campos para informações pessoais, contato, senha e gênero.

### Perfil

Interface demonstrativa com informações do usuário e indicadores de participação, incluindo:

- Contribuições realizadas.
- Avaliações positivas e negativas.
- Feedbacks recebidos.
- Informações pessoais e biografia.

Os dados apresentados no perfil são demonstrativos.

## Modelagem do banco de dados

O projeto inclui um script SQL com a estrutura inicial de sete tabelas:

| Tabela | Finalidade |
|---|---|
| `users` | Cadastro de usuários |
| `profiles` | Informações de perfil |
| `votes` | Votações criadas |
| `vote_options` | Alternativas das votações |
| `posts` | Publicações da comunidade |
| `comments` | Comentários em publicações |
| `news` | Notícias e informações |

A modelagem utiliza chaves primárias e estrangeiras para representar relacionamentos entre usuários, perfis, publicações, comentários e votações.

O script representa uma proposta inicial, ainda não integrada às interfaces.

## Estrutura do projeto

```text
ReciELO/
├── Login/
│   ├── Login.html
│   └── Login.css
├── Registro/
│   ├── Registro.html
│   └── Registro.css
├── Perfil/
│   ├── Perfil.html
│   └── Perfil.css
├── database/
│   └── recielo.sql
├── images/
├── VERSAO ANTIGA- NAO USE/
└── README.md
```

## Como executar

Clone o repositório:

```bash
git clone https://github.com/Biieru/ReciELO.git
cd ReciELO
```

Abra a tela inicial de login:

```text
Login/Login.html
```

As interfaces podem ser visualizadas diretamente em um navegador, sem instalação de dependências.

Para estudar a estrutura do banco de dados, consulte:

```text
database/recielo.sql
```

O script pode ser executado em um ambiente MySQL compatível.

## Estado atual

**Status: protótipo acadêmico em desenvolvimento.**

O repositório contém interfaces estáticas e um modelo inicial de banco de dados.

Ainda não foram implementados:

- Autenticação real de usuários.
- Integração entre formulários e banco de dados.
- Persistência dos cadastros.
- Publicação e gerenciamento de conteúdo.
- Sistema funcional de votação.
- Controle de permissões e sessões.

As telas demonstram a proposta visual e a organização inicial da aplicação.

## Aprendizados

O desenvolvimento do ReciELO permitiu explorar:

- Estruturação de páginas HTML.
- Criação de formulários e componentes CSS.
- Navegação entre páginas.
- Prototipação de interfaces.
- Modelagem de bancos relacionais.
- Criação de tabelas e relacionamentos SQL.
- Planejamento de funcionalidades de uma aplicação web.

## Melhorias futuras

- Implementação de um back-end.
- Integração com MySQL.
- Autenticação e gerenciamento de sessões.
- Validação segura dos formulários.
- Implementação de publicações e comentários.
- Sistema de votações.
- Aprimoramento da responsividade.
- Refatoração e padronização das interfaces.
- Testes automatizados.

## Autoria

Projeto desenvolvido em contexto acadêmico.

**Repositório mantido por Gabriel Coelho de Araújo.**

[GitHub](https://github.com/Biieru) · [Portfólio](https://biieru.github.io/)

---

**HTML · CSS · Bootstrap · SQL · MySQL · Web Development**
