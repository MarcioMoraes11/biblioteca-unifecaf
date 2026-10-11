# 📚 Biblioteca Digital UniFECAF

Projeto prático desenvolvido para a disciplina de **Design Web** do Centro Universitário UniFECAF.

A plataforma consiste em uma interface web responsiva, acessível e moderna para consulta de acervos bibliográficos e localização de polos universitários presenciais, concebida estritamente com **HTML5 Semântico** e **CSS3 puro** (sem bibliotecas, frameworks ou JavaScript).

---

## 🔗 Links do Projeto

- **Deploy (GitHub Pages):** [Acesse o site no ar](https://SEU_USUARIO.github.io/biblioteca-unifecaf/)
- **Repositório Oficial:** [Visualizar código no GitHub](https://github.com/MarcioMoraes11/biblioteca-unifecaf)
- **Vídeo Pitch:** [Apresentação no YouTube](LINK_DO_SEU_VIDEO_AQUI)

---

## 🎯 Proposta e Relação com o Protótipo

A interface foi desenvolvida a partir de um protótipo institucional de baixa fidelidade, transformando os blocos conceituais em seções padronizadas da web moderna:

1. **Apresentação / Hero:** Apresentação da proposta de valor e botão de ação direta (*Call to Action*) para o acervo.
2. **Sobre a Nossa Biblioteca:** Texto institucional detalhando recursos da plataforma e métricas de impacto acadêmico.
3. **Controles de Catálogo e Nossos Livros:** Barra de pesquisa semântica com filtro por categorias e catálogo composto por 8 cards com metadados e botões de acesso.
4. **As Unidades:** Exibição dos polos físicos da UniFECAF (Campus Taboão da Serra, Polo Morumbi, Polo Santo Amaro e Polo Digital EAD).
5. **Rodapé Institucional:** Links rápidos, dados institucionais e informações de contato delimitadas semanticamente com a tag `<address>`.

---

## 🎨 Identidade Visual e Tipografia

- **Paleta Institucional:**
  - Azul Escuro Institucional: `#002b66` (cor primária de autoridade e títulos)
  - Azul Vibrante: `#0050b3` (estados de destaque e ação)
  - Ciano Tecnológico: `#00b4d8` (acentos visuais, foco e badges)
  - Cinza Escuro: `#1b263b` (legibilidade do corpo de texto)
  - Fundo Suave: `#f4f6fa` e Branco Puro: `#ffffff`
- **Tipografia:** Tipografia do sistema (*system-ui*, `-apple-system`, `Segoe UI`, `Roboto`), priorizando tempo de carregamento imediato e alta nitidez em diferentes resoluções.

---

## ♿ Acessibilidade (WCAG / W3C)

O projeto prioriza boas práticas de acessibilidade nativa da web:

- **HTML5 Semântico:** Uso rigoroso de `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<address>` e `<footer>`.
- **Skip Link:** Mecanismo de salto (*Pular para o conteúdo principal*) no topo da página, acessível via navegação por teclado (`Tab`).
- **Navegabilidade por Teclado:** Estados de foco claramente delimitados através de `:focus-visible` com contorno de alto contraste.
- **Textos Alternativos:** Inclusão do atributo `alt` detalhado e contextualizado em todas as imagens.
- **Contraste de Cores:** Atendimento aos índices mínimos de contraste recomendados pelas diretrizes da W3C.

---

## 📱 Responsividade

O layout adapta-se de forma fluida a qualquer tamanho de tela:

- **CSS Grid:** Uso de `repeat(auto-fit, minmax(260px, 1fr))` no catálogo e nas unidades, reorganizando os cards automaticamente.
- **Flexbox:** Distribuição limpa de itens no cabeçalho, formulários e rodapé.
- **Media Queries:** Ponto de quebra em `768px` para conversão de menus e formulários em coluna única, garantindo usabilidade em dispositivos móveis sem rolagem horizontal indesejada.

---

## 📁 Estrutura de Arquivos

```text
biblioteca-unifecaf/
│
├── index.html
├── README.md
├── css/
│   └── style.css
└── assets/
    └── imagens/
        ├── logo-unifecaf.png
        ├── hero-biblioteca.jpg
        ├── livro-1.jpg até livro-8.jpg
        └── unidade-1.jpg até unidade-4.jpg
```
