**In tijd vertraagd gesprek**: [Bekijk van binnen](https://scratch.mit.edu/projects/499336065/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499336065/?autostart=false" frameborder="0"></iframe>
</div>

Je kunt een script een aantal seconden nadat op de groene vlag is geklikt starten:

```blocks3
when [timer v] > [5] // change the delay
```

Dit is handig voor het afstemmen van gesprekken of animaties met meerdere sprites en voor het organiseren van lange scripts.

Wanneer je de klok gebruikt, is het een goed idee om deze`op 0 te zetten`{:class="block3sensing"} `wanneer op de groene vlag wordt gekikt`{:class="block3events"}, zodat de klok start wanneer een project wordt geopend:

```blocks3
when flag clicked
reset timer
```

Een andere manier om een vertraging toe te voegen is om een `wacht`{:class="block3control"} blok te gebruiken:

```blocks3
when flag clicked
wait [5] seconds // change the delay
```
