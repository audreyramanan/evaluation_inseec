# Évaluation individuelle

## Programmation - Coaching

```
Nom : RAMANANKANDRASANA
Prénom : Audrey
URL de votre compte Github : https://github.com/audreyramanan
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

```t
L'interaction client-serveur c'est le passage de l'information entre un client qui est un ordinateur et le serveur qui est Internet. Les informations sont contenu dans des grosses machines que l'on appelle serveur.
```



 ### 2. HTML est un langage côté... 

```
marquage
```



### 3. Donnez-moi la structure de base d'une feuille HTML

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>...</title>
    </head>
    <body>
        
    </body>
```



### 4. Changez la couleur du texte "J'adore la programmation" en rose en utilisant du CSS.

```html
<div class="rose">
   <p>J'adore la programmation</p>
</div>
```

```css
/* Ecrire le code CSS sous cette ligne */
.rose {
    color: #F8A0FE
}
```



### 5. Qu'est-ce que Bootstrap ?

```
Bootstrap est une plateforme de ressource de code pré-former. C'est à dire avec un certain style déjà.
```



### 6. Reprenez votre code de la question 3 et ajoutez Bootstrap à votre feuille HTML, au bon endroit.

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">

        <title>...</title>
    </head>
    <body>
         <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
        
    </body>
```



### 7. Mettez ces trois divs sur le même plan horizontal avec trois colonnes de même taille.

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">

        <title>...</title>
    </head>
    <body>
        <div class="row">
        <div class="container">
	<div class="col-sm-4">
<div>
    Google
</div>

<div>
    Microsoft
</div>

<div>
    Apple
</div>
     </div>  
</div>
 </div>
        
        
         <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
        
    </body>

```



### 8. Avec le même code, changez le texte par le logo de la marque en question

```html
<div class="container">
	<div class="col-sm-3">
<div>
    <img src="https://img.tuttoandroid.net/wp-content/uploads/2015/09/new-google-logo.jpg" >
</div>

<div>
    <img src="https://yt3.ggpht.com/-6DRE7a5AcB4/AAAAAAAAAAI/AAAAAAAAAAA/ZZi5jVqSnsA/s900-c-k-no-mo-rj-c0xffffff/photo.jpg">
</div>

<div>
    <img src="https://yt3.ggpht.com/-KdgJnz1HIdQ/AAAAAAAAAAI/AAAAAAAAAAA/4vVN7slJqj4/s900-c-k-no-mo-rj-c0xffffff/photo.jpg" >
</div>
     </div>  
</div>
```

 

### 9. Toujours sur le même bout de code, rendez les logos cliquables. Quand on clique sur le logo, on doit arriver sur le site officiel de la marque.

```html
<a href="https://www.google.com/">Google home page</a>

<div class="container">
	<div class="col-sm-3">
<div>
    <a href="https://www.google.fr/"><img src="https://img.tuttoandroid.net/wp-content/uploads/2015/09/new-google-logo.jpg" ></a>
</div>

<div>
    <a href="https://www.microsoft.com/fr-fr/"><img src="https://yt3.ggpht.com/-6DRE7a5AcB4/AAAAAAAAAAI/AAAAAAAAAAA/ZZi5jVqSnsA/s900-c-k-no-mo-rj-c0xffffff/photo.jpg"></a>
</div>

<div>
    <a href="https://www.apple.com/fr/"><img src="https://yt3.ggpht.com/-KdgJnz1HIdQ/AAAAAAAAAAI/AAAAAAAAAAA/4vVN7slJqj4/s900-c-k-no-mo-rj-c0xffffff/photo.jpg" >
</div> </a>
     </div>  
</div>
```

![Mon gars sûr !](https://media.giphy.com/media/l0K4mbH4lKBhAPFU4/giphy.gif)

### 10. Parlons Ruby. Ruby est un langage côté...

```
Objet
```



### 11. Listez-moi tous les types de données que vous connaissez.

```
Chaine de caractère
Boolein
Chiffre entier
```



### 12. Assignez à des variables votre prénom, nom et le lien de votre compte Github puis affichez chacune des variables. En 6 lignes.

```ruby
nom = "Ramanankandrasana"
prenom = "Audrey"
lien_github = "https://github.com/audreyramanan"

puts "#{nom} #{prenom} #{lien_github}"
```



### 13. Assignez 674 et 311 à des variables `a` et `b` et stockez le résultat `a` modulo `b` dans une variable `c` et affichez la. 

```ruby
a = 674
b = 311
c = {a}/{b}

puts "#{a}/#{b}=#{c}"
# Le résultat attendu est 52. 
```



### 14. Qu'est-ce qu'une gem ? 

```texte
Un gem est un package qui permet de crée des boots avec le format d'un site. Ex: gem twitter
```



### 15. Qu'est-ce qu'une API et qu'est-ce qui nous permet de nous y connecter ?

```
application for programs
```



### 14. On va créer un script pour dire bonjour ou bonsoir, en fonction de l'heure de la journée. Votre script doit demander à l'utilisateur de rentrer son prénom. Si `hour` est inférieur à 12, lui dire `Bonjour Anthony` sinon `Bonsoir Anthony` (évidemment, le prénom doit être celui renseigné par l'utilisateur).

```Ruby
# <- Demander le prénom de l'utilisateur

hour = 15
name = "Anthony"

# Si hour est inférieur à 12
	# j'écris mon code permettant de dire Bonjour prénom
if hour < 12
	puts "Bonjour #{name}"

# sinon
	# j'écris mon code permettant de dire Bonsoir prénom
else 
    puts "Bonsoir #{name}"

```



### 15. Itérer sur l'array contenant des noms de twitos un peu famous et follow chacun d'eux grâce à une méthode trouvée dans la [doc de la gem twitter](https://github.com/sferik/twitter). Pas besoin de lancer le code et de faire la partie authentification. Juste le bloc d'itération suffira. 

```ruby
handles = ["@richardbranson", "@jeffweiner", "@LinkedInQueen", "@ericschmidt", "@elonmusk", "@petecashmore", "@SteveForbesCEO", "@mtbarra"]

client.followers(handles) .take (1).collect do |followers| 
end

```



### 16. Félicitations, vous êtes arrivé·e à la fin, pushez cette feuille sur votre Github dans un repo appelé `evaluation-inseec`. N'oubliez pas de remplir le premier block avec votre identité tout en haut ! 

![alt](https://media.giphy.com/media/l0MYJnJQ4EiYLxvQ4/giphy.gif)

