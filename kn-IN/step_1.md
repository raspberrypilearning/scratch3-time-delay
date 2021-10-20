**Time delay conversation**: [See inside](https://scratch.mit.edu/projects/499336065/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499336065/?autostart=false" frameborder="0"></iframe>
</div>

ಹಸಿರು ಧ್ವಜವನ್ನು ಕ್ಲಿಕ್ ಮಾಡಿದ ನೀವು ಕೆಲವು ಸೆಕೆಂಡುಗಳ ನಂತರ ಸ್ಕ್ರಿಪ್ಟ್ ಅನ್ನು ರನ್ ಮಾಡಬಹುದು:

```blocks3
when [timer v] > [5] // change the delay
```

ಸಂವಾದಗಳು ಅಥವಾ ಅನಿಮೇಷನ್‌ಗಳನ್ನು ಬಹು ಸ್ಪ್ರೈಟ್ ಗಳೊಂದಿಗೆ ಸಂಯೋಜಿಸಲು ಮತ್ತು ದೀರ್ಘ ಲಿಪಿಗಳನ್ನು ಸಂಘಟಿಸಲು ಇದು ಉಪಯುಕ್ತವಾಗಿದೆ.

ನೀವು ಟೈಮರ್ ಬಳಸಿದಾಗ, ಪ್ರಾಜೆಕ್ಟ್ ತೆರೆದಾಗ ಸಮಯ ಪ್ರಾರಂಭವಾದಾಗ, `when green flag clicked`{:class="block3events"} ಮಾಡಿದಾಗ `reset`{:class="block3sensing"} ಮಾಡುವುದು ಉತ್ತಮ ವಿಚಾರ:

```blocks3
when flag clicked
reset timer
```

ವಿಳಂಬವನ್ನು ಸೇರಿಸಲು ಇನ್ನೊಂದು ಮಾರ್ಗವೆಂದರೆ `wait`{:class="block3control"} block ಬ್ಲಾಕ್ ಅನ್ನು ಬಳಸುವುದು:

```blocks3
when flag clicked
wait [5] seconds // change the delay
```
