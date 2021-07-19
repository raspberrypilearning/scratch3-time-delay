**Time delay conversation**: [See inside](https://scratch.mit.edu/projects/499336065/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499336065/?autostart=false" frameborder="0"></iframe>
</div>

You can make a script run a number of seconds after the green flag is clicked:

```blocks3
when [timer v] > [5] // change the delay
```

This is useful for coordinating conversations or animations with multiple sprites, and for organising long scripts.

When you use the timer, it is a good idea to `reset`{:class="block3sensing"} it `when green flag clicked`{:class="block3events"}, as the timer starts when a project is opened:

```blocks3
when flag clicked
reset timer
```

Another way to add a delay is to use a `wait`{:class="block3control"} block:

```blocks3
when flag clicked
wait [5] seconds // change the delay
```
