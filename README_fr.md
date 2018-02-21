# Markdown Tutorial 
![](http://i.imgur.com/IMTN5cy.png)  

Bonjour, bienvenue dans mon tutoriel sur le Markdown. 
Dans ce tutoriel, vous apprendrez les bases du Markdown.  
La version espagnole est disponible [ici](https://github.com/LewisVo/Markdown-Tutorial/blob/master/Translation:Spanish.md).
La version portugaise est disponible  [ici](https://github.com/LewisVo/Markdown-Tutorial/blob/master/README_pt-BR.md).

*******
Table des matières  
 1. [Qu'est-ce que le Markdown ?](#whatismarkdown)
 2. [Pourquoi utiliser le Markdown?](#why)
 3. [Outils pour le Markdown](#tools)
 4. [La syntaxe du Markdown](#syntax)

*******

<div id='whatismarkdown'/>  

## Qu'est-ce que le Markdown ?  
Selon Wikipedia :  

  >*Le Markdown est un langage de balisage léger avec une syntaxe de formatage de texte brut conçu pour être converti en HTML ainsi qu'en d'autres format en utilisant un outil du même nom. Le Markdown est souvent utilisé pour rédiger des fichiers readme, pour écrire des messages dans des forums de discussion en ligne et pour créer des textes riches en utilisant un éditeur de texte brut.*   


`TOUT SIMPLEMENT : C'EST JUSTE UN AUTRE TYPE DE FICHIER TEXTE, COMME .txt .doc ....( ICI C'EST .md :laughing:) ET IL POSSÈDE UNE SYNTAXE SPÉCIALE.`  
<div id='why'/>  

*Il n'y a pas de standard Markdown clairement défini. Cela a conduit à une fragmentation étant donné que les différents fournisseurs écrivent leurs propres variantes du langage pour corriger les défauts ou ajouter des fonctionnalités manquantes... Une liste des versions de Markdown est disponible [ici](https://github.com/jgm/CommonMark/wiki/Markdown-Flavors).*

Pour l'instant, ce guide se concentre principalement la version Markdown de GitHub.

## Pourquoi utiliser le Markdown ?
Parce que c'est :
 * **FACILE** : La syntaxe est tellement simple que vous pouvez apprendre en une minute ou deux, puis écrire sans trouver quoi que ce soit bizarre ou geek.
 * **RAPIDE** : Cela fait gagner du temps comparé aux autres types de fichiers/formats texte. Cela aide à accélérer la productivité et le flux de travail du rédacteur.
 * **PROPRE** : La syntaxe et le rendu sont tous deux clairs, ne font pas mal aux yeux et sont simples à gérer.
 * **FLEXIBLE** : Avec un peu de configuration, votre texte sera traduit sur toutes les plateformes, sera modifiable dans tout logiciel d'édition et convertible dans un large choix de formats.
<br></br>
**En bref**, les utilisateurs réguliers le trouveront utile dans tous les cas, en particulier quand vous avez besoin de quelque chose de mieux que du texte brut mais de moins fonctionnel que Microsoft Word.  
**Pour les développeurs**, si vous êtes trop paresseux pour écrire du code HTML, vous adorerez le Markdown. **De plus**, **Github** et beaucoup d'autres sites privilégient le Markdown pour le fichier readme des projets. Cela signifie que vous allez rencontrer le Markdown d'une façon ou d'une autre.  
<div id='tools'/>  

## Outils pour le Markdown
Comme mentionné ci-dessus, tous les éditeurs peuvent être utilisés pour éditer du Markdown. Cependant, il existe quelques outils qui pourraient vous être utiles pour l'édition du Markdown.
 * **[*Stackedit*](https://stackedit.io)** : Ok, vous pouvez arrêter de lire tout de suite. Cliquez sur le lien et commencez votre visite du markdown de la plus simple des manières. Tapez juste du texte normal et utilisez votre souris, clic clic, c'est fait. Vous n'avez pas besoin de connaître la syntaxe. C'est bien, mais vous en serez dépendant et la plupart des développeurs préfèrent les claviers.
 * **[*Dillinger*](http://dillinger.io/)** : Outil en ligne, supporte le *live view* (écran partagé) et l'export au format html. Rien de très spécial mais très soigné et pratique.
 * **[*Typora*](https://www.typora.io/)** : Disponible pour Mac et Windows, minimaliste, sans aucune distraction, *live view* parfait, comprend d'autres choses comme les Images, Listes, Tableaux, Blocs de Code, Blocs de Mathématiques, YAML, Front Matters, Toc, ...
 * **[*Atom*](https://atom.io/)** : Éditeur de texte populaire (vous l'utilisez peut-être). Ouais, il est polyvalent. Supporte le Markdown ? Ça n'en est qu'une partie et c'est très bien construit.
 * **[*Minimalist Markdown*](https://chrome.google.com/webstore/detail/minimalist-markdown-edito/pghodfjepegmciihfhdipmimghiakcjf?hl=en)** : App Google Chrome. Fonctionne partout si Chrome est installé (c'est mon préféré).
 * **[*Macdown*](http://macdown.uranusjr.com/)** : le meilleur pour Mac.
 * **[*MarkdownPad*](http://markdownpad.com/)** : le meilleur pour Windows.
 * **[*Remarkable*](https://remarkableapp.github.io/)** : le meilleur pour Linux. 
 * **[*GITBOOK*](http://www.gitbook.com/)** : GitBook est un outil de publication moderne qui simplifie la rédaction et la collaboration. Il supporte le Markdown et entretient une relation proche avec notre bien-aimé Github.
<div id='syntax'/>  

## La syntaxe du Markdown 
Toute la syntaxe peut être trouvée [ici](https://daringfireball.net/projects/markdown/syntax) . Il faudrait beaucoup d'efforts pour retranscrire la syntaxe en texte (ils seraient formatés). Jetez donc un oeil au tableau ci-dessous pour toute la syntaxe de base.  

| Format        | Syntaxe      | Exemple |
| ------|-----|-----|
| Italique  	| \*Texte\* 	| *C'est en italique* 	|
| Gras 	| \*\*Gras\*\* 	| **C'est en bold** 	|
| Lien 	| \[Description\](url ici) 	| A [link](http://www.github.com) 	|
| Images 	| \![Caption\](url to img) 	| An image ![image](http://i.imgur.com/hRLuez2.png) 	|
| Lien + images 	| \[\![Caption\](url to img)\](url to a page)\] 	| Click me [![me](http://i.imgur.com/hRLuez2.png)](https://www.youtube.com) 	|
| Notes de bas de page  	| J'ai plus de choses \[^1\] à dire.   \[^1\]: Dites-le ici. 	| <a href="#section1">Hey, lisez la note sous ce tableau s'il vous plaît.  	|
| Sauts de ligne 	| Double espace + entrée 	|  	|
| Listes non-ordonnées 	| \* Item1     \*Item 2 	| <ul><li>item1</li><li>item2</li><li>item3</li><li>item4</li></ul> 	|
| Listes ordonnées 	| 1. Item a    2. Item b 	| <ol><li>itema</li><li>itemb</li><li>itemc</li><li>itemd</li></ol>  	|
| Listes mélangées 	| 1. Item 1      * item 1a 	|  <ol><li>itema</li></ol><ul><li> item1</li></ul>	|
| Citations 	| \> Texte cité 	|  <blockquote>Stay Hungry Stay Foolish</blockquote> 	|
| Préformatté 	| Commencez chaque ligne avec,deux espaces ou plus pour,faire que le texte soit,e x a c t e m e n t,comme,vous, le, tapez. 	|   Commencez chaque ligne avec,deux espaces ou plus pour,faire que le texte soit,e x a c t e m e n t,comme,vous, le,tapez. 	|
| Code 	| \`Insérez du code\` 	| `cout<<"Hello world";` 	|
| Bloc de code/ Mise en évidence de la syntaxe 	| \`\`\`insérez du code\`\`\` 	|  <a href="#section1">Hey, lisez la note sous ce tableau s'il vous plaît. 	|
| Titres 	| \#, \##, \###, \####, \#####, \###### (de h1 à h6) 	|  <h3>C'est un titre h3</h3>	|
| Barré 	| \~~Insérez du texte ici\~~ 	| ~~Je suis mort~~ 	|
| Tableau 	| \| Tables   \|      Are      \|  Cool \| \|\----------\|\:\-------------\:\|------\:\| \| col 1 is\|  left-aligned \| $1600 \| | ![](http://i.imgur.com/EItt7mh.png) |

<br></br>
 <br></br>
 <p id="section1">Note : Les **notes de pied de page** ne s'affichent pas correctement dans les tableaux (et la prévisualisation GitHub), mais cela ressemble à quelque chose comme ceci :     ![](http://i.imgur.com/pmeBr28.png)
   <br></br>
   C'est la même chose pour les **blocs de code/mise en évidence de la syntaxe**. Cela ressemble à ce que l'on voit sur cette image :
   ![](http://i.imgur.com/z8KrxAz.png).</p>

Ces caractéristiques dépendent de la version Markdown.

## Notes utiles  :
 * Le Markdown vous permet d'utiliser des échappements antislash pour générer des caractères littéraux qui
  sinon auraient un sens particulier avec la syntaxe de formatage Markdown. Un des caractères antislash d'échappement est : \     
 `Donc ? \*Ce\* n'est plus en italique mais c'este entouré par des astérisques littéraux.`

 * Les vidéos Youtube nécessitent un peu plus de travail. 
  ```
  Elles ne peuvent pas être ajoutées directement mais vous pouvez ajouter une image avec un lien vers la vidéo comme ceci :
  <a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
  " target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
  alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
  ```
 * Markdown supporte les emojis : :laughing: :laughing: :kissing_heart: :innocent: :green_heart: (vous trouverez des emojis [ici](http://www.emoji-cheat-sheet.com/) )
 * Vous pouvez utiliser les balises \<br/> pour forcer un saut de ligne. 
 * Double espace puis Entrée si vous voulez faire une nouvelle ligne et qu'il y a un souci pour en faire.
 * Voir n'est pas aussi bien que pratiquer. Vous pouvez soit vous créer un fichier markdown pour pratiquer ou le faire en ligne [ici](http://www.markdowntutorial.com).
 *  Les notes de pied de page et mise en évidence de la syntaxe ne font pas partie du Markdown original et ne sont supportés que par certaines versions de Markdown (Information de [Sean Brody](https://goo.gl/ASZwEn))
 *  Toute URL (comme http://www.github.com/) sera automatiquement convertie en un lien cliquable.  
 *  Le support de tableau Markdown est conçu pour gérer la plupart des tableaux pour la majorité des gens ; cela n'englobe pas tous les tableaux pour tout le monde. Si vous avez besoin de tableaux complexes, vous devrez les créer à la main ou avec un outil spécifiquement conçu pour votre format de sortie.  
```J'ai eu tellement de mal à rendre possible le tableau ci-dessus```
 
###### Auteur : *Vo Tran Thanh Luong*. 
###### Traducteur : *Butel Jérôme*.
