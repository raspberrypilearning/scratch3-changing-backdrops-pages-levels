Puoi utilizzare gli sfondi in un progetto Scratch per creare pagine o livelli diversi.

**Tutorial per la modifica degli sfondi**: [Guarda dentro](https://scratch.mit.edu/projects/947908157/editor){:target="_blank"}
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/947908157/?autostart=false" frameborder="0"></iframe>
</div>

Fai clic sul pannello degli Stage e quindi sulla scheda **Sfondi** per visualizzare gli sfondi per il tuo progetto. Puoi trascinare gli sfondi per riordinarli.

![Gli sfondi in ordine nella scheda Sfondi.](images/backdrops-in-order.png)

Esistono molti modi per `passare allo sfondo seguente`{:class="block3looks"}. Scegline uno che vada bene per il tuo progetto.

```blocks3
when [space v] key pressed
next backdrop
```

```blocks3
when stage clicked // Guarda dentro
next backdrop
```

```blocks3
when this sprite clicked // Fai clic su uno sprite
next backdrop
```

```blocks3
when backdrop switches to [pagina1 v]
wait [5] seconds
next backdrop
```
