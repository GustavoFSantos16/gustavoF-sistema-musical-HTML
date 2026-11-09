# 🎵 Sistema Musical — Protótipo Frontend

Este projeto foi desenvolvido como um **treino de finalização de semestre**, com o objetivo de construir a estrutura frontend completa de um sistema web para gestão de artistas e acervo musical.

O projeto estabelece toda a base visual, formulários, tabelas e fluxos de navegação que servirão de estrutura para a implementação de regras de negócio em PHP e persistência em banco de dados na próxima etapa.

---

## 📌 Funcionalidades e Telas

- **Tela de Login (`login.html`)**: Interface de autenticação com campo de credenciais e dica visual para utilizadores de teste.
- **Menu Principal (`index.html`)**: Painel central (Dashboard) que conecta os módulos de artistas e biblioteca musical.
- **Gestão de Artistas (`cadastro_artista.html`)**: Formulário de registo/edição de artistas com opção de upload de foto e listagem de artistas existentes.
- **Gestão de Músicas (`cadastro_musica.html`)**: Formulário completo para inclusão de faixas, associando-as ao artista, links do YouTube, letra e imagem de capa.
- **Biblioteca Musical (`listagem_musicas.html`)**: Catálogo geral de músicas com campos de pesquisa por palavra-chave, seletores de filtro por género e artista, além de ações de edição e eliminação.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Semântico e estruturado para acessibilidade e organização.
- **CSS3 (Puro)**:
  - Utilização de **Variáveis CSS (`:root`)** para padronização de cores, fontes e sombras.
  - **CSS Grid** e **Flexbox** para layouts responsivos.
  - Reset universal e suporte a navegação em dispositivos móveis (`media queries`).

---

## 📁 Estrutura de Ficheiros

```text
├── index.html              # Menu principal / Dashboard
├── login.html              # Ecrã de autenticação
├── cadastro_artista.html   # Formulário e listagem de artistas
├── cadastro_musica.html    # Formulário de registo de músicas
├── listagem_musicas.html   # Biblioteca musical com filtros
└── styles.css              # Folha de estilos centralizada do projeto
