# Git Ã© um jardim

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


[![Git Ã© um jardim](guia/assets/banner.jpg)](https://inematds.github.io/git-jardineiro/guia/)

**ðŸ‡§ðŸ‡· [PortuguÃªs](README.md) Â· ðŸ‡ºðŸ‡¸ [English](README.en.md) Â· ðŸ‡ªðŸ‡¸ [EspaÃ±ol](README.es.md)**

## O que Ã©

Este Ã© um guia grÃ¡tis que explica o Git usando a histÃ³ria de um jardineiro. O Git Ã© a ferramenta que guarda cada versÃ£o de um projeto, como fotos de um jardim tiradas ao longo do tempo. Serve para quem programa, para quem trabalha com agentes de IA e para quem sÃ³ quer parar de perder arquivos. Aqui vocÃª aprende seis comandos (clone, commit, branch, worktree, merge e push), cada um com um desenho, uma explicaÃ§Ã£o simples e os comandos prontos para copiar. Para praticar, basta ter o Git instalado.

## ðŸ“– Guia de uso

Guia completo (landing + 6 pÃ¡ginas explicativas): **https://inematds.github.io/git-jardineiro/guia/**

## ðŸŽ¬ VÃ­deos

- Explicativo 16:9 (3 min): https://github.com/inematds/git-jardineiro/releases/download/video-v1.0.0/git-jardineiro-16x9.mp4
- Reel 9:16 (31 s): https://github.com/inematds/git-jardineiro/releases/download/video-v1.0.0/git-jardineiro-reel.mp4
- Players no guia: https://inematds.github.io/git-jardineiro/guia/#video

O roteiro e o roteiro visual estÃ£o em `video/`.

## Os 6 passos

1. **Clone** â€” Trazer o jardim pra casa: O clone copia o projeto e toda a histÃ³ria dele para o seu computador. (https://inematds.github.io/git-jardineiro/guia/clone/)
2. **Commit** â€” Tirar a foto do jardim: Edite, escolha o que entra e tire a foto. O commit salva no seu computador. (https://inematds.github.io/git-jardineiro/guia/commit/)
3. **Branch** â€” Testar uma ideia nova: Branch Ã© uma etiqueta que anda junto com os seus commits novos. (https://inematds.github.io/git-jardineiro/guia/branch/)
4. **Worktree** â€” Dois canteiros ao mesmo tempo: Worktree Ã© outra pasta do mesmo projeto, aberta em outra branch. (https://inematds.github.io/git-jardineiro/guia/worktree/)
5. **Merge** â€” Juntar as mudanÃ§as: Merge junta duas histÃ³rias num commit novo. (https://inematds.github.io/git-jardineiro/guia/merge/)
6. **Push** â€” Compartilhar com a equipe: Push leva os seus commits para o remoto. Agora a equipe pode pegar. (https://inematds.github.io/git-jardineiro/guia/push/)

| | |
|---|---|
| `git clone <url> jardim` | trazer o projeto e a histÃ³ria para o seu computador |
| `git status` | ver o que mudou e o que estÃ¡ na bandeja |
| `git add .` | pÃ´r as mudanÃ§as na bandeja (Ã¡rea de preparo) |
| `git commit -m "frase"` | tirar a foto: salvar a versÃ£o no seu computador |
| `git switch -c flores` | criar a etiqueta flores e trabalhar nela |
| `git worktree add ../jardim-main main` | abrir outra pasta, em outra branch |
| `git merge flores` | juntar a branch flores na branch atual |
| `git push origin main` | levar as suas fotos para a estufa |
| `git fetch` | baixar a histÃ³ria nova da estufa, sem juntar |
| `git pull` | baixar e jÃ¡ juntar na sua branch |

## Para editar o guia

O texto mora em `src/<idioma>.json`; o HTML sai de `python3 src/build.py`.

Projetos e cursos gratuitos: https://inema.club

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>