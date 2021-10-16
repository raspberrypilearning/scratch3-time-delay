**تأخير وقت المحادثة**: [انظر الداخل](https://scratch.mit.edu/projects/499336065/editor){: target = "_ blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499336065/?autostart=false" frameborder="0"></iframe>
</div>

يمكنك تشغيل البرنامج النصي بعد عدة ثوانٍ من النقر فوق العلم الأخضر:

```blocks3
when [timer v] > [5] // change the delay
```

هذا مفيد لتنسيق المحادثات أو الرسوم المتحركة لمجموعة متعددة من الكائنات ، ولتنظيم البرامج النصية الطويلة.

عند استخدام المؤقت، انها فكرة جيدة ل `إعادة`{:class="block3sensing"} `عندما ينقر العلم الأخضر`{:class="block3events"}، كما يبدأ المؤقت عند فتح المشروع:

```blocks3
when flag clicked
reset timer
```

هناك طريقة أخرى لإضافة مدة تأخير هو استخدام `الانتظار`{:class="block3control"}:

```blocks3
when flag clicked
wait [5] seconds // change the delay
```
