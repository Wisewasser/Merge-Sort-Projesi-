# Merge-Sort-Projesi

www.patika.dev

#Proje 2

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

# Aşamalar

1. Problem küçük parçalara bölünür.
2. Daha küçük parçalara bölünen problemler çözülür.
3. Çözülmüş küçük parçalar tekrar birleştirilir.

[16,21,11,8,12,22]

[16,21,11]-- [8,12,22]

[16] [21,11]-- [8] [12,22]

[16], [21], [11]-- [8], [12], [22]

[16], [11,21]-- [8], [12,22]

[11,16,21] -- [8,12,22]

[8,11,12,16,21,22]

# Big-O Gösterimi
 
Her adımda n işlem yapıldığı için O(nlogn)
