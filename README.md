# Time-Series-Forecasting
Ce programme permet d'effectuer une prédiction de séries temporelles à une variable en utilisant des réseaux de neurones recursifs (LSTM).
Dans un premier temps, les données sont chargés grace à Pandas.
Ensuite, on utilise le KNN Imputer afin de reconstituer totalement les données dans le cas où elles sont corrompues.
Les données reconstituées sont ensuite redimensionnées, avant d'être entrainé par un réseau de neurones récursifs.

