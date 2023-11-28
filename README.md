# SYL_Labo3

## Questions

### Question 1
#### Que se passerait-il si l'entrée clk_i d'un des composants n'était pas reliée au signal d'horloge?

Sa sortie ne sera jamais active et donc le résultat aura toujours un bit à 0 à cette position. Le décalage ne fonctionnera donc pas.


### Question 2
#### Si l'on charge la valeur `0b0110` dans le registre et que l'on effectue un décalage de 2 bits vers la droite, puis un décalage de 3 bits vers la gauche, quelle valeur va-t-on obtenir en sortie? Démontrez les étapes pour obtenir votre résultat.

Nous obtenons la valeur `0b1000`.
- LOAD `0110`
- Shift right `0011`
- Shift right `0001`
- Shift left `0010`
- Shift left `0100`
- Shift left `1000`

### Question 3
#### Mettez en évidence les différentes étapes ci-dessus dans votre chronogramme.

![Chronogram](ChronogramQ3Capture.png)

### Question 4
#### Votre circuit a-t-il le comportement attendu? ARgumentez et développez votre réponse.

### Question 5
#### Avec une fréquence d'horloge `clk_i` de 30MHz, calculez le nombre de cycle à atte de cycles visé en fonction de la fréquence et l'équivalence encodée au format hexadécimal sur 28 bits `0xffffffff`.

### Question 6
#### Démontrez que le fonctionnement attendu est conforme en mettant en évidence les différents états sur votre chronogramme. Développez et argumentez votre réponse.
