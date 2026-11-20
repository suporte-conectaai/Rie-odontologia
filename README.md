# Rie Odontologia Integrada — Landing Page

Página web institucional da **Rie Odontologia Integrada** (Janaúba — MG), construída em HTML estático, Tailwind CSS, GSAP ScrollTrigger e Lenis Smooth Scroll.

## Estrutura do Projeto

```text
.
├── index.html          # Página principal (layout, animações, SEO técnico e modal WhatsApp)
├── robots.txt          # Diretivas de indexação para mecanismos de busca
├── .gitignore          # Arquivos ignorados pelo Git
├── README.md           # Documentação do projeto
└── assets/             # Imagens otimizadas da clínica e logotipos
    ├── logo-rie.png
    ├── logo-rie-hero.png
    ├── ambiente-01.jpg
    ├── ambiente-02.jpg
    ├── ambiente-03.jpg
    ├── ambiente-04.jpg
    ├── ambiente-05.jpg
    ├── ambiente-08.jpg
    ├── ambiente-09.jpg
    └── ambiente-10.jpg
```

## Como Visualizar Localmente

- **Diretamente no navegador:** abra o arquivo `index.html`.
- **Via servidor local (ex.: Live Server no VS Code ou Python):**
  ```bash
  python -m http.server 5500
  ```
  Acesse `http://127.0.0.1:5500/`.

## Checklist ao Publicar no Domínio Oficial

1. Adicionar `<link rel="canonical" href="https://seudominio.com.br/" />` no `<head>` do `index.html`.
2. Atualizar `og:image` e `twitter:image` com a URL completa (`https://seudominio.com.br/assets/logo-rie.png`) para exibir a prévia completa ao compartilhar no WhatsApp e redes sociais.

## Informações da Clínica

- **Endereço:** Rua Inhumas, 101, Centro — Janaúba, MG
- **WhatsApp:** (38) 98435-8299
