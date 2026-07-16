## Jacob Byron-McKay

Senior Data Scientist with 6+ years across the New Zealand public sector (health
and analytics) - working end-to-end from messy operational data through to
production analytics, machine learning, and decision-ready reporting. Māori
(Ngāti Apa). Strong in R, SQL and Power BI, building in Python, and hands-on with
applied ML/NLP, retrieval-augmented generation, and locally-run large language
models in regulated, privacy-sensitive settings.

### About these repositories

They are public-data portfolio projects that demonstrate techniques I use in
professional work. Work projects use confidential data and can't be published, so
these examples are built on open datasets - the methods, the rigour and the
decisions are the same.

### Selected work

- **[clinical-guideline-rag](https://github.com/jacobByron-McKay/clinical-guideline-rag)**:
  retrieval-augmented question answering over UK NICE clinical guidelines, running
  entirely locally (Ollama + Chroma): grounded answers that cite the exact
  recommendation and refuse when the guidelines don't cover the question, with a RAG
  evaluation harness for retrieval quality and faithfulness.

- **[hospital-readmission-risk](https://github.com/jacobByron-McKay/hospital-readmission-risk)**:
  an end-to-end, equity-aware 30-day hospital readmission model: leakage-aware
  data preparation, probability calibration, SHAP explainability, a fairness audit
  across demographic groups, and a FastAPI service with tests and CI.

- **[smoking-cessation-effect](https://github.com/jacobByron-McKay/smoking-cessation-effect)**:
  causal inference: the effect of quitting smoking on weight gain, estimated with
  g-computation, inverse-probability weighting and a doubly-robust estimator, plus
  overlap/balance diagnostics and an E-value sensitivity analysis.

- **[flu-forecasting](https://github.com/jacobByron-McKay/flu-forecasting)**:
  short-term influenza forecasting evaluated with rolling-origin backtesting
  against honest baselines; a gradient-boosted model beats seasonal-naive, with a
  regime-aware read on the COVID-era disruption.

- **[clinical-note-classifier](https://github.com/jacobByron-McKay/clinical-note-classifier)**:
  classic ML vs a local Llama on clinical-text classification: a numbers-backed
  look at when a trained model beats an LLM, and when it doesn't.

- **[health-analytics-dbt](https://github.com/jacobByron-McKay/health-analytics-dbt)**:
  analytics engineering: a tested, documented dbt + DuckDB pipeline turning raw
  health records into layered staging and mart models with data-quality tests.

- **[health-dashboard-powerbi](https://github.com/jacobByron-McKay/health-dashboard-powerbi)**:
  an interactive Power BI dashboard on top of those dbt marts: a star-schema model,
  DAX measures, and coordinated multi-page report, shipped as a text-based project
  (`.pbip`) alongside the built `.pbix`.

### Toolbox

R (tidymodels, Shiny) · SQL & database design · Power BI (DAX, RLS) · Python
(pandas, scikit-learn) · machine learning · calibration & SHAP explainability ·
causal inference · time-series forecasting · NLP & text classification · GenAI /
LLMs (local Llama, RAG, LangChain, vector databases, evaluation) · dbt / analytics engineering
· equity-aware analytics

[LinkedIn](https://www.linkedin.com/in/jacob-byron-mckay-286319ab/)
