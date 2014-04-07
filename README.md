# Turkish Deasciifier for Java

Turkish Deasciifier is a Java library which converts Turkish text written with ASCII-only sentences into proper Turkish text with Turkish-specific accented letters.

(Turkish deasciifier ile Türkçe karakterler (ş, ı, ö, ç, ğ, ü) kullanmadan yazılmış yazıları doğru Türkçe karakter karşılıkları ile düzeltebilirsiniz.)

For instance a Turkish sentence containing only ASCII characters like:

> Hadi bir masal uyduralim, icinde mutlu, doygun, telassiz durdugumuz.

will be converted to a sentence containing proper Turkish accented characters:

>Hadi bir masal uyduralım, içinde mutlu, doygun, telaşsız durduğumuz.



### Credits

It is adapted from Emre Sevinç's [Turkish Deasciifier](http://ileriseviye.org/blog/?p=327) for Python which was influenced by Deniz Yüret's [Emacs Turkish Mode](http://denizyuret.blogspot.com/2006/11/emacs-turkish-mode.html) implementation which was inspired by Gökhan Tür's [Turkish Text Deasciifier](http://www.hlst.sabanciuniv.edu/TL/deascii.html).

[Zemberek](http://code.google.com/p/zemberek/) library also offers such a functionality, however, this library is compact, faster (*almost 2000 times*) and easier to use when compared to Zemberek.

This project is developed in 2010 and is not actively maintained.

### Example usage

```java
Deasciifier d = new Deasciifier();
d.setAsciiString("Hadi bir masal uyduralim, icinde mutlu, doygun, telassiz durdugumuz.");
System.out.println(d.convertToTurkish());
```

That simple.


### Authors

* Maintainer: [Ahmet Alp Balkan](http://www.ahmetalpbalkan.com) `<ahmet at ahmetalpbalkan.com>`
_(feel free to contact for any questions or contributions)_