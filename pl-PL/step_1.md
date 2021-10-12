**Rozmowa z opóźnieniem czasowym**: [Sprawdź](https://scratch.mit.edu/projects/499336065/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499336065/?autostart=false" frameborder="0"></iframe>
</div>

Możesz uruchomić skrypt kilka sekund po kliknięciu zielonej flagi:

```blocks3
when [timer v] > [5] // change the delay
```

Jest to przydatne do koordynowania rozmów lub animacji z wieloma duszkami oraz do organizowania długich skryptów.

Kiedy używasz licznika, dobrze jest go `zresetować`{:class="block3sensing"} `kiedy zielona flaga zostanie kliknięta`{:class="block3events"}, ponieważ licznik uruchamia się po otwarciu projektu:

```blocks3
when flag clicked
reset timer
```

Innym sposobem dodania opóźnienia jest użycie `czekaj`{:class="block3control"}:

```blocks3
when flag clicked
wait [5] seconds // change the delay
```
