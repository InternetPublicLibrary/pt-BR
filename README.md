<p align="center">
  <img src=".github/assets/logo.png" alt="Logo do conteúdo em português da IPL" width="112" height="112">
</p>

<h1 align="center">Internet Public Library — conteúdo em português</h1>

<p align="center">
  As páginas em português da <a href="https://ipl.better-web.org/pt-BR/">Internet Public Library</a>:
  início, seções da biblioteca e páginas institucionais (sobre, ajuda, contribuir, políticas…).
</p>

---

Este repositório entra no [IPLibrary-website](https://github.com/InternetPublicLibrary/IPLibrary-website) como o
submódulo git `pt-BR/`. O site gera as páginas de categoria, subcategoria, seção e wiki a partir do menu e dos dados
do repositório do site; aqui ficam as páginas escritas à mão e as introduções dos temas.

## O que há aqui

| Caminho | Conteúdo |
| --- | --- |
| `index.md` | Início em português (layout `language_index`) |
| `academicos/`, `negocios/`, `computacao/`, … | Páginas e introduções das oito categorias |
| `sobre.html`, `ajuda.html`, `contribute.html` (`/pt-BR/contribuir/`), … | Páginas institucionais (layout `info`) |
| `enviar-recurso.html`, `reportar-problemas.html`, `contato.html` | Formulários que abrem issues pré-preenchidas no GitHub |

## Como contribuir

- **Corrigir ou melhorar uma página:** use a aba **Editar** em qualquer página do site — ela abre o arquivo de
  origem aqui — ou abra um pull request diretamente. Um code owner revisa toda mudança (`.github/CODEOWNERS`).
- **Sugerir um recurso:** [Sugerir um recurso](https://ipl.better-web.org/pt-BR/enviar-recurso/) no site.
- **Reportar um problema:** [Reportar problemas](https://ipl.better-web.org/pt-BR/reportar-problemas/).
- As discussões sobre as páginas acontecem nas GitHub Discussions deste repositório.

Convenções de front matter: `layout`, `title`, `lang: pt-BR`, `description` e `permalink` (mantenha as URLs
estáveis; a edição em inglês segue a mesma estrutura em [en-US](https://github.com/InternetPublicLibrary/en-US)).

## Licença

Veja [LICENSE](LICENSE).
