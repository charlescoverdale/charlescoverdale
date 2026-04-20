### G'day, I'm Charles

I'm an economist based in London with interests in climate, macroeconomics, and public policy.

See below for my projects for accessing economic data and applied research.

---

#### [econstack](https://github.com/charlescoverdale/econstack): AI-powered economic analysis

Professional economic analysis, powered by AI. econstack is a set of [Claude Code](https://claude.ai/code) skills that handle the first 80% of economic analysis: cost-benefit appraisals, business cases, regulatory impact assessments, policy briefings, IO impact models, and market research. 11 skills across the full policy analysis lifecycle, from benefits brainstorming to methodology audit. Supports HM Treasury Green Book, EU Better Regulation, World Bank, Asian Development Bank, and Australian Treasury (Victoria) frameworks with framework-native output. Backed by 57 audited parameter files and 17 R packages on CRAN.

- **`/cost-benefit`** : Build a full cost-benefit analysis with economic NPV and financial NPV side by side
- **`/longlist`** : Brainstorm all the benefits and costs for a project before you start modelling anything
- **`/business-case`** : Draft a complete Five Case Model business case, scaled by stage and project size
- **`/macro-briefing`** : Pull live macro data for the UK, US, Euro area, or Australia into one briefing
- **`/fiscal-briefing`** : Pull live public finances data and produce a deficit, debt, and fiscal rules briefing
- **`/market-research`** : Produce a source-cited industry report with sizing, competition, Porter's Five Forces, and outlook
- **`/io-report`** : Estimate regional jobs, GVA, and output impact of an investment using input-output multipliers
- **`/la-profile`** : Economic snapshot of any UK local authority, benchmarked against its country average
- **`/reg-impact`** : Produce a Regulatory Impact Assessment for a proposed regulation, policy, or legislative change
- **`/briefing-note`** : Draft a one or two-page policy briefing note for a minister, board, or committee
- **`/econ-audit`** : Review any economic analysis for methodology errors and return a RAG scorecard with fixes

---

#### [buildRpackage](https://github.com/charlescoverdale/buildRpackage): ship R packages to CRAN

A [Claude Code](https://claude.ai/code) skill for the full CRAN submission workflow: ideate, name, plan, build, check, audit, submit, resubmit. Captures CRAN policies and the fix pattern for common rejections (Ripley cache rule, globalenv manipulation, URL 404s, version discipline). Two audit modes: academic (literature, formulas, test adequacy) and code (edge cases, numerical stability, cross-platform). Built from shipping 16 R packages to CRAN.

---

#### Data access packages

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
| [**ukhousing**](https://github.com/charlescoverdale/ukhousing) | UK Land Registry, EPC, Planning | | |
| [**carbondata**](https://github.com/charlescoverdale/carbondata) | Carbon markets: EU ETS, UK ETS, RGGI, California, ICAP, VROD | | |

#### Analytical toolkits

| Package | Purpose | CRAN | Downloads |
|---|---|---|---|
| [**inequality**](https://github.com/charlescoverdale/inequality) | Inequality and poverty measurement (Gini, Theil, Lorenz, FGT) | [![CRAN](https://www.r-pkg.org/badges/version/inequality)](https://CRAN.R-project.org/package=inequality) | [![Downloads](https://cranlogs.r-pkg.org/badges/inequality)](https://CRAN.R-project.org/package=inequality) |
| [**predictset**](https://github.com/charlescoverdale/predictset) | Conformal prediction (regression, classification, Mondrian) | [![CRAN](https://www.r-pkg.org/badges/version/predictset)](https://CRAN.R-project.org/package=predictset) | [![Downloads](https://cranlogs.r-pkg.org/badges/predictset)](https://CRAN.R-project.org/package=predictset) |
| [**nowcast**](https://github.com/charlescoverdale/nowcast) | Economic nowcasting (bridge equations, mixed-frequency) | [![CRAN](https://www.r-pkg.org/badges/version/nowcast)](https://CRAN.R-project.org/package=nowcast) | [![Downloads](https://cranlogs.r-pkg.org/badges/nowcast)](https://CRAN.R-project.org/package=nowcast) |
| [**inflationkit**](https://github.com/charlescoverdale/inflationkit) | Inflation analysis (decomposition, persistence, Phillips curve) | [![CRAN](https://www.r-pkg.org/badges/version/inflationkit)](https://CRAN.R-project.org/package=inflationkit) | [![Downloads](https://cranlogs.r-pkg.org/badges/inflationkit)](https://CRAN.R-project.org/package=inflationkit) |
| [**mpshock**](https://github.com/charlescoverdale/mpshock) | Monetary policy shock and stance series for empirical macro | | |
| [**yieldcurves**](https://github.com/charlescoverdale/yieldcurves) | Yield curve fitting (Nelson-Siegel, Svensson, PCA) | [![CRAN](https://www.r-pkg.org/badges/version/yieldcurves)](https://CRAN.R-project.org/package=yieldcurves) | [![Downloads](https://cranlogs.r-pkg.org/badges/yieldcurves)](https://CRAN.R-project.org/package=yieldcurves) |
| [**debtkit**](https://github.com/charlescoverdale/debtkit) | Debt sustainability analysis (Bohn test, fan charts, stress tests) | [![CRAN](https://www.r-pkg.org/badges/version/debtkit)](https://CRAN.R-project.org/package=debtkit) | [![Downloads](https://cranlogs.r-pkg.org/badges/debtkit)](https://CRAN.R-project.org/package=debtkit) |
| [**climatekit**](https://github.com/charlescoverdale/climatekit) | Climate indices (35 temperature, precipitation, drought metrics) | [![CRAN](https://www.r-pkg.org/badges/version/climatekit)](https://CRAN.R-project.org/package=climatekit) | [![Downloads](https://cranlogs.r-pkg.org/badges/climatekit)](https://CRAN.R-project.org/package=climatekit) |
| [**inflateR**](https://github.com/charlescoverdale/inflateR) | Inflation adjustment for price series | [![CRAN](https://www.r-pkg.org/badges/version/inflateR)](https://CRAN.R-project.org/package=inflateR) | [![Downloads](https://cranlogs.r-pkg.org/badges/inflateR)](https://CRAN.R-project.org/package=inflateR) |
| [**ivcheck**](https://github.com/charlescoverdale/ivcheck) | Instrumental variable validity tests | | |

#### Products

[**econprofile.com**](https://econprofile.com) : Economic profiles for 391 UK local authorities. Interactive maps, IO impact calculator, compare tool.

[**Macroeconomics with R**](https://macrowithr.com) : 14-chapter applied macro textbook. UK, European, and international data. Uses the packages above.
