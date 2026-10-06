# Big Data Project: Content Recommendation System
**Team members:**
- Komlan Jeremie NODZO
- Ayoub ABBAS
- Valentin NGUYEN
- Aaron AIDOUDI

## Submission
- **Code:** `ContentRecommendationSystem.ipynb` is the complete notebook implementing the recommendation system. It contains dataset generation, database setup, recommendation engine, real-time simulation, and all experiments.

- **Report:** `AbbasAidoudiNodzoNguyen.pdf`,  covering problem formulation, related work, solution, experiments, limitations, and references.

## Execution & Requirements
**No external data files required.** The notebook generates the synthetic dataset (4,000 users, 60,000 interactions) directly from the *"Social Media Ad Engagement Dataset"* structure.

**Tested on Google Colab:**
- Hardware: Standard Colab CPU (12.7 GB RAM)
- Total Execution Time: ~10 minutes

## Dependencies
Main dependencies include:
* `psycopg2-binary`, `sqlalchemy` (PostgreSQL)
* `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`