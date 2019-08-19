# Petit intro en markdown

Le markdown est un langage de balisage comme le HTML mais il est très léger par rapport au HTML.

Nous allons illuster quelques exemples pour ajouter du contenu dans le langage markdown. Il s'agira principalement des images (statiques et animées), des citations courtes et longues, des bouts de code, des formules chimiques, des tableaux, des liens&hellip;

Le langage markdown est beaucoup utilisé dans la plateforme Github.

## Des images

### Image statique

voici un exemple d'une image statique disponible en ligne (banque d'images aléatoires **placeimg**) en cliquant sur ce lien http://placeimg.com/300/300/animals/15.

![un chien](http://placeimg.com/300/300/animals/15)

### Image animée

Une deuxième image animée (gif, stockée dans mon repo.)

![un chat gris qui danse](images/chat-gris.gif)

## Citations 

> Un langage qui n'affecte pas votre manière de penser la programmation ne vaut pas la peine d'être connu.&ndash; **Alan Jay Perlis**

## Bout de code 

L'affichage d'un texte en PHP se fait via la commande *echo* comme ceci : `<php echo "Bonjour les becoders!"; ?>`.

Voici un autre exemple de bout de code en JavaScript :
```javascript
let name = "julio";   //déclaration d'une variable
alert("Hello "+name); //popup avec message

//fonction sayHello qui prend le nom 'name' en entrée
const sayHello = (name) => console.log(`Hello {name}`);
sayHello("Becode");   //affiche sur la console le msg
```
    
## Formules

* H<sub>2</sub>O : eau  (*p*H=7)
* CH<sub>3</sub>COOH<sup>&ndash;</sup> : ion acétate (*p*ka=4,8)

## Tableau

| Frontend   | Backend         |
|------------|-----------------|
| HTML5      | PHP             |
| CSS3       | Python (django) |
| JavaScript | Rubis on rails  |
| Ajax       | Java (JSP)      |
| Angular    | ASP             |
| React.js   | SQL, noSQL      |

Pour savoir un peu plus sur le langage markdown, vous pouvez consulter la vidéo [Markdown Crash Course](https://www.youtube.com/watch?v=HUBNt18RFbo).