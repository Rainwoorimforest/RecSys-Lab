# 🚀 RecSys-Deep-Dive: Cold Start & Deep Learning

이 저장소는 추천 시스템의 고전적인 난제인 **Cold Start 문제**를 해결하고, **Deep Learning 기반의 최첨단 추천 알고리즘**을 심도 있게 스터디하며 구현하는 공간입니다.

이전 프로젝트 [Warchiving](https://github.com/Warchiving/Warchiving-release)에서의 고민을 확장하여, 데이터 희소성 문제를 극복하고 사용자 경험을 극대화하는 모델을 탐구합니다.

---

## 📌 Focus Areas

* **Cold Start Solutions:** 신규 사용자 및 아이템에 대한 데이터 부족 문제를 해결하기 위한 콘텐츠 기반 필터링(CB) 및 하이브리드 기법 연구.
* **Deep Learning Models:** NCF, DeepFM, Wide & Deep 등 딥러닝 기반의 비선형 특징 추출 및 임베딩 기술 구현.
* **Best Practices:** [Microsoft Recommenders](https://github.com/recommenders-team/recommenders)의 방법론을 벤치마킹하여 데이터 전처리부터 평가 지표까지 표준화된 파이프라인 구축.
* **references & study** : [eugeneyan의 테크블로그?](https://eugeneyan.com/writing/recsys-llm/)
---


## 📚 Industry Tech Analysis

실제 비즈니스 환경에서 추천 시스템이 어떻게 설계되고 운영되는지 아카이빙 하였습니다. 체계적으로 내용을 정리 요약하여 프로젝트나 실무에서 활용할 예정입니다.

| Source | Core Concept | Key Takeaways & Engineering Points |
| :--- | :--- | :--- |
| **오늘의집** | [Multi-Stage RecSys](https://www.bucketplace.com/post/2024-03-26-%EA%B0%9C%EC%9D%B8%ED%99%94-%EC%B6%94%EC%B2%9C-%EC%8B%9C%EC%8A%A4%ED%85%9C-1-multi-stage-recommender-system/) | **Retrieval-Ranking-Reranking**으로 이어지는 실시간 파이프라인 설계 및 서빙 최적화 전략 |
| **Twitter (X)** | [The Algorithm](https://github.com/twitter/the-algorithm) | **Real Graph 기반의 관계성 설계** 및 차단 사용자 필터링 등 사용자 경험을 고려한 Re-Ranking 로직 |
| **Toss** | [E-commerce Data](https://toss.im/career/article/38431) | 비정형 데이터의 **정교한 카테고리화**를 통한 데이터 품질 개선 및 추천 정교화의 중요성 |


---

## 📂 Roadmap & Topics

### 1. Fundamentals & Cold Start
- [ ] Collaborative Filtering (User-based, Item-based)
- [ ] Matrix Factorization (ALS, SVD)
- [ ] Content-based Filtering for Cold Start (TF-IDF, Word2Vec)

### 2. Deep Learning Based Recommenders
- [ ] **NCF (Neural Collaborative Filtering)**: MLP와 GMF의 결합
- [ ] **Wide & Deep Learning**: 암기(Memorization)와 일반화(Generalization)의 공존
- [ ] **DeepFM**: Factorization Machines의 딥러닝 확장 버전

### 3. Advanced Topics
- [ ] Graph Neural Networks (GCN) for Recommendation
- [ ] Multi-Task Learning for Ranking & Retrieval
- [ ] Session-based Recommendation

---

## 🛠 Tech Stack

- **Language:** Python 3.10
- **Frameworks:** PyTorch
- **Libraries:** Pandas, NumPy, Scikit-Learn, Surprise
- **Reference:** Microsoft Recommenders Open Source

---

## 📊 Evaluation Metrics

추천 품질을 다각도에서 검증하기 위해 다음 지표를 활용합니다.

- **Ranking:** NDCG, MAP, Precision@K, Recall@K
- **Rating:** RMSE, MAE
- **Diversity:** Coverage, Novelty

---

## 🔗 References

- [Microsoft Recommenders Repository](https://github.com/recommenders-team/recommenders)
- [Warchiving: Release (Previous Work)](https://github.com/Warchiving/Warchiving-release)
- Papers: (추후 노션으로 정리할 예정)
