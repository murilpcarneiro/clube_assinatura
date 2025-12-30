# Encantos Literarios

Landing page responsiva para o clube de assinatura literario "Encantos Literarios", criada apenas com HTML e CSS. A pagina destaca beneficios, um kit mensal surpresa e planos de assinatura, com microanimacoes e efeitos de hover para deixar a experiencia mais envolvente.

## Sobre o desafio

Neste desafio voce cria uma landing page de um clube de assinatura literario chamado Encantos Literarios. O objetivo e apresentar os beneficios do clube, mostrar um exemplo de livro surpresa que o assinante recebe e destacar os planos de assinatura. A proposta inclui trabalhar animacoes em CSS (transicoes suaves, efeitos de destaque e interacoes) para dar mais vida a pagina.

## Estrutura

- [index.html](index.html) — markup principal com secoes Hero, Surpresa do mes, Kit mensal, Planos e rodape.
- [styles/index.css](styles/index.css) — importa os demais estilos.
- [styles/global.css](styles/global.css) — tokens de cor, tipografia (Raleway e Syne), resets e breakpoints.
- [styles/utility.css](styles/utility.css) — utilitarios (flex, grid, alinhamentos, variantes desktop-only).
- [styles/hero.css](styles/hero.css) — hero com background ilustrado, CTA e animacao de entrada.
- [styles/surprise.css](styles/surprise.css) — bloco do livro surpresa com animacoes de escala/hover e brilho.
- [styles/month.css](styles/month.css) — vitrine do kit mensal com itens posicionados e animacoes sequenciais.
- [styles/price.css](styles/price.css) — cards de precos com efeitos de hover, destaque do plano popular e stars.
- [styles/footer.css](styles/footer.css) — rodape com rede sociais e links rapidos.
- assets/ — icones SVG e imagens usadas nos blocos.

## Secoes e interacoes

- Hero: headline, CTA "Assinar" e texto de apoio com animacao de fade-in.
- Surpresa do mes: destaque para o livro/brindes surpresa com glows, escalas e rotacoes em hover.
- Kit mensal: composicao do box com marcadores, setas e spans animados por keyframes.
- Planos: tres cards (Mensal, Semestral/Popular e Anual) com destaque de cores, hover que aumenta escala e estrela rotacionando.
- Rodape: logotipo, redes sociais com hover que troca a cor do svg, e duas colunas de links de apoio.

## Responsividade

- Mobile-first, com ajustes em 390px, 750px e 64em/80em.
- Elementos com classe `desktop-only` aparecem apenas em telas medias/grandes.
- Limites de largura controlados por `--max-width` e layout centralizado.

## Demo (GitHub Pages)

- Deploy publico via GitHub Pages: [Abrir no navegador](https://murilpcarneiro.github.io/clube_assinatura/)

## Como executar localmente

1. Clone ou baixe o projeto.
2. Abra [index.html](index.html) diretamente no navegador **ou** use uma extensao como Live Server no VS Code para recarregamento automatico.

## Conheca o projeto

Landing page do clube de assinatura literario Encantos Literarios. A pagina destaca beneficios do clube, mostra um exemplo de livro surpresa que o assinante recebe e evidencia os planos de assinatura. O foco e criar uma pagina atrativa com transicoes suaves, efeitos de destaque e interacoes que deixem a experiencia mais envolvente.

## Recursos

- LP de Clube de Assinatura (layout estatico) — [Figma](https://www.figma.com/community/file/1394686421442995256)
- Prototipo animado — [Figma](https://www.figma.com/community/file/1394686421442995256)

## Requisitos atendidos

- Secao inicial: logo no topo esquerdo, CTA no topo direito, titulo e texto centralizados, ilustracoes decorativas.
- Kit do mes: imagem do livro em destaque, textos laterais com setas/linhas ligando os itens e animacoes em sequencia.
- Assinaturas: 3 cards (Mensal, Semestral, Anual) com nome, preco, equivalente anual, beneficios e botao de acao.
- Rodape: logo, icones clicaveis de redes sociais e links (Kits passados, Clube de membros, Blog, Central de ajuda, Regulamentos, Suporte).

## Animacoes

- Transicoes suaves em CTAs e hover de cards.
- Animacoes de entrada/fade no hero.
- Escala e rotacao em elementos surpresa e itens do kit mensal.
- Destaque visual nos cards de preco (incluindo o plano popular).

## Entrega

- Codigo no GitHub (este repositorio) e deploy no GitHub Pages.
- Sugestao: compartilhar o resultado no LinkedIn com print/preview e relato do aprendizado.

## Personalizacao rapida

- Paleta e tipografia: altere variaveis em [styles/global.css](styles/global.css).
- Imagens e icones: substitua arquivos em `assets/` mantendo os nomes ou ajuste os `src` em [index.html](index.html).
- Animacoes: keyframes e duracoes podem ser ajustados em [styles/surprise.css](styles/surprise.css), [styles/month.css](styles/month.css) e [styles/price.css](styles/price.css).

## Licenca

Uso livre para fins de estudo e portfolio. Ajuste creditos dos assets conforme necessario.
