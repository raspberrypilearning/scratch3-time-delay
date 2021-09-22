**Conversa com intervalo de tempo**: [Veja um exemplo](https://scratch.mit.edu/projects/499336065/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499336065/?autostart=false" frameborder="0"></iframe>
</div>

Você pode fazer um script rodar alguns segundos depois que a bandeira verde for clicada:

```blocks3
when [timer v] > [5] // change the delay
```

Isso é útil para coordenar conversas ou animações com vários atores e para organizar scripts longos.

Ao usar intervalos, é uma boa ideia usar `zere o cronômetro`{:class="block3sensing"} `quando a bandeira verde for clicada`{:class="block3events"}, pois o cronômetro começa quando um projeto é aberto:

```blocks3
when flag clicked
reset timer
```

Outra maneira de adicionar um intervalo é usar um bloco `espere`{:class="block3control"}:

```blocks3
when flag clicked
wait [5] seconds // change the delay
```
