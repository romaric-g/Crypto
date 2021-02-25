# Question 1

La valeur est 01100001 (97) ce qui correspond à la lettre A

# Question 2

Quand le nombre est paire, c'est un 0, quand il est impaire c'est un 1

# Question 3

Un nombre paire est divisible par 2

# Question 4

Pour 01100001: 

`0*128 + 1*64 + 1*32 + 0*16 + 0*8 + 0*4 + 0*2 + 1*1 = 97`

En js:

```javascript
var digit = parseInt(binary, 2);
```

# Question 5

Le message caché:
`
BRAVO ! Envoyez ce texte en clair sans perdre une minute a l'adresse suivante: jpsalmon@u-bordeaux3.fr avec le titre 'MMI SECU TP2 EXO1 NOM1, puis repondez aux instructions suivantes: 1)Imaginez une solution pour delimiter la fin du message. 2)Envoyez votre reponse par mail avec le titre 'MMI SECU TP2 EXO2 NOM1'. 3)Ajouter la possibilite a votre programme de choisir le nombre de bits sur lesquels seront codes le message. 4)Envoyer votre chef-oeuvre par mail avec le titre 'MMI SECU TP2 EXO3 NOM1'. BRAVO!
`