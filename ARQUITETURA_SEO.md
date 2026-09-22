# Arquitetura de Expansão SEO: SOS Reformas (Transição SOS Calhas ABC)

Este documento define as diretrizes para a futura expansão de páginas de serviços e localidades no GitHub Pages sem risco de canibalização, páginas órfãs ou penalidade por conteúdo raso (*doorway pages*).

---

## 1. Estrutura de Diretórios Recomendada

Para o GitHub Pages (lemg-mei.github.io/SOSCalhasABC/), a hierarquia limpa de URLs utiliza pastas contendo index.html:

`	ext
/ (Home Hub - Autoridade Geral)
├── servicos/
│   ├── calhas/index.html
│   ├── rufos/index.html
│   ├── limpeza-de-calhas/index.html
│   ├── reforma-de-telhados/index.html
│   ├── impermeabilizacao/index.html
│   └── pintura-de-telhados/index.html
├── regioes/
│   ├── santo-andre/index.html
│   ├── sao-bernardo-do-campo/index.html
│   ├── sao-caetano-do-sul/index.html
│   ├── diadema/index.html
│   ├── maua/index.html
│   └── sao-paulo/index.html
├── img/
├── robots.txt
├── sitemap.xml
└── googleb5dce199ae672d9f.html
`

---

## 2. Regras Essenciais para Páginas Locais

O Google pune sites que criam dezenas de páginas idênticas apenas trocando o nome da cidade. Cada página de localidade deve conter obrigatoriamente:
1. **Bairros reais atendidos**: Lista de bairros específicos do município (ex.: Campestre, Bairro Jardim, Parque das Nações em Santo André; Rudge Ramos, Assunção, Baeta Neves em SBC).
2. **Fotos reais de obras no município**: Pelo menos 2 a 3 fotos tiradas em atendimentos reais na cidade com lt geolocalizado.
3. **Casos de uso e problemas típicos da topografia local**: Por exemplo, problemas com calhas em épocas de chuvas fortes, vazamentos em telhados antigos da região central, etc.
4. **CTA direto de WhatsApp** com mensagem contextualizada: Olá, preciso de orçamento de calhas/telhados em Santo André.
5. **Canonical tag apontando para si mesma**: <link rel="canonical" href="https://lemg-mei.github.io/SOSCalhasABC/regioes/santo-andre/" />.
6. **BreadcrumbList Schema** indicando o caminho: Home > Regiões > Santo André.

---

## 3. Checklist para Publicação de Nova Página

- [ ] URL amigável e canônica definida.
- [ ] Título exclusivo de até 60 caracteres.
- [ ] Meta description exclusiva entre 140 e 155 caracteres.
- [ ] Único H1 semântico na página.
- [ ] Imagens locais com atributos width, height, loading="lazy" e lt descritivo.
- [ ] JSON-LD específico (Service ou LocalBusiness com reaServed).
- [ ] Adição da URL no arquivo sitemap.xml.
- [ ] Link interno a partir da home ou do rodapé para garantir indexabilidade (sem páginas órfãs).