# fiche de synthese C info1

## Variable 

### Déclaration de variable
```c 
int ne; //pour déclarer un nombre entier
float nr; //pour déclarer un nombre réel
char c; //pour déclarer un caractère
```
on peut aussi déclarer plusieur variable sur une même ligne 
sans réutiliser plusieurs fois la déclaration de type en insérant 
des virgules entre les differentes variables du même type

exemple : 
```c
int a,b,c;
```
### Déclaration de variable avec initialisation 

on peut affecter une valeur à une variable directement lors de sa déclaration

exemple : 
```c
float nr=7.2;
```

on peut également affecter une valeur à une variable après sa déclaration 

exemple : 
```c
int x=2;
int y;

y=x; //ici y prend la valeur de x
x=x+3; //ici x va prend son ancienne valeur et y ajouter 3
Y=x+y; //ici y va prendre la nouvelle valeur de x ET la valeur de y déclarée précédemment
```


## Entrées / Sorties

### Affichage

#### Affichage simple à l'écran 

```c
printf("message"); //va faire apparaitre à l'ecran : message
```
#### Affichage d'une variable

```c
int nb;
printf("%d",nb); //va faire apparaitre à l'ecran le contenue de la variable int nb
```
Pour visualiser des variable d'autres type il faudra changer l'indicateur "%d" utilisé dnas l'exemple précédent 

```c
int nb;
float nr;
char c;
printf("%d",nb); //va faire apparaitre à l'ecran le contenue de la variable int nb
printf("%f",nr); //va faire apparaitre à l'ecran le contenue de la variable float nr
printf("%c",c); //va faire apparaitre à l'ecran le contenue de la variable char c 
```

## Structure de Contrôles

## Variable Composées 

## Fonctions
