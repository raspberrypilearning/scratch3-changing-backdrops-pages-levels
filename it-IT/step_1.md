Puoi utilizzare gli sfondi in un progetto Scratch per creare pagine o livelli diversi.
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="" frameborder="0"></iframe>
</div>

Fai clic sul pannello degli Stage e quindi sulla scheda **Sfondi** per visualizzare gli sfondi per il tuo progetto. Puoi trascinare gli sfondi per riordinarli.

![Gli sfondi in ordine nella scheda Sfondi.](images/backdrops-in-order.png)

Esistono molti modi per `passare allo sfondo seguente`{:class="block3looks"}. Scegline uno che vada bene per il tuo progetto.

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
