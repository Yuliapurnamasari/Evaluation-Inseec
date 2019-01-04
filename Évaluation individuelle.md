# 13Évaluation individuelle

## Programmation - Coaching

```
Nom : Purnamasari
Prénom :  Yulia
URL de votre compte Github : https://github.com/Yuliapurnamasari
```

## Déroulé et fonctionnement. 

L'évaluation est à faire sur [Typora](https://typora.io/). Les réponses sont à écrire dans les blocks de code. 
Pour la partie Ruby, testez votre code sur [repl.it](https://repl.it/) et copiez le dans les blocks de code prévu à cet effet. 
Une fois fini, pushez votre feuille sur Github, dans un nouveau repository que vous appelerez "evaluation-inseec".
L'évaluation est individuelle et durera 1h30. Elle intègre des notions d'HTML, CSS, Ruby et computer science. 

![alt](https://media.giphy.com/media/26xBBfd0ii1khakpy/giphy.gif)

## Quelques mises en garde.

Je connais très bien ce merveilleux site qu'est Wikipédia. Je vous saurais gré de ne pas me remplir certaines questions avec les définitions de Wikipédia. Accessoirement, je sais aussi faire une recherche Google. Si j'ai un doute, je n'hésiterais pas rechercher "Qu'est-ce qu'une API" et comparer les définitions en tête de recherche avec les votre. Si je trouve une similarité trop grande et que je doute de votre bonne foi, je n'hésiterais pas à mettre 0 à la question. 
Pareil pour la copie sur les voisins. Si c'est trop gros et que j'ai un doute trop prononcé... 🔫

![alt](https://media.giphy.com/media/BtedgmzGNCiuk/giphy.gif)



------

### 1. Avec vos mots, expliquez l'interaction client-serveur

Client serveur est Ruby. Il permet de faire un process du text, créer un jeux (games) et aussi site Framework.



 ### 2. HTML est un langage côté... 	

```
Client
```



### 3. Donnez-moi la structure de base d'une feuille HTML

```html
<!DOCTYPE html>
<!-- Completez après cette ligne --> 
<html>
    <head>
        <body>
            
        </body>
    </head>
</html>
```



### 4. Changez la couleur du texte "J'adore la programmation" en vert en utilisant du CSS.

```html
<div>
   <p>J'adore la programmation</p>
</div>
```

```css
p { color: green;
}

```



### 5. Qu'est-ce que Bootstrap ?

```
C'est un site / une plateforme qui permet d'acceder pleins de code afin de developper un langgage HTML, CSS, et JavaScript.
```



### 6. Reprenez votre code de la question 3 et ajoutez Bootstrap à votre feuille HTML, au bon endroit.

```html

<!DOCTYPE html>
<html>
    <head>
        <body>
            
        </body>
    </head>
</html>
```



### 7. Mettez ces trois divs sur le même plan horizontal avec trois colonnes de même taille.

```html
<div class= container>
    <div class = "row">
        
</div>
	Google
<div>
    Microsoft
</div>

<div>
    Apple
</div>

</div>
</div>

```



### 8. Avec le même code, changez le texte par le logo de la marque en question

```html
<div>
    <img src=" google.png" alt="google logo"  />
</div>

<div>
	 <img src=" mslogo.jpg" alt="Microsoft logo"  />
</div>

<div>
     <img src=" applelogo.png" alt="apple logo"  />
</div>
```

 

### 9. Toujours sur le même bout de code, rendez les logos cliquables. Quand on clique sur le logo, on doit arriver sur le site officiel de la marque.

```html
<div>
    Google <a href=‘http://google.com’>
	<img src=‘https://www.google.com/url?sa=i&rct=j&q=&esrc=s&source=images&cd=&cad=rja&uact=8&ved=2ahUKEwiRlI-ThdTfAhVBXhoKHQIIBgcQjRx6BAgBEAU&url=https%3A%2F%2Ftechspective.net%2F2018%2F03%2F14%2F5-ways-the-google-logo-has-changed-over-its-20-year-history%2F&psig=AOvVaw0CF2uPLvYp09Tx5qdEA0gm&ust=1546688320875798’ alt=‘google logo’ />
</a>
</div>

<div>
    Microsoft <a href=‘http://microsoft.com’>
	<img src="https://www.google.com/url?sa=i&rct=j&q=&esrc=s&source=images&cd=&cad=rja&uact=8&ved=2ahUKEwjp85vwhNTfAhUNuRoKHaWABIEQjRx6BAgBEAU&url=https%3A%2F%2Fwww.theverge.com%2F2012%2F8%2F23%2F3262517%2Fmicrosoft-new-logo&psig=AOvVaw305YnwhDrNc4dmZmtdEl9L&ust=1546688236300917" alt=‘microsoft logo’ />
</a>
</div>

<div>
    Apple <a href=‘http://apple.com’>
	<img src=‘https://www.google.com/url?sa=i&rct=j&q=&esrc=s&source=images&cd=&ved=2ahUKEwjHzu-uhdTfAhVNOhoKHY0fBQsQjRx6BAgBEAU&url=https%3A%2F%2Fwww.freepik.com%2Ffree-icon%2Fapple-logo_748451.htm&psig=AOvVaw3y8m8zW7GP7j7iN_lsknHI&ust=1546688357761693’ alt=‘apple logo’ />
</a>
</div>
```

![Mon gars sûr !](https://media.giphy.com/media/l0K4mbH4lKBhAPFU4/giphy.gif)

### 10. Parlons Ruby. Ruby est un langage côté...

```
serveur
```



### 11. Listez-moi tous les types de données que vous connaissez en donnant le nom et la syntaxe.

```
1. array:chaine de caractère ex: array=[“string”
2. my_boolean = true,false
3. my_string = "Ruby" #Finally learn Rubby
4. float : décimaux
5. integer : chiffre entier negatif et positif
6. hash = (clés et valeurs)



```



### 12. Assignez à des variables votre prénom, nom et le lien de votre compte Github puis affichez chacune des variables. En 6 lignes.

```ruby
prenom = "Yulia"
nom = "Purnamasari"
Github = "https://github.com/Yuliapurnamasari""
puts prenom
puts nom
puts Github

```



### 13. Assignez 674 et 311 à des variables `a` et `b` et stockez le résultat `a` modulo `b` dans une variable `c` et affichez la. 

```ruby
a = 674
b = 311 
c = a % b
puts c
# Le résultat attendu est 52. 
```



### 14. Qu'est-ce qu'une gem ? 

```texte
C'est un type de code qui associé à Ruby. Il permet des fonctios particulieres comme l'authentification automatique
```



### 15. Qu'est-ce qu'une API et qu'est-ce qui nous permet de nous y connecter ?

```
Application Programming Interface est une application qui sert à l'ensemble de fonctionnalités organisé et structuré qui peut être mis à disposition d’autres programmes
```



### 16. On va créer un script pour dire bonjour ou bonsoir, en fonction de l'heure de la journée. Votre script doit demander à l'utilisateur de rentrer son prénom. Si `hour` est inférieur à 12, lui dire `Bonjour Anthony` sinon `Bonsoir Anthony` (évidemment, le prénom doit être celui renseigné par l'utilisateur).

```Ruby
# <- Demander le prénom de l'utilisateur

hour = 15

# Si hour est inférieur à 12
	# j'écris mon code permettant de dire Bonjour prénom

# sinon
	# j'écris mon code permettant de dire Bonsoir prénom


# <- Demander le prénom de l'utilisateur
prenom = "Anthony"
hour = 15

# Si hour est inférieur à 12
	# j'écris mon code permettant de dire Bonjour prénom
if hour == 12
puts "Bonjour #{prenom}"
# sinon
else 
puts "bonsoir #{prenom}"
    
	# j'écris mon code permettant de dire Bonsoir prénom
end


```



### 17. Itérer sur l'array contenant des noms de twitos un peu famous et follow chacun d'eux grâce à une méthode trouvée dans la [doc de la gem twitter](https://github.com/sferik/twitter). Pas besoin de lancer le code et de faire la partie authentification. Juste le bloc d'itération suffira. 

```ruby
client.follow("@richardbranson", "@jeffweiner", "@LinkedInQueen", "@ericschmidt", "@elonmusk", "@petecashmore", "@SteveForbesCEO", "@mtbarra")
```



### 18. Félicitations, vous êtes arrivé·e à la fin, pushez cette feuille sur votre Github dans un repo appelé `evaluation-inseec`. N'oubliez pas de remplir le premier block avec votre identité tout en haut ! 

![alt](https://media.giphy.com/media/l0MYJnJQ4EiYLxvQ4/giphy.gif)

