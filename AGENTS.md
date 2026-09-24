# Repository Guidelines

## Project Structure & Module Organization

Este repositório contém um site institucional estático da Game Store 41. `index.html` reúne o conteúdo e a estrutura da página; `styles.css` concentra os estilos, componentes visuais e regras responsivas; `images/` contém o favicon e as imagens usadas pelo site. Não há diretórios de código-fonte separados, suíte de testes ou configuração de build identificados.

## Build, Test, and Development Commands

Não há etapas de build nem scripts npm configurados. Para visualizar localmente, abra `index.html` no navegador. Se precisar servir os arquivos por HTTP, execute `python -m http.server 8000` na raiz e acesse `http://localhost:8000`. Antes de enviar alterações, confira a página em desktop e em uma largura móvel, especialmente navegação, links externos, mapa e imagens.

## Coding Style & Naming Conventions

Mantenha o HTML semântico e acessível: use regiões e títulos apropriados, texto alternativo em imagens informativas e rótulos descritivos em links e iframes. Preserve o idioma da página (`pt-BR`) e a identidade visual existente. O HTML usa indentação de dois espaços; siga esse padrão nas novas linhas. No CSS, mantenha seletores legíveis, nomes de classes em kebab-case (por exemplo, `.hero-card`) e regras de responsividade agrupadas em media queries. Reutilize classes e variáveis já existentes antes de criar estilos duplicados. Salve imagens em `images/` com nomes curtos e descritivos.

## Testing Guidelines

Não há framework de testes ou exigência de cobertura configurados. Valide manualmente as mudanças no navegador e verifique os caminhos de imagens, âncoras e destinos de links. Para alterações visuais, confira ao menos a visualização ampla e a estreita; para conteúdo, revise acentos, quebras de linha e consistência em português.

## Commit & Pull Request Guidelines

O histórico disponível contém apenas o commit inicial, então ainda não há convenção de mensagens estabelecida. Use mensagens curtas e imperativas que descrevam a alteração, como `Ajusta layout do banner`. Pull requests devem explicar o que mudou e como foi conferido; inclua capturas de tela quando houver impacto visual e relacione uma issue quando aplicável.

## Configuration & External Services

A página referencia fontes do Google, ícones Lucide via CDN e um mapa incorporado do Google Maps. Alterações nesses recursos devem preservar alternativas textuais e funcionamento aceitável caso o serviço externo não carregue. Não inclua credenciais ou dados privados nos arquivos versionados.
