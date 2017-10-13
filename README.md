# Test technique Scala

Ta mission sera de réaliser un super serveur de résultat patient en Play2 Scala pour Ubilab. 


Format d'un résultat
```
{
  "msg_type": "inr_simple",
  "correspondent": {
    "idCorrespondent": "COUCOU",
    "profil": "ide",
    "firstName": "Erlich",
    "lastName": "Bachman",
    "mobile": "0633471153"
  },
  "patient": {
    "idPatient": "92010201867",
    "firstName": "Richard",
    "lastName": "Hendricks",
    "birthdayDate": "01-06-1986"
  },
  "result": {
    "idResult": "B71012P6823-PUIMA-/INRW",
    "dateOfResult": 1507884006000,
    "msg_type": "inr_simple",
    "msg_raw": "Pvt 12/10/2017 à 10:00:00\nDossier 525648-P-6823\nINR: 2.6 \n Laboratoire Silicon Valley"
  }
}
```

## [Obligatoire] Envoie d'un résultat 
On pourra à l'aide d'un Webservice envoyer un ou plusieurs résultats. 
Attention, tous les champs du JSON sont aubligatoires, certains champs sont formmatés. 
N'oublie pas de valider ce qu'on t'envoie

## [Obligatoire] Lecture de mes résultats (Patients)
A l'aide de mon ID patient, je pourrais récupérer tous mes résultats

## [Obligatoire] Lecture des résultats correspondants 
Je suis un correspondants (Médecin, Infirmière) je veux récupérer tous les résultats de mes patients. 

## [Obligatoire] Authentification
Aucune authentification

## [Obligatoire] Base de données
Aucune base de données (base de données en mémoire)


## [Bonus] Test unitaire
Tu peux si tu as le temps faire des tests unitaires (en fait je te recommande de commencer par ça)
`sbt test`

## [Bonus] Pagination
Tu peux si tu as le temps paginer les webservices de lectures

# Consigne de rendu
Tu doit creer un projet play2 Scala sbt, qui lancera un mini serveur implementant tous les webservices demandées. 
Pour lancer le projet je dois pouvoir faire *uniquement* la commande `sbt run`.
Une attention particulière sera données à la qualité du code, la pertinence des noms données aux méthodes mais aussi à ton API.

Tu as 2 semaines à partir du moment ou tu recevras le mail de test technique pour passer ce test. 
Si tu n'y arrive pas au bout de 2 semaine c'est que tu n'a pas le niveau ou l'envie de le faire.

Tu devras fournir un repo github avant le rendu nous permettant de cloner et de vérifier ton rendu.

A la racine du projet, tu devras rédiger en Français une documentation sur README.md avec les requêtes CURL nous permettant de tester tous tes webservices.


# cas d'élimination
Nous avons besoins de personnes rigoureuses donc voici les cas d'élimination : 
* Si le projet ne compile pas
* Si les features [Obligatoire] ne sont pas implémentés
* Si le projet n'est pas rendu à temps
* Si les consignes de rendu ne sont pas respectés

# Questions 
Tu peux poser des questions sur le test par mail à l'adresse que tu as reçu par mail.

