**Conversación con tiempo de retraso**: [Ver dentro](https://scratch.mit.edu/projects/591172317/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/591172317/?autostart=false" frameborder="0"></iframe>
</div>

Puedes hacer que un script se ejecute varios segundos después de hacer clic en la bandera verde:

```blocks3
when [timer v] > [5] // cambia el tiempo de retraso
```

Esto es útil para coordinar conversaciones o animaciones con múltiples objetos y para organizar scripts largos.

Cuando usas el cronómetro, es una buena idea usar `reiniciar cronómetro`{:class="block3sensing"} `al presionar bandera verde`{:class="block3events"}, ya que el temporizador comienza cuando se abre un proyecto:

```blocks3
when flag clicked
reset timer
```

Otra forma de agregar tiempo retraso es usando un bloque `esperar`{:class="block3control"}:

```blocks3
when flag clicked
wait [5] seconds // cambia el tiempo de retraso
```

