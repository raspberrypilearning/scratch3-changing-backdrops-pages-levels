Du kan använda bakgrunder i ett Scratch-projekt för att skapa olika sidor eller nivåer.
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="" frameborder="0"></iframe>
</div>

Klicka på scenpanelen och sedan på fliken **Bakgrunder** för att se bakgrunderna till ditt projekt. Du kan dra i bakgrunderna för att ändra ordning på dem.

![Bakgrunderna i ordning i Bakgrundsfliken.](images/backdrops-in-order.png)

Det finns många sätt att flytta till `nästa bakgrund`{:class="block3looks"}. Välj en som fungerar för ditt projekt.

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
