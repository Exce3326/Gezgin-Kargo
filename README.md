 Gezgin Kargo Problemi
 Giris: Gezgin Satc Problemimde amac, bir satcnn bulundugu sehirden baslayarak her
 sehre sadece bir kez ugradktan sonra basladg sehre donebilmesi icin en ksa yolun bulunmasıdır. 
 Bu problem polinom zamanda cozulmesi mumkun olmadgndan NP (non polynomial problem) sınıfına girmektedir. 
 Bu projedeki problem, Gezgin Satc Probleminden uyarlanarak aşağıda tanımlanmıştır.
 Bir nakliye rmasnn en az maliyetli tasma agn yapmas ve internet ag trafigi protokolu problemleri kullanm alanlarına ornek verilebilir.
 
 Amac: Projeyi yapan kisi icin veri yaplar ve veri modellerini anlamak, grafik yapsının kullanlması ve algoritma mantıgının
 kullanarak bir probleme cozum sağlayabilmesi amaçlanmaktadır.
 Problem: Merkezi Kocaelide kurulan yeni bir kargo rmas, siparislerini en ksa yoldan
 yerlerine ulastırmayı amaçlamaktadır. Bu amaç doğrultusunda size basvurmaktadr.

 Dil: C, C#, JAVA
 
1 Kurallar
 Tum sevkiyatlarn baslangc ve bitis noktas Kocaeli olmaldr.
 Tek bir seferde maksimum 10 sehire teslimat yaplabilmelidir.
 
 Senaryo: Adm 1- Teslimat adresleri kullanc tarafndan baslangcta Ankara, Kayseri
 ve Izmir olmak uzere 3 sehir belirlenmis olsun.
 Bir sehirden diger sehre giderken komsu sehirler uzerinden hareket edilmelidir.
 
 Senaryo: Adm 2- Ilk olarak Kocaeli den gidilebilir sehirler olusturacagnz komsuluk
 matrisine gore Yalova, Istanbul, Bursa veya Sakarya sehirlerinden biri olmaldr. Ayn
 sekilde bir sonraki admda da gidilen sehre gore o sehrin komsular uzerinden gecis
 yaplmaldr.
 
 Bir sehirden birden fazla kez gecilebilir.
 
 Senaryo: Adm 3- Kocaeli den komsuluklar kullan larak Eskisehirden gecerek Ankaraya
 gidebilir. Ankaradan da Izmire gitmek icin Eskisehirden 2. defa gecmesi mumkundur.
 Bulunan cozum o problem icin en ksa mesafeli yolu bulabilmelidir.
 
 Senaryo: Adm 4- Kocaeliden Ankara, Kayseri ve Izmir yolculugunda Artvin gibi cok
 uzak yerlerden gecmek yerine daha ksa mesafedeki yerlerden gitmesi daha optimum
 sonucu verecektir.
 Aramada bulunan alternatif en ksa yollar en az maliyetliden baslayacak sekilde sral
 olarak yazdrlmaldr.
 Bulunan en ksa 5 cozum gorsel bir harita uzerinde cizdirilmelidir (5 yol yoksa oldugu
 kadar). Bunlar arasndaki en iyi yol farkl renkle belirgin bir sekilde vurgulanmaldr.
 Komsuiller arasndaki mesafeleri URL:https://www.kgm.gov.tr/Sayfalar/KGM/SiteTr/
 Root/Uzakliklar.aspx) linkindeki iller arasmesafe cetvelindeki mesafelerle uyumlu
 olmaldr.
 URL:https://drive.google.com/file/d/1bsYfGHz3Wwe-mKfsoS97bEZvy5IB7mUz/view?
 usp=sharing linkinde plaka kodu, sehir ve gidilebilecek komsu listeleri bulunmaktadr.
 Bu dosyay kendi uygulamanza gore farkl formatlarda kullanabilirsiniz.
 Gezgin satc problemi temelde NP-hard bir problem oldugu icin klasik yontemlerle
 cozum ideal zamanda bulunamayabilir. Bu sebeple farkl sezgisel yaklasmlarn kullanlması gerekebilir.
 Projenin degerlendirilmesinde uygulamann makul surede (max 40 saniye) kabul edilebilir sonuclar bulabilmesi onemlidir.
 NOT: Proje tantmnda proje detaylı olarak anlatlacaktr. Proje sunumlarnda problem
 yasamamak adna sunuma katlm onemlidir. Anlaşılamayan noktalar mutlaka sorulmaldr.
 Projeyle ilgili surecin e-destek uzerinden takip edilmesi gerekmektedir



![Şehir Listesi](https://github.com/user-attachments/assets/fb8a0da5-96e2-40cc-878c-f11804f564a2)
![Komşuluk Matrisi](https://github.com/user-attachments/assets/4e81eceb-67a4-4bb0-8a8c-f8224a36c22a)
![Harita Gösterimi](https://github.com/user-attachments/assets/dbc7bdfe-c54b-4db4-8899-75144d64cd6e)
![Hata](https://github.com/user-attachments/assets/65341e27-7373-4d7b-9aaa-e8e35214f02c)
![9-Adım](https://github.com/user-attachments/assets/a588d467-69f3-4eb9-8d77-9b237b4ac02c)
![8-Adım](https://github.com/user-attachments/assets/21c4a0b9-f700-4583-893f-0903c053d9e1)
![7-Adım](https://github.com/user-attachments/assets/7d4d09ca-4f6f-4812-a0a2-f8b41b548936)
![7 2-Adım](https://github.com/user-attachments/assets/f7daec0e-711e-43b0-a865-28522ef2f551)
![7 1-Adım](https://github.com/user-attachments/assets/4722e884-b3ed-439e-9085-104aadcc2d2d)
![6-Adım](https://github.com/user-attachments/assets/9900e2c8-f693-43fe-987c-cfef19b3f5e2)
![5-Adım](https://github.com/user-attachments/assets/283503fa-13ae-404e-84c5-802cebc4e42d)
![3-Adım](https://github.com/user-attachments/assets/4c2d74b7-5b4c-4a12-a005-c1246b11ceac)![4-Adım](https://github.com/user-attachments/assets/1727db90-5cfc-44da-b637-ca5b17cda191)
![3-Adım.png yükleniyor ...]()
![1-Adım](https://github.com/user-attachments/assets/9dd90830-1459-413f-bae8-5f64e714c0ec)![2-Adım](https://github.com/user-attachments/assets/35042a36-524d-4ca7-b370-59095b1c2d70)
![1-Adım.png yükleniyor ...]()
