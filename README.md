### G'day, I'm Charles

I'm an economist based in London with interests in climate, macroeconomics, and public policy.

See below for my projects for accessing economic data and applied research.

---

#### [econstack](https://github.com/charlescoverdale/econstack): AI-powered economic analysis

Professional economic analysis, powered by AI. econstack is a set of [Claude Code](https://claude.ai/code) skills that handle the first 80% of economic analysis: cost-benefit appraisals, business cases, regulatory impact assessments, policy briefings, IO impact models, and market research. 12 skills across the full policy analysis lifecycle, from benefits brainstorming to methodology audit. Supports UK HM Treasury Green Book, EU Better Regulation, World Bank, Asian Development Bank, and Victorian Treasury HVHR frameworks with framework-native output. Backed by 57 audited parameter files and 16 R packages on CRAN.

- **`/longlist`** : Brainstorm all the benefits and costs for a project before you start modelling anything
- **`/cost-benefit`** : Build a full cost-benefit analysis with economic NPV and financial NPV side by side
- **`/mca`** : Develop criteria and rank options against them, with tailored scoring and sensitivity analysis
- **`/business-case`** : Draft a complete Five Case Model business case, scaled by stage and project size
- **`/reg-impact`** : Produce a Regulatory Impact Assessment for a proposed regulation, policy, or legislative change
- **`/macro-briefing`** : Pull live macro data for the UK, US, Euro area, or Australia into one briefing
- **`/fiscal-briefing`** : Pull live public finances data and produce a deficit, debt, and fiscal rules briefing
- **`/market-research`** : Produce a source-cited industry report with sizing, competition, Porter's Five Forces, and outlook
- **`/io-report`** : Estimate regional jobs, GVA, and output impact of an investment using input-output multipliers
- **`/la-profile`** : Economic snapshot of any UK local authority, benchmarked against its country average
- **`/briefing-note`** : Draft a one or two-page policy briefing note for a minister, board, or committee
- **`/econ-audit`** : Review any economic analysis for methodology errors and return a RAG scorecard with fixes

Backed by 16 R packages on CRAN for data access and computation.

---

#### Data access packages

Pull macroeconomic, trade, and climate data directly into R, ready for analysis. 10 packages covering 8 data sources.

| Package | Source | CRAN | Downloads |
|---|---|---|---|
| [**ons**](https://github.com/charlescoverdale/ons) | UK Office for National Statistics | [![CRAN](https://www.r-pkg.org/badges/version/ons)](https://CRAN.R-project.org/package=ons) | [![Downloads](https://cranlogs.r-pkg.org/badges/ons)](https://CRAN.R-project.org/package=ons) |
| [**boe**](https://github.com/charlescoverdale/boe) | Bank of England | [![CRAN](https://www.r-pkg.org/badges/version/boe)](https://CRAN.R-project.org/package=boe) | [![Downloads](https://cranlogs.r-pkg.org/badges/boe)](https://CRAN.R-project.org/package=boe) |
| [**hmrc**](https://github.com/charlescoverdale/hmrc) | HM Revenue & Customs | [![CRAN](https://www.r-pkg.org/badges/version/hmrc)](https://CRAN.R-project.org/package=hmrc) | [![Downloads](https://cranlogs.r-pkg.org/badges/hmrc)](https://CRAN.R-project.org/package=hmrc) |
| [**obr**](https://github.com/charlescoverdale/obr) | Office for Budget Responsibility | [![CRAN](https://www.r-pkg.org/badges/version/obr)](https://CRAN.R-project.org/package=obr) | [![Downloads](https://cranlogs.r-pkg.org/badges/obr)](https://CRAN.R-project.org/package=obr) |
| [**fred**](https://github.com/charlescoverdale/fred) | US Federal Reserve (FRED) | [![CRAN](https://www.r-pkg.org/badges/version/fred)](https://CRAN.R-project.org/package=fred) | [![Downloads](https://cranlogs.r-pkg.org/badges/fred)](https://CRAN.R-project.org/package=fred) |
| [**readecb**](https://github.com/charlescoverdale/readecb) | European Central Bank | [![CRAN](https://www.r-pkg.org/badges/version/readecb)](https://CRAN.R-project.org/package=readecb) | [![Downloads](https://cranlogs.r-pkg.org/badges/readecb)](https://CRAN.R-project.org/package=readecb) |
| [**readoecd**](https://github.com/charlescoverdale/readoecd) | OECD | [![CRAN](https://www.r-pkg.org/badges/version/readoecd)](https://CRAN.R-project.org/package=readoecd) | [![Downloads](https://cranlogs.r-pkg.org/badges/readoecd)](https://CRAN.R-project.org/package=readoecd) |
| [**readnoaa**](https://github.com/charlescoverdale/readnoaa) | NOAA Climate Data | [![CRAN](https://www.r-pkg.org/badges/version/readnoaa)](https://CRAN.R-project.org/package=readnoaa) | [![Downloads](https://cranlogs.r-pkg.org/badges/readnoaa)](https://CRAN.R-project.org/package=readnoaa) |
| [**readaec**](https://github.com/charlescoverdale/readaec) | Australian Electoral Commission | [![CRAN](https://www.r-pkg.org/badges/version/readaec)](https://CRAN.R-project.org/package=readaec) | [![Downloads](https://cranlogs.r-pkg.org/badges/readaec)](https://CRAN.R-project.org/package=readaec) |
| [**comtrade**](https://github.com/charlescoverdale/comtrade) | UN Comtrade | [![CRAN](https://www.r-pkg.org/badges/version/comtrade)](https://CRAN.R-project.org/package=comtrade) | [![Downloads](https://cranlogs.r-pkg.org/badges/comtrade)](https://CRAN.R-project.org/package=comtrade) |

#### Analytical toolkits

Applied economics computation. Pure R, no API keys, no external dependencies.

| Package | Purpose | CRAN | Downloads |
|---|---|---|---|
| [**predictset**](https://github.com/charlescoverdale/predictset) | Conformal prediction (regression, classification, Mondrian) | [![CRAN](https://www.r-pkg.org/badges/version/predictset)](https://CRAN.R-project.org/package=predictset) | [![Downloads](https://cranlogs.r-pkg.org/badges/predictset)](https://CRAN.R-project.org/package=predictset) |
| [**nowcast**](https://github.com/charlescoverdale/nowcast) | Economic nowcasting (bridge equations, mixed-frequency) | [![CRAN](https://www.r-pkg.org/badges/version/nowcast)](https://CRAN.R-project.org/package=nowcast) | [![Downloads](https://cranlogs.r-pkg.org/badges/nowcast)](https://CRAN.R-project.org/package=nowcast) |
| [**inflationkit**](https://github.com/charlescoverdale/inflationkit) | Inflation analysis (decomposition, persistence, Phillips curve) | [![CRAN](https://www.r-pkg.org/badges/version/inflationkit)](https://CRAN.R-project.org/package=inflationkit) | [![Downloads](https://cranlogs.r-pkg.org/badges/inflationkit)](https://CRAN.R-project.org/package=inflationkit) |
| [**yieldcurves**](https://github.com/charlescoverdale/yieldcurves) | Yield curve fitting (Nelson-Siegel, Svensson, PCA) | [![CRAN](https://www.r-pkg.org/badges/version/yieldcurves)](https://CRAN.R-project.org/package=yieldcurves) | [![Downloads](https://cranlogs.r-pkg.org/badges/yieldcurves)](https://CRAN.R-project.org/package=yieldcurves) |
| [**debtkit**](https://github.com/charlescoverdale/debtkit) | Debt sustainability analysis (Bohn test, fan charts, stress tests) | [![CRAN](https://www.r-pkg.org/badges/version/debtkit)](https://CRAN.R-project.org/package=debtkit) | [![Downloads](https://cranlogs.r-pkg.org/badges/debtkit)](https://CRAN.R-project.org/package=debtkit) |
| [**climatekit**](https://github.com/charlescoverdale/climatekit) | Climate indices (35 temperature, precipitation, drought metrics) | [![CRAN](https://www.r-pkg.org/badges/version/climatekit)](https://CRAN.R-project.org/package=climatekit) | [![Downloads](https://cranlogs.r-pkg.org/badges/climatekit)](https://CRAN.R-project.org/package=climatekit) |
| [**inflateR**](https://github.com/charlescoverdale/inflateR) | Inflation adjustment for price series | [![CRAN](https://www.r-pkg.org/badges/version/inflateR)](https://CRAN.R-project.org/package=inflateR) | [![Downloads](https://cranlogs.r-pkg.org/badges/inflateR)](https://CRAN.R-project.org/package=inflateR) |

#### Products

[**econprofile.com**](https://econprofile.com) : Economic profiles for 391 UK local authorities. Interactive maps, IO impact calculator, compare tool.

[**Macroeconomics with R**](https://macrowithr.com) : 14-chapter applied macro textbook. UK, European, and international data. Uses the packages above.
