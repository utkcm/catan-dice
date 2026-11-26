# Catan Dice

Catan oyunları için tarayıcıda çalışan zar atıcı. Tek bir HTML dosyası; kurulum gerekmez.

## Özellikler

- **Space** tuşuyla zar atma, son atışın büyük gösterimi ve son 40 atışın geçmişi
- Oyun boyunca 2–12 dağılımı (gelen ve olasılığa göre beklenen)
- Tahtadaki kaynakları sayılara girme; zar atılınca o sayının kaynakları ekranda belirir
- Oyun boyunca kaynak başına üretim sayısı
- Son atışı geri alma, yeni oyun

## Rastgelelik

Zarlar tarayıcının şifreleme amaçlı rastgele sayı üretecinden (`crypto.getRandomValues`) gelir. Ret örneklemesi (252–255 arası baytlar atılır) sayesinde her yüz tam 1/6 olasılıkla gelir. Zarların dönme animasyonu yalnızca görseldir; sonuç tuşa basıldığı anda belirlenir.

## Kullanım

`index.html` dosyasını bir tarayıcıda açın ya da GitHub Pages adresinden kullanın. Atışlar ve tahta, kullanılan tarayıcıda saklanır.
