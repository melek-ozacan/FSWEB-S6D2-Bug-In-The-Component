# Gün Projesi: Gönderiler Component'inde Bug

Takım olarak çalışınca dikkatli olmak gerekiyor. Genelde projede yapabileceklerimiz belli izinlere bağlı oluyor. Ama bir şekilde takımında bir şeyler yanlış ayarlanmış. Ekibe yeni katılan bir stajyer bir yerde kodlarda hatalı bir değişiklik yapabilmiş. Bu yüzden de uygulama düzgün çalışmıyor.

Sorun gönderiler component'inde gibi duruyor.
Normalde, Gonderiler component'i gönderiler state'indeki array'i map'leyerek her item için Gonderi component'ini render ediyor.

Proplemi nasıl düzeltebilirsin?

- İpucu: .map() metoduna bakabilirsin
- İpucu: .map() yapınca oluşan element'e key atribute'u eklemeyi unutma. Uygulama hata vermez ama console'a hata basar.

## Önemli Notlar

- Proje dizinindeki `user.json` dosyasını bulun ve `user_id` alanını NextGen proje ekranında görünen kendi `user_id` değeriniz ile güncelleyin.
- Geliştirme sırasında testleri izlemek için `npm test` komutunu kullanın.
- Testleri çalıştırıp skoru NextGen'e kaydetmek için `npm run sendresults` komutunu kullanın.
