# Présence en cours

Analyse de données sur le nombre de personne présent en cours en Sprint entre mars et mai 2022.

## Rendu

Le rendu est visible [ici](https://voila.oh-my-g.fr/voila/render/Présence%20en%20cours/Presence-en-cours.ipynb)

## Données

Les données sont au format suivant :

| Nom de la colonne | Description |
| ----------------- | ----------- |
| Date | Date à laquelle le cours à eu lieu au format **aaaa-mm-jj hh:mm**|
| Cours | La référence du cours parmi : **PY215**, **PY222**, **PY404**, **PY421**, **PY423**, **PY531** |
| Type | Le type de cours parmi : **TD**, **TP**, **CM**, **Partiels** |
| Effectif | Le nombre de personnes présentes en cours |

Les références des cours sont les suivantes :

| Référence | Nom du cours |
| --- | --- |
| PY215 | Physique Expérimentale |
| PY222 | Modélisation Numérique en Physique |
| PY404 | Mécanique Avancée |
| PY421 | Ondes et Electromagnétisme |
| PY423 | Méthodes Mathématiques |
| PY531 | Astrophysique |

## Conclusion

Il semblerait que l'heure et la matière aient bien un impact sur la présence en cours même si il plutôt difficile de savoir si les deux sont liés dans certains cas.  
De plus, on note une lente baisse de participation tout au long du semestre.

## TODO

- [ ] Inclure les partiels
- [ ] Plus intéractif (bqplot ?)
- [ ] Plus de détails par rapport au type de cours
