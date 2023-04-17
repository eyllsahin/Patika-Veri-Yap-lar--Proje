# Patika-Veri-Yap-lar--Proje
Patikada veri yapılarının bitirme projeleri
[16,21,11,8,12,22] -> Merge Sort

    Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
    Big-O gösterimini yazınız
    
    16,21,11   ve   8,12,22 olarak ikiye böler arrayi  n/2
    
    16,21   11       8,12    22  olarak ikiye bölünen grupları tekrar ikiye böler n/4
    
    16 21   11       8 12   22  olarak tekrar ikiye bölme işlemi yapar  n/8 sonra sıraama yapıp tekrar birleştirir.
    
    11   16,21       8,12   22 
    
    11,16,21         8,12,22
    
    8,11,12,16,21,22 olarak son birleştirmeyi yapar. 
    Big O Notationu O(n*logn) çünkü recursive bir fonksiyon merge fonksiyonu her seferinde kendini çağırıp ikiye bölecek. Her merge işlemi n kere olacak. 
