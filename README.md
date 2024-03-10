HepsiPayCaseStudy- UI-API Otomasyonu
Bu projede Virgosol tarafından verilen task oluşturulmuş olup senaryoların Page Object Model kullanılarak koşulması sağlanmıştır.
Proje Özellikleri
Otomasyonun hazırlanışında Java, Maven, IntejijIDEA, Selenium, Cucumber, TestNG ve WebDriverElement gibi teknoloji, kütüphane ve araçlar kullanılmıştır.
Proje Java dilinde Selenium frameworku ile geliştirilmiştir . Mimaride POM kullanılmıştır.
Otomasyon Chrome ve Firefox browser'larında çalışacak şekilde hazırlanmıştır. Hangi browser ile çalışacağı configuration.properties den parametrik olarak değiştiriebilmektedir.
Webdriver ları projede eklenmiştir. Driver versiyon uyuşmazlığı durumunda aynı isim ile src/test/resources/ altında güncellenmelidir.
Test sırasında hata ile karşılaşıldığı zamanda ekran görüntüsü kaydetmektedir. Ayrıca Her Stepte Ekran Görüntüsü kaydetmesi için de isteğe göre kullanılabilecek Metot vardır. 
Annotasyonlar ve assertionlar için JUnit kütüphanesi kullanılmıştır.
Hooks dosyasında Before ve After metotları bulunmaktadır. 
CukesRunner dosyasında “tags” etiketi UI veya API olarak 2 seçenekli kurgulanmıştır. Hangisi seçilirse Feature-StepDefinitions dosyalarından UI ya da API otomasyonu tetiklenecektir.
