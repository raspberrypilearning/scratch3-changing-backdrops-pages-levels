Je kunt achtergronden in een Scratch-project gebruiken om verschillende pagina's of niveaus te maken.
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="" frameborder="0"></iframe>
</div>

Klik op het Speelveld en vervolgens op het **Achtergronden** tabblad om de achtergronden voor jouw project te bekijken. Je kunt de achtergronden slepen om ze op een andere plek te zetten.

![De achtergronden op volgorde in het tabblad Achtergronden.](images/backdrops-in-order.png)

Er zijn veel manieren om naar de `volgende achtergrond`{:class="block3looks"} te gaan. Kies er een die bij jouw project past.

```blocks3
when [space v] key pressed
next backdrop
```

```blocks3
when stage clicked // click on the Stage
next backdrop
```

```blocks3
when this sprite clicked // click on a sprite
next backdrop
```

```blocks3
when backdrop switches to [page1 v]
wait [5] seconds
next backdrop
```
