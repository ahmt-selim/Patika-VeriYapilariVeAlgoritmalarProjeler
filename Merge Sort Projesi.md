# VERİ YAPILARI VE ALGORİTMALAR

## PROJE 2 : Merge Sort Projesi

- [16,21,11,8,12,22] -> Merge Sort

    Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

    Merge Sort, bir sıralama algoritmasıdır ve "böl ve yönet" stratejisine dayanır. Diziyi sıralamak için önce diziyi ortadan ikiye böler, ardından her iki parçayı sıralar ve son olarak iki sıralı parçayı birleştirir. İşte verilen dizinin Merge Sort adımları:

Dizi: [16, 21, 11, 8, 12, 22]

    1.Adım: [16, 21, 11] ve [8, 12, 22] olarak iki parçaya böl.
        Sol: [16, 21, 11]
        Sağ: [8, 12, 22]

    2.Adım: Her iki parçayı da aynı mantıkla ikiye böl ve sırala.

    Sol (1. Parça): [16] ve [21, 11] -> [16] ve [11, 21]
    Sağ (2. Parça): [8] ve [12, 22] -> [8] ve [12, 22]

    3.Adım: İki sıralı parçayı birleştir.
        Sol: Birleştir ([16], [11, 21]) -> [11, 16, 21]
        Sağ: Birleştir ([8], [12, 22]) -> [8, 12, 22]

    4.Adım: Son olarak, iki sıralı parçayı birleştir.
        Birleştir ([11, 16, 21], [8, 12, 22]) -> [8, 11, 12, 16, 21, 22]

Dizi sıralandı: [8, 11, 12, 16, 21, 22]

Merge Sort'un zaman karmaşıklığı O(n log n)'dir, bu da algoritmanın veriyi hızlı bir şekilde sıralayabilme yeteneğini yansıtır.

[16,21,11,8,12,22]
- Yukarıdaki dizinin Big-O gösterimini yazınız.

Merge Sort'un zaman karmaşıklığı O(n log n)'dir. Bu, dizideki eleman sayısının (n) logaritmik büyüklükte bir oranda arttığı anlamına gelir. Merge Sort, böl ve yönet stratejisi sayesinde genellikle büyük veri setlerinde daha etkili ve tutarlı performans sergiler.
