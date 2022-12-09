# NotlarUygulamasi
## Kullanılan Teknolojiler
1. Activityler arası gezinme ve veri transferi
2. Fab Button Kullanımı
3. Recyclerview ve Adapter kullanımı
4. CardView tasarımı
5. Toolbar Menu Tasarımı
6. Sqlite Veritabanı Üzerinde veri ekleme, veri silme ve veri düzenleme aşamaları

## Özet
Uygulamanın ana amacı kullanıcının derslerinin notlarının ortalamasını bulması ve butun ders notlarını tek bir uygulama üzerinde görmesi. Bu uygulama toplam da 3 adet 
Activitden oluşmaktadır. İlk activity olan MainActiviy üzerinde veriler recyclerview yapısı ile listelenmektedir ve fab button sayesınde kullanıcı yeni verileri uygulamaya
girebilir. İkinci activity olan NotKayitActivitye ulaşmak için kullanıcının fab buttona tıklayarak yeni veri kaydetmesi gerekmektedir. Acılan activity üzerinde bulunan 
plainTextler ile dersin adı derse ait ilk not derse ait ikinci not kullanıcının girdiği veriler sayesinde alınır ve kaydet buttonuna tıklandığı anda veriler veritabanına
kaydedilir sonrasında uygulama MainActivity sekmesine geri döner ve tabi ki yeni kayıt edilen veri reyclerView üzerinde görüntülenmeye başlanır. Üçüncü Activiy olan 
DetayActivitye geçmek için kullanıcının notlarının gözüktüğü cardView tasarım nesnesine dokunması gerekir. Bu activity üzerinde notlarının plainTextler üzerinde görünmesi
sağlanır bu yapı activityler arası nesne transferi sayesinde yapılmıştır. Notlarında ya da ders adında değişiklil yapmak isteyen kullanıcı customToolbar üzerinde bulunan 
düzenle menu buttonu ile verileri düzenleyebilir ya da silme menu buttonu ile butun dersNesnesini silebilir.
