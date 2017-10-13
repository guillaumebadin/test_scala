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

## Envoie d'un résultat 
On pourra à l'aide d'un Webservice envoyer un ou plusieurs résultats. 

## Authentification
Aucune authentification

## Lecture de mes résultats (Patients)
A l'aide de mon ID patient, je pourrais récupérer tous mes résultats

## Lecture des résultats correspondants 
Je suis un correspondants (Médecin, Infirmière) je veux récupérer tous les résultats de mes patients. 

