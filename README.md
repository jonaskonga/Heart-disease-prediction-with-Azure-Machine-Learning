# Heart-disease-prediction Using Microsoft Azure-Machine-Learning

## About the project
The project aims to predict the probability of an individual developing cardiovascular disease using a machine learning model via Microsoft Azure Machine Learning.

## Project architecture

**The project** aims to collect data from an API. Using Data Factory's ingestion mechanisms, a pipeline will be created to extract this data and store it in a data lake. This data will then be retrieved from Azure Data Lake via Azure Machine Learning to make predictions.



## Meaning of features  :
<ul>
<li>Age : âge (années)</li>
<li>Sex : sexe (0 = femme, 1 = homme)</li>
<li>Angine : douleur thoracique (1 = angine stable, 2 = angine instable, 3 = autres douleurs, 4 = asymptomatique)</li>
<li>Blood_Pressure : pression artérielle au repos (mmHg)</li>
<li>Cholesterol : taux de cholestérol (mg/dl)</li>
<li>Glycemia : glycémie à jeun (0 = Moins de 120 mg/dl, 1 = Plus de 120 mg/dl)</li>
<li>ECG : résultats de l'électrocardiogramme (0 = Normal, 1 = Anomalies, 2 = Hypertrophie)</li>
<li>Heart_Rate : fréquence cardiaque maximale atteinte</li>
<li>Angina_After_Sport : angine de poitrine après un effort physique (0 = non, 1 = oui)</li>
<li>ECG_Angina : mesure de l'angine de poitrine sur l'électrocardiogramme</li>
<li>ECG_Slope : pente de l'électrocardiogramme (1 = en hausse, 2 = stable, 3 = en baisse)</li>
<li>Fluoroscopy : résultats de la fluoroscopie (0 = pas d'anomalie, 1 = faible, 2 = moyen, 3 = élevé)</li>
<li>Thalassaemia : présence d'une thalassémie (3 = Non, 6 = Thalassémie sous contrôle, 7 = Thalassémie instable)</li>
<li>Disease : présence d'une maladie cardiovasculaire (0 = Non, 1/2/3/4 = Oui)</li>
</ul>

## Architecure Schema
<div align="center">
  <img src="https://github.com/user-attachments/assets/008c98f0-9ce2-4955-82e3-0cdfb602d655" width="600" height="400"/>
</div><br>

Télecharger l'image via ce lien :https://github.com/user-attachments/assets/008c98f0-9ce2-4955-82e3-0cdfb602d655

## Languages and Tools:

<div align="left">
  <img src="https://github.com/user-attachments/assets/750e201c-21e9-42b7-a18b-b98f6c2374a2" title="Azure Data Factory" alt="Azure Data Factory" width="60" height="60"/>&nbsp;
  <img src="https://github.com/user-attachments/assets/0f20c400-570e-431c-b688-20983fe1a75a" title="Azure Data Lake Storage" alt="Azure Data Lake Storage" width="60" height="60"/>&nbsp;
  <img src="https://github.com/user-attachments/assets/02118f60-f9e4-47ed-a25b-f219463324c0" title="Azure Machine Learning" alt="Azure Machine Learning" width="60" height="60"/>&nbsp;
</div>


