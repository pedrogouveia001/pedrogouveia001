# Pedro Henrique Gouveia de Souza

**Backend Engineer — Python · FastAPI · PostgreSQL · REST APIs**

Recife, Pernambuco, Brasil
[LinkedIn](https://www.linkedin.com/in/pedro-gouveia-7b81471b8) · [E-mail](mailto:pedrogouveia001@gmail.com) · [sad-mcdm](https://github.com/sad-mcdm)

---

### O que eu faço

Construo backend em Python: desenho de API, modelagem de dados relacional, autorização e suíte de teste automatizado. O que me interessa é a parte que só aparece depois do deploy — isolamento de dado entre clientes garantido pelo banco, migração versionada, regressão pega antes do merge.

**Stack de trabalho**

| | |
| :--- | :--- |
| **Backend** | Python 3.12 · FastAPI · Flask · SQLAlchemy 2 (async) · Pydantic · Alembic |
| **Banco** | PostgreSQL (Row Level Security, JSONB, índice trigram) · MySQL · SQLite · modelagem conceitual/lógica/física |
| **Teste & qualidade** | Pytest · pytest-asyncio · teste de integração contra banco real · Ruff · SBOM (CycloneDX) |
| **Entrega** | Git/GitHub (Pull Request, CODEOWNERS, Git LFS) · OpenAPI · JWT + argon2 · Jinja2 |
| **Computação numérica** | NumPy · SciPy · Pandas · simulação de Monte Carlo |
| **Legado** | Delphi / Object Pascal · VBA |

---

### Sistemas de apoio à decisão — CDSID/UFPE (2022–2026)

Quatro anos construindo software de decisão multicritério no Centro de Desenvolvimento de Sistemas de Informação e Decisão da UFPE. O código está arquivado em repositórios privados; o resumo do que foi construído:

- **FITradeoff Web (Flask + MySQL)** — reescrita web do FITradeoff: autenticação, cadastro e retomada de problema salvo, importação de matriz de consequências em `.csv`/`.xlsx`, motor de cálculo aditivo com pesos ROC, preferência holística e por decomposição, análise de sensibilidade por Monte Carlo com teste de Kendall, exportação em PDF e CSV, i18n PT/EN. Inclui a migração do banco legado (`fitradeoff_data`) para o esquema novo.
- **FITradeoff-CB-HE** — seleção de portfólio de projetos por razão custo-benefício. **Registro de software no INPI nº 512025006292-3** (coautor: módulos de cálculo e fluxo de uso do método).
- **SPEAR / Surrogate / PROMETHEE / NSGA-II** — motores de cálculo e simulação em Delphi/Object Pascal e Python, usados em sessões reais de elicitação de preferências com decisores.
- **Portal bibliométrico do FITradeoff** — sincronização entre o raspador da página oficial e a API do OpenAlex, com desduplicação por DOI/título e grafo de coautoria em D3.js.

**Produção derivada desse software:** capítulo na Springer Nature (LNBIP, 2025) · INFORMS Annual Meeting 2024 (Seattle) · 27th International Conference on MCDM 2024 (Tunísia) · SBPO.

---

### [sad-mcdm](https://github.com/sad-mcdm) — open source

Suíte de resolvedores de decisão multicritério, mantida por mim.

- **[sad-mcdm-lib](https://github.com/sad-mcdm/sad-mcdm-lib)** (Python) — pacote unificado: `solve_ahp`, `solve_bwm`, `solve_bwt`, `solve_electre`, `solve_macbeth`, `solve_promethee`, `solve_smarts_smarter`, `solve_topsis`, `solve_vikor`, `run_monte_carlo` e geração de relatório em PDF.
- **Bindings:** [R](https://github.com/sad-mcdm/sad-mcdm-r) · [JavaScript](https://github.com/sad-mcdm/sad-mcdm-js) (com Simplex de duas fases no navegador) · [C++](https://github.com/sad-mcdm/sad-mcdm-cpp) · [Julia](https://github.com/sad-mcdm/sad-mcdm-julia) · [Java](https://github.com/sad-mcdm/sad-mcdm-java)
- **[sad-central-mcdm](https://github.com/sad-mcdm/sad-central-mcdm)** — hub que processa matriz de consequências e exporta relatório executivo em PDF.
- **Aplicações:** [PrometheeInvestor](https://github.com/sad-mcdm/sad-promethee-b3) e [SAD Smarter B3](https://github.com/sad-mcdm/sad-smarter-b3) — análise fundamentalista de ações da B3.

---

### Formação

- **Engenharia de Produção** — UFPE (2021–2025)
- **CS50x** e **CS50P** — Harvard University
- **Técnico em Mecânica** — IFPE (2017–2021)
- Mestrado em Engenharia de Produção / Pesquisa Operacional — PPGEP-UFPE, créditos cursados (trancado em ago/2026)

---

<p align="center">
  <img height="165em" src="https://github-readme-stats.vercel.app/api?username=pedrogouveia001&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true" alt="Estatísticas do GitHub" />
  <img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=pedrogouveia001&layout=compact&theme=tokyonight&langs_count=8" alt="Linguagens mais usadas" />
</p>
