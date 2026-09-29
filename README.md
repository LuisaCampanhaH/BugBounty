<div align="center">

# 🕵️ Bug Bounty

**Aprenda cibersegurança e lógica de programação investigando casos como um mercenário digital.**

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow?style=for-the-badge)
![ODS 4](https://img.shields.io/badge/ODS%204-Educa%C3%A7%C3%A3o%20de%20Qualidade-c5192d?style=for-the-badge)

</div>

---

## 📖 Sobre o projeto

Cibersegurança e lógica de programação costumam ser vistas como abstratas,
técnicas demais ou chatas, principalmente por quem está começando.

**Bug Bounty** é um app educativo em Flutter que transforma esses temas em um
jogo de investigação. O jogador é um **"mercenário digital"** contratado para
encontrar falhas de segurança em empresas fictícias, sem precisar de
conhecimento técnico prévio e com dificuldade progressiva.

> Projeto desenvolvido para a disciplina **Trabalho Interdisciplinar IV**
> (Ciência da Computação — PUC Minas).

> ⚠️ **Aviso:** todas as empresas, sistemas e vulnerabilidades do jogo são
> **fictícios e simulados**. O app não interage com sistemas reais.

## 🎮 Como funciona

Cada caso tem uma narrativa de detetive, com contrato e cliente fictícios, e
se divide em duas etapas:

1. **Infiltração** — investigação e dedução: o jogador coleta pistas dentro
   de um ambiente simulado.
2. **Exploit** — um quebra-cabeça de lógica para explorar a vulnerabilidade
   encontrada.

No final, o jogador escreve um **report** explicando qual era a vulnerabilidade
e **como corrigi-la**, como faria um profissional da área.

## 📱 Telas

O app simula um "sistema operacional falso" dentro do celular. A navegação
dentro de um caso usa um rodapé fixo, presente em todas as telas.

| Tela | Função |
|---|---|
| **Login / Cadastro** | Acesso do jogador |
| **Lista de Casos** | Escolha do caso a investigar |
| **Mesa de Investigação** | Tela central (hub) de cada caso |
| **Arquivo do Caso** | Contrato, cliente e informações do caso |
| **Terminal** | Terminal simulado para investigar |
| **Acesso Rápido** | Apps falsos: Google, banco de dados e app de imagem |
| **Manual** | Conteúdo educativo de apoio |
| **Report** | O jogador escreve a vulnerabilidade e a correção |

## 🔐 O que você aprende

- **SQL Injection**
- **XSS** (Cross-Site Scripting)
- **IDOR** (Insecure Direct Object Reference)
- **Engenharia social**

## 🤖 IA adaptativa

O projeto terá uma IA que analisa o desempenho do jogador (acertos, erros e
tempo de resposta) e ajusta a **dificuldade dos puzzles** e o **nível de
dicas** de acordo com ele.

> Status: em desenvolvimento.

## 🌍 Alinhamento com a ONU

O projeto se alinha ao **ODS 4 — Educação de Qualidade**, ao tornar acessível
um conteúdo normalmente visto como difícil ou distante do público leigo.

## 🖼️ Screenshots

<!-- Adicione imagens em docs/ e referencie assim: -->
<!-- ![Mesa de Investigação](docs/mesa-de-investigacao.png) -->

*Em breve.*

## 🛠️ Tecnologias

- [Flutter](https://flutter.dev) / Dart
- [Figma](https://figma.com) — protótipo e design das telas: `<link do Figma>`
- IA adaptativa: `<linguagem/biblioteca>`

## 🚀 Como rodar

**Pré-requisitos:** [Flutter SDK](https://docs.flutter.dev/get-started/install)
`<versão>` instalado. Confira o ambiente com `flutter doctor`.

```bash
# 1. Clone o repositório
git clone https://github.com/LuisaCampanhaH/<nome-do-repositorio>.git
cd <nome-do-repositorio>

# 2. Instale as dependências
flutter pub get

# 3. Rode o app (com um emulador aberto ou um celular conectado)
flutter run
```

## 📂 Estrutura do projeto

```
<nome-do-repositorio>/
├── lib/        # código-fonte do app (telas, widgets, lógica)
├── assets/     # imagens, fontes e conteúdo dos casos
├── test/       # testes
└── docs/       # screenshots e documentação
```



## 👥 Equipe

| Nome | GitHub |
|---|---|
| Luisa Campanha | [@LuisaCampanhaH](https://github.com/LuisaCampanhaH) |


