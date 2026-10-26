# Protótipo Aula para Todos — catálogo e páginas de curso

Versão independente, HTML estático, sem vínculo com o AEM.

## Publicação no GitHub Pages

Envie o conteúdo deste ZIP diretamente à **raiz** do repositório existente (mesclando a pasta `assets`).

- `index.html`: home V2 preservada com links para o catálogo e detalhes dos cursos.
- `cursos.html`: catálogo navegável com filtros e pesquisa.
- `curso.html?curso=logistica`: detalhes de Assistente de Logística.
- `curso.html?curso=administrativo`: detalhes de Auxiliar Administrativo.
- `curso.html?curso=recepcionista`: detalhes de Atendente / Recepcionista.
- `assets/`: imagens, logotipos e `cursos.css`.

Nenhum dado é integrado a LMS, AEM ou sistema de matrícula. Os módulos são **ilustrativos** e precisam ser substituídos por planos de curso reais antes de qualquer publicação produtiva. Botões de ação apenas navegam pelo protótipo.

Inspiração de UX: navegação e apresentação de cursos semelhante às páginas de detalhe de plataformas de ensino, com estrutura original.

## V4 — Simulação de compras
- `curso.html`: novo painel comercial com preço fictício de R$ 1,00 por curso, Pix, cartão de crédito e boleto **somente como exemplos**.
- `carrinho.html`: carrinho demonstrativo com adição, remoção e soma dos valores.
- `assets/carrinho.js`: salva a seleção no armazenamento local do navegador, sem servidores ou dados pessoais.
- `assets/cursos.css`: novos estilos responsivos do painel e carrinho.
- Botão **Finalizar compra** não processa pagamentos; apresenta aviso de demonstração. Não existe checkout, matrícula ou emissão de certificado.

Para atualizar o GitHub Pages, envie **todos** os arquivos do ZIP, substituindo os arquivos existentes e preservando os caminhos de `assets/`.
