# Evan Guennou

**Ingénieur IA · Data science & machine learning · Paris**

Je conçois des outils data et IA de bout en bout : préparation des données, modèles et recherche, évaluation, API et interfaces. Mon travail public couvre la recherche hybride, le traitement de documents, les pipelines ELT et le machine learning appliqué.

**Disponible à partir d’octobre 2026** pour un CDI ou des missions freelance.

[CV Data Scientist (FR)](https://github.com/Evanguennou29/Portfolio/blob/main/public/cv/evan-guennou-data-scientist-fr.pdf) · [CV ML Engineer (FR)](https://github.com/Evanguennou29/Portfolio/blob/main/public/cv/evan-guennou-ml-engineer-fr.pdf) · [LinkedIn](https://www.linkedin.com/in/evan-guennou/) · [Email](mailto:evan.guennou@gmail.com)

## Expérience

- **Thales, 2026 :** ingénieur en IA générative, avec des travaux sur un assistant de recherche documentaire et un agent de traitement des incidents en environnement sécurisé.
- **CANAL+, 2025 :** data analyst et data scientist, avec un modèle de classification et de ranking pour la rétention ainsi que des analyses BI.

Le [dépôt Portfolio](https://github.com/Evanguennou29/Portfolio) présente le parcours complet et les CV en français et en anglais.

## Projets sélectionnés

### [DECP Copilot](https://github.com/Evanguennou29/decp-copilot) · Recherche hybride et évaluation

Recherche de marchés publics français par filtres SQL, BM25 et embeddings, avec résultats sourcés et API FastAPI. Sur 45 questions vérifiées, le dépôt rapporte un **Recall@10 de 0,60**, contre **0,18** pour la recherche sémantique seule ; le résultat dépend du corpus et du jeu d’évaluation. [Voir la démo](https://decp-copilot.vercel.app/) · [Lire l’évaluation](https://github.com/Evanguennou29/decp-copilot/blob/main/eval/results.md).

### [Eco2Mix ELT](https://github.com/Evanguennou29/eco2mix-elt) · Data engineering

Pipeline reproductible sur les données ouvertes de RTE : ingestion, Parquet, DuckDB, dbt et orchestration Dagster. Un tableau de bord permet d’explorer l’intensité carbone par heure, région et saison. [Voir le tableau de bord](https://eco2mix-elt-h7xesyj8z8smnyo34ezqhz.streamlit.app/).

### [Intelligent Document Processing](https://github.com/Evanguennou29/intelligent-document-processing-multimodal-genai-main) · IA multimodale

Pipeline Python pour transformer scans et PDF en JSON structuré : OCR, extraction par modèle de vision et validation Pydantic, avec exécution cloud ou locale.

### [PalmerMorphoBench](https://github.com/Evanguennou29/PalmerMorphoBench-MachineLearning) · Machine learning reproductible

Comparaison d’une baseline et de trois modèles sur Palmer Penguins. La sélection repose sur une validation croisée stratifiée, avec prétraitement dans les pipelines et test séparé. Le modèle retenu obtient un **F1 macro moyen de 0,976 ± 0,037** en validation croisée.

## Technologies utilisées

**Data & ML :** Python, SQL, pandas, scikit-learn, XGBoost, DuckDB, dbt, Dagster  
**IA appliquée :** RAG, recherche sémantique, OCR, LLM, FastAPI  
**Livraison :** Docker, GitHub Actions, API et interfaces web
