# VERİ YAPILARI VE ALGORİTMALAR

## PROJE 1 : Selection Sort Projesi

[22,27,16,2,18,6] -> Insertion Sort

* Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Insertion sort, bir diziyi sıralamak için kullanılan bir sıralama algoritmasıdır. Her adımda, dizinin bir elemanı seçilir ve dizinin önceki elemanlarıyla karşılaştırılarak uygun konuma yerleştirilir. 
İşte verilen dizinin adım adım sıralanması:

    1.Adım: [22, 27, 16, 2, 18, 6]

    2.Adım: [22, 27, 16, 2, 18, 6]

    3.Adım: [16, 22, 27, 2, 18, 6]

    4.Adım: [2, 16, 22, 27, 18, 6]

    5.Adım: [2, 16, 18, 22, 27, 6]

    6.Adım: [2, 6, 16, 18, 22, 27]


[22,27,16,2,18,6]
* Yukarıda verilen dizinin Big-O gösterimini yazınız.

Insertion Sort algoritmasının Big-O gösterimi, en kötü durumda O(n^2)'dir. Bu durumda, her bir elemanın doğru konumuna yerleştirilmesi için diğer tüm elemanlarla karşılaştırma yapılması gerekmektedir. Bu, iç içe iki döngü kullanıldığı için O(n^2) zaman karmaşıklığına yol açar.

Ancak, en iyi durumda (dizi zaten sıralı) ve ortalama durumda Insertion Sort'un zaman karmaşıklığı O(n) olabilir. Bu durumda, döngüler içindeki karşılaştırmaların sayısı daha az olacaktır.

Ancak, genellikle Big-O gösterimi olarak en kötü durum karmaşıklığı ifade edilir. Dolayısıyla, Insertion Sort için Big-O gösterimi O(n^2)'dir.


* Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

    Average case: Aradığımız sayının ortada olması
    Worst case: Aradığımız sayının sonda olması
    Best case: Aradığımız sayının dizinin en başında olması.
    
18 sayısı sıraladığımız listede ortada olduğu için Average case kapsamına girer.

* [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

Selection Sort, her adımda dizinin minimum (veya maksimum) elemanını seçip onu sıralı kısmın başına yerleştiren bir sıralama algoritmasıdır. İlk dört adımı şu şekilde gerçekleşir:

Dizi: [7, 3, 5, 8, 2, 9, 4, 15, 6]

    1.Adım: [2, 3, 5, 8, 7, 9, 4, 15, 6]

    2.Adım: [2, 3, 5, 8, 7, 9, 4, 15, 6]

    3.Adım: [2, 3, 4, 8, 7, 9, 5, 15, 6]

    4.Adım: [2, 3, 4, 5, 7, 9, 8, 15, 6]

Bu adımlarda, her adımda seçilen minimum eleman sıralı kısma yerleştirilir. Bu işlem devam ederek dizinin tamamı sıralanana kadar devam eder.

