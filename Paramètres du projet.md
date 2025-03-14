
# **Afficher du Pixel Art en grand écran avec Godot**

Prenons un exemple concret :

Tu disposes d’un tileset constitué de sprites de **16×16 pixels** chacun. Tu souhaites afficher une grille composée de **20 sprites en largeur et 20 sprites en hauteur**, ce qui correspond à une fenêtre interne de **320×320 pixels**. Cependant, tu aimerais afficher cette scène pixelisée dans une fenêtre plus grande à l’écran.

Voici comment procéder :

**1. Régler la taille initiale de l’affichage**

• Ouvre le menu : **Projet → Paramètres du projet**.

• Dans la section **« Affichage » (ou « Display » en anglais)**, définis :

• **Largeur de la fenêtre d’affichage** : 320

• **Hauteur de la fenêtre d’affichage** : 320

À cette étape, la fenêtre est petite. Pour agrandir l’affichage et préserver l’effet pixel-art, il faut maintenant activer les options avancées.

**2. Activer les options avancées pour agrandir la fenêtre**

• Toujours dans la fenêtre des paramètres, coche l’option **« Options avancées »** en haut à droite.

• De nouvelles options apparaissent, notamment :

• **Redéfinir la largeur de la fenêtre**

• **Redéfinir la hauteur de la fenêtre**

• **Largeur**

• **Hauteur**

Règle ces paramètres à la taille que tu souhaites pour ta fenêtre finale, par exemple :

• Largeur : 1280

• Hauteur : 1280

**3. Paramétrer l’étirement pour préserver l’aspect pixelisé**

Toujours dans les paramètres avancés, dans la partie **« Étirement » (ou « Stretch » en anglais)**, règle les options suivantes :

• **Mode** : Canvas_item

• **Aspect** : Keep_height

Ces réglages permettent d’agrandir l’image tout en préservant l’aspect pixel-art sans distorsion.

**Optionnel : Bloquer le redimensionnement manuel**

Si tu veux empêcher l’utilisateur de redimensionner librement la fenêtre :

• Décoche simplement la case **« Redimensionnable »** dans les paramètres d’affichage.

Tu as désormais une grande fenêtre tout en conservant l’aspect pixel-art original de tes sprites !

Enfin, selon sa préférence on peut aussi empêcher le redimessionnement de la fenêtre en décochant ‘“Redimensionnable”