[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/BzgEFjMi)

Predictia eruptiilor solare pe baza imaginilor AIA si HMI

<details>
<summary> <b>Tabel documentație laborator 2</b></summary>

| Nr. | Autor/An | Titlu proiectului | Domeniu | Tehnologii | Abordare | Rezultate | Limitări | Comentarii |
|-----|-----------|-------------------|----------|-------------|-----------|------------|------------|-------------|
| 1 | **Julia Bringewald / 2025** | *Solar Flare Forecast: A Comparative Analysis of Machine Learning Algorithms for Predicting Solar Flare Classes* | Solar Flares Prediction | `GridSearchCV`, `StandardScaler` | Colectarea și procesarea datelor → antrenarea algoritmilor → evaluare | XGBoost are cea mai bună performanță, urmat de KNN și Random Forest | Set de date mic | — |
| 2 | **P. A. Vysakh/Prateek Mayank / 2023** | *Solar Flare Prediction and Feature Selection Using a Light-Gradient-Boosting Machine Algorithm* | Solar Flares Prediction | `SunPy`, `GridSearch`, `SMOTE` | Colectarea și procesarea datelor → antrenarea algoritmilor → evaluare | Acuratete foarte buna pentru imaginile fara eruptii(aprox 95%), insa acuratete moderata pentru cele cu eruptii(aprox. 55%) | Set de date mic pentru imaginile cu eruptii | — |
| 3 | **Xuebao Li, Yanfang Zheng, Xinshuo Wang, and Lulu Wang / 2020** | *Predicting Solar Flares Using a Novel Deep Convolutional Neural Network* | Solar Flares Prediction | `Keras`, `TensorFlow` | Colectarea și procesarea datelor → antrenarea retelei CNN → evaluare si comparare cu rezultate anterioare | Acuratete foarte buna pentru imaginile C class si M class | Set de date mic pentru imaginile X class, de aici si o acuratete scazuta | — |
| 4 | **Eric Jonas, Monica Bobra / 2018** | *Flare Prediction Using Photospheric and Coronal Image Data* | Solar Flares Prediction | `SunPy`, `PyWren` | Colectarea și procesarea datelor → antrenarea algoritmilor → evaluare  | Acuratete buna pentru imaginile C class si M class | O acuratete mai scazuta pentru clasa X | — |
</details>
