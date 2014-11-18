not-allowed
===========

Check if the text contains not allowed words

Just call to app.helpers.notAllowed.check('Example text') and if that text contains denied words it will return a true boolean.

```
  app.helpers.notAllowed.check('Eres un gilipollas') //true
  app.helpers.notAllowed.check('Eres una pütÂ') //true
  app.helpers.notAllowed.check('Eres mi amiga 946730012') //true (check function checks if there is a spanish telephone number or not allowed word)
  app.hepers.notAllowed.checkTelephones('puta') //false
  app.hepers.notAllowed.checkWords('puta') //true
  app.hepers.notAllowed.checkTelephones('688638123') //true
```

You can add or remove not allowed words from the notAllowed array in the file.
