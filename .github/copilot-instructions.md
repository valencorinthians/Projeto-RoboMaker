# Copilot Instructions for Projeto-RoboMaker

- Este projeto é um site estático simples. A base principal é `index.html` no diretório raiz.
- Não há backend, pipeline de build ou testes automatizados definidos atualmente.

## Estrutura principal
- `index.html`: única página do site. Contém o conteúdo HTML do catálogo de produtos, categorias, cursos e rodapé.
- Imagens referenciadas em `index.html` vêm de URLs externas e de arquivos locais esperados no mesmo diretório (`senores.jpg`, `motores e servos.jpg`, `estrutura .jpg`, `facebook logo.png`, `instagram logo.png`, `youtube logo.png`).

## O que fazer primeiro
- Preserve a estrutura atual da página: cabeçalho, seções `Categorias`, `Produtos`, `Cursos` e rodapé.
- Mantenha o idioma do conteúdo em português do Brasil, já que o site é construído em `pt-BR`.
- Use HTML sem frameworks, pois não há dependências nem arquivos de configuração adicionais.

## Pontos importantes ao editar
- Corrija apenas erros claros de HTML, ortografia ou acessibilidade. Exemplo: os nomes de imagens locais podem precisar ser ajustados para corresponder ao nome do arquivo real.
- A tabela de cursos está escrita em HTML puro; preserve o layout de `<table>`, `<thead>`, `<tbody>`, `<tr>` e `<td>`.
- Remova ou atualize links e imagens apenas com base no contexto do projeto, não adicione dependências externas desnecessárias.

## Quando propor alterações maiores
- Se for necessário adicionar CSS ou JavaScript, crie novos arquivos no diretório raiz e vincule-os a `index.html` em vez de inserir estilos ou scripts complexos inline.
- Evite mudanças estruturais drásticas que transformem o projeto em algo maior do que um simples site estático.

## Regras de estilo para este projeto
- Mantenha o HTML limpo e simples.
- Use `alt` descritivos em imagens.
- Não remova seções relevantes como `Categorias`, `Produtos` ou `Cursos` sem buscar confirmação.

## Observação
- Não existem comandos de build nem testes no repositório. O fluxo de trabalho padrão é editar `index.html` e verificar no navegador.
