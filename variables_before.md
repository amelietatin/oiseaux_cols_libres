Tablaux finaux:

'variable_name': dtype, example

1) Resume par jour:
--> dans ce tableau on trouve le nombre d'individus par espèce observé (sans heure d'observation, total par jour). Chaque ligne est la somme d'observation pour une espèce par jours.
--> données climatiques par jours
--> l'heure de début et de fin d'observation
--> observateurs: nom, nombre actif, nombre present

- 'id' : int64
- 'date' : object
- 'observers': object
- 'weather': float64
- 'windspeed_bfr': float64
- 'wind_ms': float64
- 'winddirection': object
- 'cloudcover': float64
- 'cloudheight': float64
- 'precipitation': object
- 'perc_duration': float64
- 'visibility': float64
- 'temperature': float64
- 'observersactive': float64
- 'observerspresent': float64
- 'remarks': object
- 'created': object
- 'changed': object
- 'start': object
- 'stop': object
- 'speciesid': float64
- 'species': object
- 'direction1': object
- 'direction2': object
- 'maxlocal': object

2) Detail journalier:
--> dans ce tableau on trouve le nombre d'individus par espèce observé par observation (avec heure d'observation). Chaque ligne est une observation.
--> on y trouve aussi les données sex/age, en revanche beaucoup de dates n'ont pas de données
--> les variables les plus importances ici: date, timestamp, species, direction1, direction2, local
--> mais on peut quand même garder age, sex, plumage

- 'date': object
- 'timestamp': object
- 'countid': int64 1
- 'speciesid': int64
- 'species': object
- 'direction1': int64
- 'direction2': int64
- 'local': int64
- 'remarkable': bool
- 'remarkablelocal': bool
- 'age': object
- 'sex': object
- 'plumage': object
- 'remark': object
- 'height': float64
- 'location': float64 
- 'migtype': object
- 'counttype': object
- 'exactdirection1': object
- 'exactdirection2': float64
- 'groupid': float64
- 'submitted': object
