# fiche de synthese C info1

## Variable 

### Déclaration de variable
```c 
int ne; //pour déclarer un nombre entier
float nr; //pour déclarer un nombre réel
char c; //pour déclarer un caractère
char* s; //pour déclarer une chaine de caractère
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

La fonction printf() permet d'afficher à l'ecran une variable ou un message.

exemple : 

```c
printf("message"); //va faire apparaitre à l'ecran : message
```
#### Affichage d'une variable

exemple : 

```c
int nb;
printf("%d",nb); //va faire apparaitre à l'ecran le contenue de la variable int nb
```
Pour visualiser des variable d'autres type il faudra changer l'indicateur "%d" utilisé dans l'exemple précédent 

exemple : 

```c
int nb;
float nr;
char c;
char* s;
printf("%d",nb); //va faire apparaitre à l'ecran le contenue de la variable int nb
printf("%f",nr); //va faire apparaitre à l'ecran le contenue de la variable float nr
printf("%c",c); //va faire apparaitre à l'ecran le contenue de la variable char c
printf("%s",s); //va faire apparaitre à l'ecran la chaine de caractère contenue dans la variable char* s
```
on peut aussi bien afficher plusieurs variable de même type ou non en une seul ligne

exemple : 

```c
int nb1=2 , nb2=3
printf("les nombre sont %d et %d",nb1,nb2) //va faire apparaitre à l'ecran : les nombre sont 2 et 3
```

### Lecture au clavier

#### Lecture multitype : scanf

La fonction scanf() permet de lire une ou plusieurs variable(s) au clavier. 

exemple : 

```c
int nb1,nb2;
printf("entrez 2 nombre entier");
scanf("%d,%d,&nb1,&nb2); // le "&" devant le nom de la variable sert à indiquer l'adresse de la variable indiquée
printf(" les nombres sont: %d et %d",nb1,nb2);
```






## Structure de Contrôles

## Variable Composées 

## Fonctions
