# 📚 RBCS Papers — Acervo Permanente de Artigos Publicados

Este repositório armazena os artigos formalmente aceitos e publicados na **Revista Brasileira de Computação e Software Científico (RBCS)**.

---

## 🏛️ Estrutura de Arquivamento

Cada artigo publicado possui seu próprio diretório organizado por ano e número de artigo:

```
papers/
├── 2026/
│   └── 0001/
│       ├── paper.md           # Texto-fonte do artigo em Markdown
│       ├── paper.bib          # Referências em BibTeX
│       ├── paper.pdf          # PDF oficial de publicação
│       ├── paper.jats         # Metadados JATS XML para indexadores
│       └── paper.crossref.xml # Metadados para depósito de DOI na Crossref
└── papers.json                # Catálogo unificado em JSON consumido pelo portal web
```

---

## 🔗 Identificadores & Preservação

* Todos os artigos são publicados sob licença **Creative Commons Attribution 4.0 International (CC-BY 4.0)**.
* O código-fonte dos softwares correspondentes permanece nos repositórios dos autores sob suas respectivas licenças de código aberto (MIT, Apache, GPL, etc.).
* Releases finais dos softwares e PDFs são arquivados com DOIs permanentes (Zenodo / Crossref / Software Heritage).
