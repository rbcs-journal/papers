---
title: 'PyBioCluster: Um pacote aberto para agrupamento e análise comparativa de dados genômicos'
tags:
  - Python
  - Bioinformática
  - Genômica
  - Agrupamento
  - Dados Ômicos
authors:
  - name: Autor Exemplo
    orcid: 0000-0000-0000-0000
    affiliation: 1
affiliations:
 - name: Instituto de Computação e Bioinformática, Brasil
   index: 1
date: 4 Novembro 2026
bibliography: paper.bib
---

# Resumo

O aumento exponencial no volume de sequenciamento de DNA e dados de transcriptômica de célula única (*single-cell*) impõe desafios para análises exploratórias rápidas e reprodutíveis. `PyBioCluster` é um pacote de código aberto em Python projetado para integrar algoritmos de redução de dimensionalidade e agrupamento não supervisionado com visualizações interativas para conjuntos de dados genômicos em larga escala.

# Declaração de Necessidade (Statement of Need)

Embora existam pipelines consolidados como o Seurat em R e o Scanpy em Python, muitas rotinas de análise comparativa de genomas bacterianos e metagenomas exigem fluxos de trabalho leves que possam ser incorporados diretamente em ambientes de nuvem e pipelines do Nextflow sem overhead excessivo de dependências.

O `PyBioCluster` fornece:
1. Uma interface unificada baseada em matrizes esparsas do SciPy e aceleração com Numba.
2. Algoritmos de agrupamento baseados em grafos otimizados para distâncias de k-mers.
3. Exportação direta de árvores filogenéticas em formato Newick e visualização em SVG.

# Arquitetura e Disponibilidade

O código é integralmente aberto sob licença MIT e pode ser instalado via gerenciador de pacotes:

```bash
pip install pybiocluster
```

O repositório oficial contém suíte completa de testes automatizados com cobertura superior a 90% via GitHub Actions, além de documentação hospedada com exemplos reprodutíveis.

# Agradecimentos

Agradecemos o apoio dos programas de pós-graduação e das agências de fomento à pesquisa aberta no Brasil.

# Referências
