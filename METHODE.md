# Méthode
1. Conserver les deux classeurs originaux ; lire la feuille Data et les métadonnées.
2. Filtrer BEN, BFA, CIV, GHA, SEN, TGO et les années 2000–2024.
3. Dépivoter les colonnes d’années ; une ligne par pays et année.
4. Contrôler l’unicité CodePays + Année, les types et les valeurs manquantes.
5. Fusionner sur CodePays + Année ; 150 correspondances attendues dans ces éditions.
6. Conserver les valeurs brutes sur 0–100. Pour les mesures d’affichage, diviser la moyenne par 100 et appliquer le format pourcentage.
7. Couverture initiale/finale : filtrer l’année 2000/2024 en conservant le contexte pays.
8. Variation en points : valeur brute finale − initiale, ou différence des mesures sur 0–1 multipliée par 100.
9. Variation relative (%) : (finale − initiale) / initiale × 100. En DAX, DIVIDE sans multiplication par 100 si le résultat reçoit un format pourcentage.
10. Écart annuel en points : eau − assainissement ; variation de l’écart : écart 2024 − écart 2000.

Les données sont complètes sur le périmètre étudié ; ne pas remplacer d’éventuelles absences futures par zéro. Les comparaisons par pays évitent d’interpréter une moyenne simple comme une couverture régionale.

## Définitions
Eau : population utilisant une source améliorée avec un trajet aller-retour de collecte de 30 minutes au maximum, attente comprise, ou un niveau de service supérieur.
Assainissement : population utilisant des installations améliorées non partagées avec d’autres ménages, ou un niveau de service supérieur.

Les moyennes nationales masquent les disparités territoriales et sociales. Un service au moins élémentaire n’est pas nécessairement un service géré en toute sécurité. L’écart entre deux couvertures ne mesure pas la proportion exacte de personnes ayant l’eau mais pas l’assainissement. Une réduction de cet écart peut résulter d’une baisse de la couverture en eau. Les pourcentages ne doivent pas être additionnés entre pays ; leur moyenne simple n’est pas une couverture régionale pondérée. Ces comparaisons descriptives ne permettent pas d’attribuer les évolutions à une cause.

Source : Banque mondiale, données OMS/UNICEF Joint Monitoring Programme (JMP).
- [Eau potable — SH.H2O.BASW.ZS](https://data.worldbank.org/indicator/SH.H2O.BASW.ZS)
- [Assainissement — SH.STA.BASS.ZS](https://data.worldbank.org/indicator/SH.STA.BASS.ZS)
- [Définitions eau — JMP](https://washdata.org/topics/drinking-water)
- [Définitions assainissement — JMP](https://washdata.org/topics/sanitation)

Estimations officielles, non simulées. Analyse des éditions des classeurs conservées dans ce dépôt ; des révisions ultérieures peuvent modifier les séries. Date exacte du téléchargement initial non documentée. Licence des indicateurs Banque mondiale : CC BY 4.0.
