**FiveM SQL Yedekleme Botu**

# FiveM sunucunuz için çalışan, zip sıkıştırmalı Discord SQL yedekleme botu. İyi kullanımlar ve iyi forumlar!

### 🛠️ Kurulum

```text
1. "config.js" dosyasını açıp bot tokenı, kanal ID ve veritabanı bilgilerinizi giriniz.

2. Terminal veya CMD açıp "npm i" yazarak modülleri kurunuz.

3. "baslat.bat" dosyasına çift tıklayarak veya terminale "node index.js" yazarak botu başlatınız.
```

### 🚀 Özellikler

* **Otomatik & Manuel Yedek:** Belirlediğiniz süre aralıklarında otomatik veya `.yedek` komutu ile manuel yedek alma.
* **Akıllı Zip Sıkıştırma:** Veritabanını ham `.sql` yerine otomatik `.zip` formatına sıkıştırarak dosya boyutunu küçültür.
* **Disk Dostu Temizleme:** `config.js` üzerinden belirlenen adet (`maxLocalBackups`) aşıldığında eski yedekleri klasörden otomatik siler.
* **Çoklu Sağlayıcı:** XAMPP, MariaDB ve AppServ konumlarını otomatik algılar.
* **Yetki Koruması:** Manuel yedek alma komutu yalnızca `Yönetici` yetkisine sahip yetkililere açıktır.
* 
