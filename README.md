# Detección de Diabetes con Espectroscopia Raman utilizando técnicas de aprendizaje supervisado

El código presente corresponde con el desarrollo del trabajo de fin de Máster de Inteligencia Artificial de la Universidad de la Rioja. El trabajo se titula "Detección de Diabetes con Espectroscopia Raman utilizando técnicas de aprendizaje supervisado" cuyo es tratar de mejorar la calidad de la detección de diabetes mellitus tipo 2, mediante la comparación de métodos de aprendizaje supervisado, junto con datos obtenido a través de la Espectroscopia Raman. La metodología utilizada está basada en CRISP-DM en la que se preprocesan los datos utilizando Análisis de Componentes Principales (PCA). Se entrenaron varios modelos y se evaluaron utilizando LeaveOneOut como método de validación cruzada y recall como métrica para comparar los modelos. En cuanto a resultados, el mejor modelo se construyó con el algoritmo K-nearest neighbor (KNN) con un recall de 0.91, y el algoritmo que mejor funcionó es Naive Bayes (NB) con una media de recall de 0.88. Se concluye que hacer uso de PCA mejora notablemente los resultados y que los algoritmos que han funcionado mejor son NB, KNN y máquinas de vector de soporte.

Los datos utilizados se obtuvieron en [https://www.kaggle.com/codina/raman-spectroscopy-of-diabetes](https://www.kaggle.com/codina/raman-spectroscopy-of-diabetes), los cuales fueron utilizados en el trabajo de Guevara, E., Torres-Galván, J. C., Ramírez-Elías, M. G., Luevano-Contreras, C., & González, F. J. (2018). Use of Raman spectroscopy to screen diabetes mellitus with machine learning tools. Biomedical Optics Express, 9(10), 4998–5010.
