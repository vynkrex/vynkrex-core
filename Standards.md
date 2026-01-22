# Vynkrex Geliştirme Standartları

Bu belge, Vynkrex çatısı altında geliştirilen tüm projelerde uygulanması gereken teknik standartları, geliştirme süreçlerini ve çalışma disiplinini tanımlar.
Amaç; anlaşılır, sürdürülebilir ve uzun vadede bakımı yapılabilir yazılım sistemleri üretmektir.
Bu standartlar, tüm projeler için bağlayıcıdır.

# 1. Genel İlkeler

Kod yalnızca çalışıyor olmak için yazılmaz.
Okunabilirlik, sürdürülebilirlik ve genişletilebilirlik önceliklidir.
Kısa vadeli çözümler yerine uzun vadeli mimari kararlar tercih edilir.
Teknik borç bilinçli alınır ve kayıt altına alınır.
Her proje, Vynkrex Manifestosu ile uyumlu olmak zorundadır.

# 2. Kodlama Standartları

Kod açık, anlaşılır ve tutarlı olmalıdır.
Değişken, fonksiyon ve sınıf isimleri anlamlı ve açıklayıcı seçilmelidir.
Gereksiz karmaşıklık, tekrar eden kod ve aşırı soyutlamalardan kaçınılır.
Projeye uygun mimari yapı (modülerlik, katmanlama vb.) korunmalıdır.
Kod, mümkün olduğunca kendi kendini açıklayacak şekilde yazılmalıdır.

# 3. Mimari ve Yapı

Mimari kararlar belgeye dayalı alınır.
Her modül belirli bir sorumluluğa sahip olmalıdır.
Modüller arası bağımlılıklar minimum seviyede tutulur.
Gerçek kullanım senaryoları tasarımın merkezinde yer alır.
Performans ve bakım maliyeti göz önünde bulundurulur.

# 4. Dal (Branch) ve Commit Kuralları

Dal Yapısı
main
Her zaman çalışır ve dağıtıma hazır olmalıdır.
feature/<özellik-adı>
Yeni özellik geliştirmeleri için kullanılır.
bugfix/<konu-adı>
Hata düzeltmeleri için kullanılır.
Commit Kuralları
Commit mesajları kısa, net ve açıklayıcı olmalıdır.
Tek commit = tek amaç prensibi uygulanır.
Örnek commit mesajı:
auth: kullanıcı oturum süresi hatası düzeltildi

# 5. Pull Request (PR) Kuralları

Her değişiklik PR üzerinden yapılmalıdır.
PR açıklaması yapılan değişiklikleri açıkça belirtmelidir.
Kod incelemesi zorunludur.
Otomatik testler başarısızsa PR birleştirilemez.
Standartlara uymayan kod reddedilir.

# 6. Test Standartları

Yeni özellik eklenirken mümkün olduğunca test yazılmalıdır.
Testler anlaşılır, tekrarlanabilir ve hızlı çalışmalıdır.
Kritik sistem bileşenleri için birim test zorunludur.
Test edilmeyen kod teknik borç olarak kabul edilir.

# 7. Dokümantasyon

Önemli mimari kararlar belgelenmelidir.
Proje README dosyası güncel tutulmalıdır.
Karmaşık sistemler için ek dokümantasyon sağlanmalıdır.
Dokümantasyon, koddan bağımsız düşünülmemelidir.

# 8. Proje Yönetimi

Her proje kendi deposunda geliştirilir.
Bu repository merkezi referans noktasıdır.
Projeler, Vynkrex standartlarıyla uyumlu olmak zorundadır.
Standartlara uymayan projeler Vynkrex kapsamı dışında kabul edilebilir.

9. Kalite ve Sürdürülebilirlik

Kod kalitesi teslimattan önce değerlendirilir.
Geçici çözümler kalıcı hale getirilmemelidir.
Uzun vadede bakımı mümkün olmayan sistemler kabul edilmez.
Yeni geliştiricilerin projeye hızlı adapte olabilmesi hedeflenir.

# Sonuç

Vynkrex standartları, yalnızca kurallar bütünü değildir.
Bu belge, Vynkrex projelerinin nasıl düşünüldüğünü, nasıl geliştirildiğini ve nasıl sürdürüldüğünü tanımlar.

Tüm projeler bu çerçeveye göre şekillendirilir.
