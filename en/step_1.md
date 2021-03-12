**Time delay conversation**: [See inside](https://scratch.mit.edu/projects/499336065/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499336065/?autostart=false" frameborder="0"></iframe>
</div>

You can make a script run a number of seconds after the green flag is clicked.

```blocks3
when [timer v] > [5] // change the delay
```

This is useful for coordinating conversations or animations with multiple sprites and for organising long scripts.

When you use the timer, it's a good idea to reset it when the green flag is clicked as the timer might already be runninng when you start your project.

```blocks3
when flag clicked
reset timer
```
