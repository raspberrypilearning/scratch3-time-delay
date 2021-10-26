**Temporisation de la conversation** : [Voir à l'intérieur](https://scratch.mit.edu/projects/499336065/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499336065/?autostart=false" frameborder="0"></iframe>
</div>

Tu peux exécuter un script plusieurs secondes après avoir cliqué sur le drapeau vert :

```blocks3
when [timer v] > [5] // changer le délai
```

Ceci est utile pour coordonner des conversations ou des animations avec plusieurs sprites et pour organiser de longs scripts.

Lorsque tu utilises le minuteur, c'est une bonne idée de le `réinitialiser`{:class="block3sensing"} `lorsque le drapeau vert est cliqué`{:class="block3events"}, car le minuteur démarre lorsqu'un projet est ouvert :

```blocks3
when flag clicked
reset timer
```

Une autre façon d'ajouter un délai consiste à utiliser un bloc `attendre`{:class="block3control"} :

```blocks3
when flag clicked
wait [5] seconds // changer le délai
```
