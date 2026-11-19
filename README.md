<div align="center">

# 📊 Portfolio Power BI

**Do dado bruto à decisão clara.**
Hub de projetos de Business Intelligence e Data Analytics, com dashboards interativos em Power BI, ETL em Python e SQL.

### 🔗 [Acessar o portfólio ao vivo](https://darlan-monteiro.github.io/Portfolio-POWER-BI/)

</div>

---

## Sobre o projeto

Este repositório hospeda o site do meu portfólio de dados. Cada projeto reúne o pipeline completo: extração e tratamento (Python, Power Query, SQL Server), modelagem em Star Schema, medidas em DAX e interface desenhada no Figma.

## Destaques do site

- Visual **liquid glass** com a paleta amarela do Power BI
- Alternador de tema: **claro, escuro ou automático** (segue o sistema e lembra a escolha)
- **14 dashboards** incorporados, com filtro por tema (Esportes, Vendas e CRM, Finanças e ETL)
- Carregamento sob demanda: cada dashboard só carrega quando se aproxima da tela
- Botões de **tela cheia** e **abrir em nova aba** em cada dashboard
- Responsivo, com navegação por teclado e respeito a `prefers-reduced-motion`

## Tecnologias

| Área | Ferramentas |
| --- | --- |
| BI e modelagem | Power BI, DAX, Power Query (M), Star Schema |
| Engenharia de dados | Python (Pandas, pdfplumber, web scraping), SQL Server (T-SQL) |
| Design | Figma (UI/UX dos dashboards) |
| Site | HTML, CSS e JavaScript puros, hospedado no GitHub Pages |

## Estrutura

```
Portfolio-POWER-BI/
├── index.html   # o site inteiro (HTML + CSS + JS em um único arquivo)
└── README.md
```

## Como publicar no GitHub Pages

1. Envie `index.html` e `README.md` para a branch `main`.
2. Em **Settings → Pages**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`.
3. Em alguns minutos o site estará em `https://darlan-monteiro.github.io/Portfolio-POWER-BI/`.

## Como adicionar um novo dashboard

Copie um bloco `<article class="card glass" ...>` dentro de `<div class="list">`, atualize o código (R15, R16...), título, tags, descrição e o `data-src` do iframe. Use `data-cat` com `esportes`, `vendas` ou `financas` para o filtro.

## Contato

- GitHub: [Darlan-Monteiro](https://github.com/Darlan-Monteiro)
- LinkedIn: [Darlan Santos](https://www.linkedin.com/in/darlan-santos-01a87b185/)
