# İnme (Stroke) Tahmin Projesi

Dengesiz sağlık verisinde inme tahmini için 3 makine öğrenmesi modelinin karşılaştırmalı analizi.

## Kullanılan Yöntemler
- SMOTE ile dengesizlik çözümü
- Lojistik Regresyon, Random Forest, XGBoost
- ROC-AUC, PR-AUC, G-Mean metrikleri

## Sonuçlar
XGBoost en yüksek Recall (%84) ile en az hasta kaçıran model oldu.

## Veri Seti
https://www.kaggle.com/datasets/shashwatwork/cerebral-stroke-predictionimbalaced-dataset

## Gereksinimler
pandas, numpy, matplotlib, seaborn, scikit-learn, imbalanced-learn, xgboost
