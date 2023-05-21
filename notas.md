# Notas
## Imputers 
- SimpleImputer
- KNNImputer
- IterativeImputer

## Scalers
- MinMaxScaler
- StandardScaler
- Normalizer
- PowerTransformer

## Feature Selection
- Pearson Correlation
- PCA
- SelectKBest
- SequentialFeatureSelection

## Models
- DecisionTreeClassifier
- RandomForestClassifier
- SVC (Support Vector Classification)
- LogisticRegression
- KNeighborsClassifier

## Best Combination

- Imputer --||--            IterativeImputer(random_state=42)
- Scaler --||--             StandardScaler()
- Feature_selector --||--   SequentialFeatureSelector(clf, n_features_to_select=35, scoring=scorer)
- Classifier --||--         SVC(C=100, gamma=0.1, random_state=42)
