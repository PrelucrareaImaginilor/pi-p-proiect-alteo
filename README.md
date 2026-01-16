
# Predictia eruptiilor solare pe baza imaginilor AIA si HMI
Demo link : https://youtu.be/2E4WWWu42TQ
## Varianta intermediara

<details>
<summary> <b>Tabel documentație laborator 2</b></summary>

| Nr. | Autor/An | Titlu proiectului | Domeniu | Tehnologii | Abordare | Rezultate | Limitări | Comentarii |
|-----|-----------|-------------------|----------|-------------|-----------|------------|------------|-------------|
| 1 | **Julia Bringewald / 2025** | *Solar Flare Forecast: A Comparative Analysis of Machine Learning Algorithms for Predicting Solar Flare Classes* | Solar Flares Prediction | `GridSearchCV`, `StandardScaler` | Colectarea și procesarea datelor → antrenarea algoritmilor → evaluare | XGBoost are cea mai bună performanță, urmat de KNN și Random Forest | Set de date mic | — |
| 2 | **P. A. Vysakh/Prateek Mayank / 2023** | *Solar Flare Prediction and Feature Selection Using a Light-Gradient-Boosting Machine Algorithm* | Solar Flares Prediction | `SunPy`, `GridSearch`, `SMOTE` | Colectarea și procesarea datelor → antrenarea algoritmilor → evaluare | Acuratete foarte buna pentru imaginile fara eruptii(aprox 95%), insa acuratete moderata pentru cele cu eruptii(aprox. 55%) | Set de date mic pentru imaginile cu eruptii | — |
| 3 | **Xuebao Li, Yanfang Zheng, Xinshuo Wang, and Lulu Wang / 2020** | *Predicting Solar Flares Using a Novel Deep Convolutional Neural Network* | Solar Flares Prediction | `Keras`, `TensorFlow` | Colectarea și procesarea datelor → antrenarea retelei CNN → evaluare si comparare cu rezultate anterioare | Acuratete foarte buna pentru imaginile C class si M class | Set de date mic pentru imaginile X class, de aici si o acuratete scazuta | — |
| 4 | **Eric Jonas, Monica Bobra / 2018** | *Flare Prediction Using Photospheric and Coronal Image Data* | Solar Flares Prediction | `SunPy`, `PyWren` | Colectarea și procesarea datelor → antrenarea algoritmilor → evaluare  | Acuratete buna pentru imaginile C class si M class | O acuratete mai scazuta pentru clasa X | — |
| 5 | **Yasser Abduallah, Jason T. L. Wang, Yang Nie, Chang Liu and Haimin Wang / 2021** | *DeepSun: machine-learning-as-a-service for solar flare prediction* | Solar Flares Prediction | `Python`, `scikit-learn` | Colectarea și procesarea datelor → antrenarea algoritmilor → evaluare  | Acuratete buna pentru imaginile C class si M class. Algoritmul Ensemble are cele mai bune rezultate | O acuratete mai scazuta pentru clasa X | — |

</details>
## 1.Input
- Colectarea si organizarea datelor -> Colectarea imaginilor de tipul AIA si HMI
  
## 2.Preporcesare
- Calibrarea imaginilor -> corectie, aplicare filtre
- Normalizarea datelor -> normalizare si redimensionare
- Filtrarea datelor -> eliminarea imaginol necorespunzatoare
  
## 3.Etapa intermediara
- Antrenarea ML
- Detectia regiunilor active -> localizarea zonelor cu camp magnetic intens
- Extractie trasaturi ->analizarea elementelor si asemanarilor dintre imagini pentru clasificare
  
## 4.Postprocesare
- Filtrarea si maparea rezultatealor -> impartirea imaginilor in clase de imagini
  
## 5. Output
- Analiza rezultatelor -> Verificare si comparare a acuratetii
  


