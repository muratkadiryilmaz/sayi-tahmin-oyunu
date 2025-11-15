## Sayı Tahmin Oyunu (C Dili) ##

Bu proje, C dilinde 1 ile 1000 arasında rastgele seçilen bir sayıyı tahmin etmeye dayalı basit bir oyunudur.  
Kullanıcının toplam **10 tahmin hakkı** vardır.  
Her yanlış tahminde, doğru sayının daha büyük mü küçük mü olduğu belirtilir.

---

# Nasıl Çalışır
Program, `rand()` ve `time()` fonksiyonlarını kullanarak her çalıştırmada farklı bir sayı üretir.  
Kullanıcıdan her denemede tahmin girmesi istenir.  
Doğru tahmin yapılırsa oyun biter, aksi halde ipuçları verilir.

---

# Derleme ve Çalıştırma
Aşağıdaki komutları terminalde çalıştırarak oyunu derleyip başlatabilirsiniz:

```bash
gcc sayi_tahmin_oyunu.c -o sayi_tahmin_oyunu
./sayi_tahmin_oyunu
