**Sgwrs amser oedi**: [Gweld tu mewn](https://scratch.mit.edu/projects/499336065/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499336065/?autostart=false" frameborder="0"></iframe>
</div>

Galli di wneud i sgript redeg nifer o eiliadau ar ôl clicio'r faner werdd:

```blocks3
when [timer v] > [5] // newid yr amser oedi
```

Mae hyn yn ddefnyddiol ar gyfer cydlynu sgyrsiau neu animeiddiadau sydd â sawl corlun, ac ar gyfer trefnu sgriptiau hir.

Pan fyddi di'n defnyddio amserydd, mae'n syniad da ei `ailosod`{:class="block3sensing"} `pan fydd y faner werdd wedi'i chlicio`{:class="block3events"}, gan fod yr amserydd yn cychwyn pan gaiff prosiect ei agor:

```blocks3
when flag clicked
reset timer
```

Ffordd arall o ychwanegu amser oedi ydy defnyddio bloc `aros`{:class="block3control"} block:

```blocks3
when flag clicked
wait [5] seconds // newid yr amser oedi
```
