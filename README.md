# PWA Android App
 Av. Ali BEYAZ'ın resmi Android uygulaması  
 Kendi web sayfanızı uygulamaya çevirip Google Play Store'a yükleyebilmeniz için örnek olarak paylaşılmıştır.  
 
 NASIL DERLENİR?  
 Android Studio'ya import etmeniz yeterlidir.  
 
 NOTLAR:  
 -Kendi uygulamanızı yaparken paket adı, uygulama adı, versiyon nuamralarını ve tabiki web site url'sini değiştirmeyi unutmayın.  
 -Aynı şekilde uygulama ikonları ve açılış ekranı imajlarını da değiştirmeyi unutmayın.  
 -Uygulamanın tam ekran olması için web sayfasının bulunduğu sunucuda "/.well-known/assetlinks.json" dosyası oluşturmanız gerekiyor. Google'da "assetlinks.json" diye arama yaparsanız örnek xml dosyalarına ulaşabilirsiniz. Güvenlik amacıyla ben paylaşmamayı tercih ediyorum.  
 -"assetlinks.json dosyası içerisindeki "package_name" ve "sha256_cert_fingerprints" parametrelerinin kendilerinizinkiyle değiştirmeniz gerekiyor.  
 -"sha256_cert_fingerprints" değerini Google Play Console'daki "Release Management>App signing>App signing certificate" yolu üzerinden kopyalayabilirsiniz.  
