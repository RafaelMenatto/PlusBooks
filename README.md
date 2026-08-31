# PlusBooks 

Projeto de um site estático para uma livraria online fictícia, desenvolvido como parte do curso de HTML e CSS da [Alura](https://www.alura.com.br/).

---

## Funcionalidades

- **Header responsivo** com menu hamburguer (CSS puro, sem JavaScript)
- **Barra de busca** com ícone de lupa
- **Carrosséis de livros** (Lançamentos e Mais Vendidos) com Swiper.js
- **Cartão de recomendação** com capa, descrição e botões de ação
- **Autora do Mês** com avaliação em estrelas e ilustração
- **Tópicos visitados** com tags clicáveis
- **Formulário de newsletter** com campo de email
- **Rodapé completo** com links para empresas do grupo Alura
- **Layout totalmente responsivo** com 3 breakpoints (mobile, desktop e large desktop)

---

## Tecnologias Utilizadas

| Tecnologia | Uso |
|---|---|
| **HTML5** | Estrutura semântica da página |
| **CSS3** | Estilização modular com variáveis customizadas |
| **Swiper.js v8** | Carrosséis de livros (via CDN) |
| **Google Fonts** | Fontes Poppins e Josefin Sans |
| **Flexbox** | Layout responsivo |
| **Media Queries** | Responsividade em 3 breakpoints |

---

## Estrutura do Projeto

```
alurabooks-aula05/
├── index.html              # Página principal
├── styles.css              # Arquivo CSS raiz (importa os parciais)
├── reset.css               # Reset CSS (Eric Meyer)
├── styles/                 # Estilos modulares por seção
│   ├── header.css
│   ├── banner.css
│   ├── carrossel.css
│   ├── topicos.css
│   ├── contato.css
│   └── rodape.css
└── img/                    # Imagens SVG (logos, capas, ícones)
    ├── Logo.svg
    ├── Menu.svg
    └── ...
```

---

## Como Executar

### Opção 1: Abrir direto no navegador
Dê um duplo-clique no arquivo `index.html`.

### Opção 2: Usando um servidor local (recomendado)

**VS Code (Live Server):**
1. Instale a extensão "Live Server"
2. Clique com o botão direito em `index.html` → "Open with Live Server"

**Python:**
```bash
python -m http.server 8000
```
Acesse http://localhost:8000

**Node.js:**
```bash
npx serve .
```

---

## Breakpoints Responsivos

| Breakpoint | Comportamento |
|---|---|
| **< 1024px** | Mobile: menu hamburguer, layout empilhado |
| **≥ 1024px** | Desktop: navegação horizontal, rodapé visível |
| **≥ 1728px** | Large desktop: labels de texto, colunas no rodapé |

---

## Pré-requisitos

- Navegador web moderno
- Conexão com a internet (para carregar CDN do Swiper.js e Google Fonts)

---

## Créditos

Projeto desenvolvido durante o curso **HTML e CSS** da [Alura](https://www.alura.com.br/).
