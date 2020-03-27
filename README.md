# PSUnit-Extended
Extension of PSUnit to pretty it up, both with clean code and UX tweaks.

![Now with more pretty](https://i.imgur.com/Rs2NbTn.png)

This single class is an extension of ```TTS_UNITTEST:TestBase```. It adds a prettier UX, as shown above, and cleaner code:

```
method run
   /+ Extends/implements TTS_UNITTEST:TestBase.Run +/  
   %This.description = "Numeric example";
   %This.expectedResult = 2;
   %This.actualResult = 1 + 1;
   %This.test();
```
