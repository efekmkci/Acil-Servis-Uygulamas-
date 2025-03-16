# Hastane Acil Servis Uygulamasi

## Proje Aciklamasi
Bu proje, bir hastane acil servisinde hasta kayitlarini yonetmek icin gelistirilmis basit bir C programidir. Hasta bilgileri kuyruk yapisi kullanilarak saklanir ve oncelik seviyesine gore siralanarak islem yapilir.

## Ozellikler
- Hasta ekleme (Ad, Yas, Hastalik Durumu, Oncelik Seviyesi, Recete No)
- Hasta listesini goruntuleme
- Oncelik sirasina gore hastayi isleme alma
- Hastalarin oncelik derecelerine gore siralanmasi

## Kurulum ve Calistirma
1. Dev-C++ veya herhangi bir C derleyicisini acin.
2. `hospital_emergency.c` dosyasini acin.
3. Programi derleyip calistirin.

## Kullanim
1. **Hasta Ekle:** Hasta bilgilerini girerek sisteme hasta ekleyebilirsiniz.
2. **Hastalari Listele:** Kayitli hastalari ve bilgilerini goruntuleyebilirsiniz.
3. **Hastayi Isle:** En yuksek oncelige sahip hastayi siradan cikartip islem yapabilirsiniz.
4. **Cikis:** Programdan cikis yapabilirsiniz.

## Geliştirici Notlari
- Hasta bilgileri dizi (queue) yapisinda saklanmaktadir.
- Oncelik siralamasi icin kucuk deger daha onceliklidir (1 en acil, 5 en dusuk).
- Recete numarasi rastgele olarak olusturulmaktadir.

## Yapilacaklar
- HL7 formatina uygun veri ciktisi eklenebilir.
- Dosyaya kayit islemi eklenebilir.

Bu proje, C dilinde temel veri yapilarini ve is mantigini uygulamak icin tasarlanmistir. Gelistirmeye aciktir. 🚀

