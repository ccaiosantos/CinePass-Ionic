# CinePass

<p align="center">
  <strong>Seu cinema. Sua sessão. Seu ingresso.</strong>
</p>

<p align="center">
  Aplicação mobile para explorar filmes, consultar sessões e simular reservas de ingressos de cinema.
</p>

---

## Sobre o projeto

O **CinePass** é um aplicativo mobile desenvolvido como projeto acadêmico, com a proposta de oferecer uma experiência digital de compra e reserva de ingressos de cinema.

Inspirado na experiência de plataformas de cinema como Cinemark e Kinoplex, o aplicativo permite explorar filmes em cartaz, visualizar informações sobre as produções, escolher sessões, selecionar ingressos e assentos, e acompanhar o resumo da reserva.

O projeto utiliza a API do TMDB para obter informações sobre filmes, enquanto o fluxo de sessões e reservas é simulado localmente.

## Funcionalidades

- [x] Interface mobile com Ionic
- [x] Navegação entre páginas
- [x] Página inicial com filmes em destaque
- [x] Listagem de filmes populares
- [x] Detalhes dos filmes
- [x] Integração com API de filmes (TMDB)
- [x] Seleção de sessões
- [x] Seleção de tipos e quantidade de ingressos
- [x] Seleção de poltronas
- [x] Resumo da reserva
- [x] Persistência de reservas com LocalStorage
- [x] Página da equipe de desenvolvimento

## Tecnologias utilizadas

| Tecnologia | Descrição |
|---|---|
| Ionic Framework | Desenvolvimento da interface mobile |
| Angular | Framework da aplicação |
| TypeScript | Linguagem de desenvolvimento |
| SCSS | Estilização da interface |
| Angular Router | Navegação entre páginas |
| TMDB API | Dados e informações sobre filmes |
| LocalStorage | Persistência local das reservas |

## API

O CinePass utiliza a API do **The Movie Database (TMDB)** para consultar informações de filmes, incluindo títulos, sinopses, avaliações, imagens e filmes populares.

Endpoints utilizados:

- Filmes em cartaz.
- Filmes populares
- Detalhes de um filme específico

Documentação oficial: [TMDB API](https://developer.themoviedb.org/docs)

## Instalação e execução

### Pré-requisitos

- Node.js
- npm
- Ionic CLI

### 1. Clone o repositório

```bash
git clone https://github.com/SEU-USUARIO/CinePass.git
```

### 2. Acesse a pasta do projeto

```bash
cd CinePass
```

### 3. Instale as dependências

```bash
npm install
```

### 4. Execute a aplicação

```bash
ionic serve
```

A aplicação estará disponível localmente no endereço exibido pelo terminal.

## Estrutura do projeto

```text
src/
├── app/
│   ├── core/
│   │   ├── models/
│   │   └── services/
│   │ ├── components/
│   │ ├── pages/
│   │ │   ├── home/
│   │ │   ├── filmes/
│   │ │   ├── detalhes/
│   │ │   ├── sessoes/
│   │ │   ├── ingressos/
│   │ │   ├── poltronas/
│   │ │   ├── resumo/
│   │ │   └── equipe/
│   │ ├── pipes/
│   │ ├── directives/
│   │ └── app.routes.ts
├── assets/
├── theme/
└── environments/
```

## Fluxo de reserva

```text
Home
  ↓
Filmes
  ↓
Detalhes do filme
  ↓
Sessões
  ↓
Ingressos
  ↓
Poltronas
  ↓
Resumo da reserva
```

## Equipe de desenvolvimento

| Integrante | Responsabilidade |
|---|---|
| Caio Gabriel | Integração e estrutura |
| Caio Marcos | API e Services |
| Victor Alves | Sessões e ingressos |
| Pedro Luckas | Poltronas e reservas |
| Vitor | Pipes, diretivas e finalização |

## Observações

- O projeto possui finalidade acadêmica.
- As sessões, salas e disponibilidade de assentos são simuladas.
- Não existe integração com sistemas reais de cinemas.
- A finalização da reserva não envolve processamento real de pagamentos.
- Os dados de filmes são obtidos através da API do TMDB.

---

<p align="center">
  Desenvolvido com dedicação pela equipe CinePass.
</p>
