# Vynkrex Standards

Bu doküman, Vynkrex projelerinde uygulanacak teknik standartları ve geliştirme süreçlerini tanımlar. 
Amaç, projelerin anlaşılır, sürdürülebilir ve yüksek kalitede geliştirilmesini sağlamaktır.

## Kodlama Standartları

- Kod okunabilir ve yorumlanabilir olmalıdır.
- Fonksiyon ve değişken isimleri anlamlı ve tutarlı olmalıdır.
- Gereksiz karmaşıklık ve tekrar eden koddan kaçınılmalıdır.
- Kod, proje tipine uygun yapı ve mimariyi takip etmelidir.

## Branch ve Commit Prensipleri

- Ana branch: `main` (her zaman deploy edilebilir durumda olmalıdır)
- Feature branch’ler: `feature/<özellik-adı>`
- Bugfix branch’ler: `bugfix/<konu-adı>`
- Commit mesajları kısa ve açıklayıcı olmalıdır (örn. “Fix login error on mobile client”)
- Her commit küçük ve tek bir amaç için olmalıdır.

## Pull Request (PR) Kuralları

- Her PR, ilgili branch üzerinden açılmalıdır.
- PR açıklaması net, yapılacak değişiklikler detaylı olmalıdır.
- Kod review, en az bir başka geliştirici tarafından yapılmalıdır.
- Otomatik testler (CI) başarılı olmadan merge edilmemelidir.

## Testing

- Yeni kod eklerken mümkün olduğunca test eklenmelidir.
- Testler anlaşılır, tekrarlanabilir ve hızlı çalışmalıdır.
- Kritik modüller için unit test zorunludur.

## Workflow ve Süreçler

- Tüm projeler, merkezi doküman ve standartlara uygun geliştirilir.
- Kod review ve PR süreçleri opsiyonel değildir, zorunludur.
- Standartlara uymayan kod merge edilmemelidir.
