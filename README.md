# Heart-disease-prediction Using Microsoft Azure-Machine-Learning

## About the project
The project aims to predict the probability of an individual developing cardiovascular disease using a machine learning model via Microsoft Azure Machine Learning.

## Project architecture

**The project** aims to collect data from an API. Using Data Factory's ingestion mechanisms, a pipeline will be created to extract this data and store it in a data lake. This data will then be retrieved from Azure Data Lake via Azure Machine Learning to make predictions.



## Signification des features :

Age : âge (années)
Sex : sexe (0 = femme, 1 = homme)
Angine : douleur thoracique (1 = angine stable, 2 = angine instable, 3 = autres douleurs, 4 = asymptomatique)
Blood_Pressure : pression artérielle au repos (mmHg)
Cholesterol : taux de cholestérol (mg/dl)
Glycemia : glycémie à jeun (0 = Moins de 120 mg/dl, 1 = Plus de 120 mg/dl)
ECG : résultats de l'électrocardiogramme (0 = Normal, 1 = Anomalies, 2 = Hypertrophie)
Heart_Rate : fréquence cardiaque maximale atteinte
Angina_After_Sport : angine de poitrine après un effort physique (0 = non, 1 = oui)
ECG_Angina : mesure de l'angine de poitrine sur l'électrocardiogramme
ECG_Slope : pente de l'électrocardiogramme (1 = en hausse, 2 = stable, 3 = en baisse)
Fluoroscopy : résultats de la fluoroscopie (0 = pas d'anomalie, 1 = faible, 2 = moyen, 3 = élevé)
Thalassaemia : présence d'une thalassémie (3 = Non, 6 = Thalassémie sous contrôle, 7 = Thalassémie instable)
Disease : présence d'une maladie cardiovasculaire (0 = Non, 1/2/3/4 = Oui)

## Architecure Schema
<div align="center">
  <img src="https://github.com/user-attachments/assets/008c98f0-9ce2-4955-82e3-0cdfb602d655" width="600" height="400"/>
  
</div><br>
Télecharger l'image via ce lien : ![image](https://github.com/user-attachments/assets/008c98f0-9ce2-4955-82e3-0cdfb602d655)
