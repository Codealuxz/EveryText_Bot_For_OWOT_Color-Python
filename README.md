# EveryText-pour-OWOT
Un bot pour le site yourworldoftext.com. Ce bot utilise les websockets pour afficher votre art ASCII sur la carte.

---

## 1. Installation des paquets requis

Assurez-vous que Python est installé sur votre machine. Ensuite, installez les bibliothèques requises avec la commande suivante :

```
pip install websocket-client customtkinter
```

---

## 2. Lancement du bot

Une fois les étapes précédentes terminées, lancez le fichier Python contenant le bot avec la commande suivante :

```
python main.py
```

---

## 3. Configuration du bot

Vous devez configurer le bot dans l'interface :

- Pour l'art ASCII, sélectionnez un fichier texte :  
![image du fichier](https://raw.githubusercontent.com/Codealuxz/EveryText-for-YWOT/refs/heads/main/img/file_image.png)
  
- Pour les coordonnées, définissez-les ici :  
![image des coordonnées](https://raw.githubusercontent.com/Codealuxz/EveryText-for-YWOT/refs/heads/main/img/co_image.png)

- Pour utiliser les couleurs, cochez la case "Use Colors" et assurez-vous que votre fichier contient le formatage BBCode correct.

## Utilisation des couleurs

Le bot prend en charge les couleurs via les balises BBCode. Format :

```
[color=#HEX]texte[/color]
```

Où HEX est le code couleur hexadécimal (ex: FF0000 pour rouge).

Exemple de texte avec couleurs :
```
[color=#FF0000]Texte en rouge[/color]
[color=#00FF00]Texte en vert[/color]
[color=#0000FF]Texte en bleu[/color]
```

#### Vous pouvez utilisé mon site pour convertire une image en ascii art color [everytextcolor.netlify.app](https://everytextcolor.netlify.app/)

Amusez-vous à créer et partager votre art ASCII coloré !

