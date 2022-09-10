# Patika.dev - Veri Yapıları ve Algoritmalar - Merge Sort Projesi
>[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

## Cevap
<pre>                                      7 (root)
                                      / \
                                   5      8
                                 /  \       \
                                1    6       9
                               / \
                             0    3  
                                 /  \       
                                2    4

</pre>

**Açıklama:** İşlemleri tek tek inceleyelim ve sıralama mantığını çözelim.
7 rakamı root olarak belirlenmiştir. Sırayı takip eden diğer rakamlar, 7'den küçük ise sola; 7'den büyük ise sağa yazılacaktır. Ağacın her bir alt satırında aynı mantık takip edilerek rakamlar sola veya sağa yerleştirilecektir.

* 5 rakamı 7'den küçüktür, sola yazılır.
* 8 ise 7'den büyüktür sağa yazılır.

* 1 rakamı 5'ten küçüktür sola yazılır, 6 rakamı 5'ten büyüktür sağa yazılır.
* 0 rakamı 1'den küçüktür sola yazılır, 3 rakamı 1'den büyüktür sağa yazılır.
* 2 rakamı 3'ten küçüktür sola yazılır, 4 rakamı 3'ten büyüktür sağa yazılır.






[PatikaDev profilim](https://app.patika.dev/fatihsakar)
[https://www.patika.dev]