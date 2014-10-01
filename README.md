###autocapitalize issue in iOS 8


- From Devie > Toggle Hardware keyboard off so you can use the virtual keyboard on the simu.

- Try to type more than two characters in the numeric box, then when you click the alpha textbox where autocapitalize = "words"

- it will not set Caps on. However, if you click another box, it will set the cap. See caps.png file.

- this start happening in iOS8, and I tried to turn off predictor in Settings but no luck :(

- Try to check this on iOS 7 simulator by setting different target. Also try to throw this file on simulator to test it on Safari. It works on the Safari app.

- Conclusion: After type more than two digits in numeric fields, the cap setting is not correct right after the numeric box.
