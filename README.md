# Merge-Sort-
patika.dev'in merge sort gösterimi

[16,21,11,8,12,22] Dizisinin Merge Sorta göre aşamalarını yazınız:

[16,21,11] + [8,12,22]
[16] + [21,11] + [8] + [12,22]
[16] + [11,21] + [8] + [12,22]
[11,16,21] + [8,12,22]
[8,11,12,16,21,22]

Big O Gösterimini yazınız:

Diziyi tek elemanlı olarak parçalayana kadar sürekli ikiye bölmektedir. Bölünmüş her dizide işlem için dizinin uzunluğu kadar olan n tane işlem yapıldığına göre 6 adet eleman bulunmaktadır. = O(n*(logn)) => O(6*(log6)) olacaktır.
