**Χρονική καθυστέρηση συνομιλίας**: [Δες μέσα](https://scratch.mit.edu/projects/499336065/editor){: target = "_ blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499336065/?autostart=false" frameborder="0"></iframe>
</div>

Μπορείς να κάνεις ένα σενάριο να εκτελείται αρκετά δευτερόλεπτα μετά το κλικ στην πράσινη σημαία:

```blocks3
when [timer v] > [5] // change the delay
```

Αυτό είναι χρήσιμο για τον συντονισμό συνομιλιών ή κινουμένων σχεδίων με πολλαπλά sprites και για την οργάνωση μεγάλων σεναρίων.

Όταν χρησιμοποιείς το χρονόμετρο, είναι μια καλή ιδέα να το`μηδενίσεις`{: class = «block3sensing»} `όταν πατηθεί η πράσινη σημαία`{: class = «block3events»}, καθώς το χρονόμετρο ξεκινά όταν ανοίγεις ένα έργο:

```blocks3
when flag clicked
reset timer
```

Ένας άλλος τρόπος για να προσθέσεις καθυστέρηση είναι να χρησιμοποιήσεις το `περίμενε`{: class = "block3control"}:

```blocks3
when flag clicked
wait [5] seconds // change the delay
```
