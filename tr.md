# Peki OpenAI → ChatGPT nasıl çalışır?

- ChatGPT algoritması rastgele gibi görünebilir, ancak gerçekte öyle değildir. Bu bir numaradır: her şey zaten belirlenmiştir. Bir örnek verelim: ChatGPT'ye sorun → `bana 0 ile 100 arasında bir sayı ver` → size 73 verecektir. Ardından `Tekrar` deyin → 42 cevabını verecektir. Sonra tekrarlayın: `Tekrar`, ve vakaların %96,04'ünde 88 cevabını verecektir. Peki neden ilk ikisi tahmin edilebilirken diğerleri daha az tahmin edilebilir?

## Peki gerçekten tahmin edilebilirler mi? Pek sayılmaz.

- Sorun şu ki, üçüncü sayı artık modelin dahili hafızasında değil; "harici" hafızada → veri kümesinde veya veritabanında (emin değilim). Açıklayayım: veritabanında arama yaptığında, mümkün olduğunca hızlı yanıt vermeye çalışır, çünkü bunun için tasarlanmıştır. Bu yüzden arar ve bulunan ilk sayı vakaların %96,04'ünde 88'dir. Dolayısıyla denerseniz, büyük ihtimalle çoğunlukla 88 elde edersiniz. Ancak bu nedenle ChatGPT'nin söyleyeceği veya yapacağı her şeyi tahmin edebilir miyiz? Evet... ama aynı zamanda hayır. Sorun şu ki, söyleyeceği her şeyi başarılı bir şekilde tahmin etmek istiyorsak, 2-3 hafta boyunca yüz binlerce hesapta test edilmiş devasa bir kesin istem (prompt) veritabanına ihtiyacımız var. Ve eğer başarılı olursak, ChatGPT her yerde aynı şekilde yanıt verirdi, çünkü bunun etkili olduğunu "öğrenirdi". Ve istediğimizi yaptığı için onu ne kadar ödüllendirirsek, o davranışı o kadar çok tekrarlayacaktır. Bir algoritma böyle çalışır.

## Bunu nasıl yapabiliriz?

Yukarıda açıklandığı gibi, ChatGPT sadece matematiksel bir algoritmadır. Bu nedenle, belirli istemleri kullanarak ne söyleyeceğini tahmin etmek istersek, tamamen aynı istemi 2-3 hafta boyunca yüz binlerce hesapta test etmemiz gerekir. Ve eğer bu işe yarasaydı, ChatGPT her yerde aynı şekilde tepki verirdi, çünkü bu davranışın etkili olduğunu görürdü.

## xql ve diğerleri tarafından yapılan çalışma

- En üstteki ilk kısım hariç, şimdilik tüm bunlar tamamen teoriktir. Hepsi bu :)
