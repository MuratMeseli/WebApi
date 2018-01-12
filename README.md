Mechsoft .NET --   Toplantı Organizasyonu --  (Meeting Organizer)

Proje Adı : 

Meeting Organizer

Projenin Tanımı :

Müşteriler ile yapılacak toplantıların kaydedilebileceği, güncellenebileceği ve silinebileceği bit tek sayfa uygulaması.

Yapılanlar : 

-Toplantı Kayıt Formu

-Toplantı Güncelleme Formu

-Toplantı Listesi
-WEB API Backend 
Toplantı Kayıt Formu : 
Bu formda toplantıya ait bilgiler yer alır. 
- Toplantı Konusu
-Başlangıç Saati
-Bitiş Saati
-Katılımcılar
Toplantı Güncelleme Formu :
Kullanıcının bilgileri güncelleyebilecekleri form yapıldı.
Toplantı Listesi : 
Kullanıcıların kaydettiği bilgilerden oluşan kayıtların sayfada gösterilmesi.
Kullanılan Dil ve Teknolojiler : 
Bu programda .NET kullanıldı. Database ile CRUD işlemi gerçekleştirildi. Bu işlemde entity framework yardımı ile gerekli ekleme, güncelleme ve silme işlemleri için methodlar tanımlanıp bu methodların işleme koyulması için gerekli ( geri dönecek değerler, işleme koyulacak değerler vb.) işlemler gerçekleştirildi.
Bu programın client tarafında MVC kullanılarak formlar oluşturuldu , bu formlar database ve gerekli kodlarla bağlantıları yapıldı.
Programın server kısmında ise ASP.NET Web Api framework kullanıldı. Bu framework lerde arka planda çalışacak ve istenen işlemleri yapacak kodlar yerleştirildi.
Programın veritabanında MSSQL sunucusu kullanıldı.
Programın Kullanımı : 
Programda İndex dosyası açılır ve daha önce kayıt edilmiş olan veya yeni kayıtların listeleneceği alan karşımıza çıkar. Bu alanda bütün bilgiler kendi sütunlarında düzenli olarak gözükür. Bu sayfada üst bölümdeki Create New butonu yeni kayıt oluşturmaya yarar. Kayıtların Sağ tarafında gelen edit butonu kayıtları değiştirmeye yara ve o butona tıklanıldığında karşımıza kayıt formumuz gelir. Yine sağ tarafta bulunan delete butonu seçilen kaydı silme işlemine yarar. Yine sağ tarafta bulunan details butonu seçilen kayıtların içerisindeki bilgileri detaylı olarak görmeye yarar.
