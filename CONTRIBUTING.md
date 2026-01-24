# Katkıda Bulunma 

Vynkrex Core deposu ve altındaki projelere katkıda bulunmak isteyenler için temel kurallar, yol haritası ve referans rehberidir. 
Amaç, katkının düzenli, anlaşılır ve sürdürülebilir olmasını sağlamak ve projeler arası uyumu korumaktır. 
Bu rehber, yalnızca dokümantasyon, standartlar ve proje yönlendirmeleri için geçerlidir; kod içermeyen Core deposu için hazırlanmıştır. 

# Başlamadan Önce 

- Core depo dokümantasyon ve standart deposudur. Kod veya proje içeriği içermez. 
- Katkılar, belgelerin geliştirilmesi, standartların uygulanması veya mevcut dokümanların iyileştirilmesi yönünde olmalıdır. 
- Katkı yapmadan önce Manifesto.md ve Standartlar.md dosyalarını okuyun ve anlayın. 
- Projeler hakkında fikir edinmek için PROJECTS.md dosyasına bakın; bu katkı yapacağınız alanı seçmenize yardımcı olur. 

# Pull Request (PR) Kuralları 

- Tüm değişiklikler PR üzerinden yapılmalıdır. 
- PR açıklaması değişiklikleri net bir şekilde anlatmalıdır; hangi dosyada ne değiştiği ve neden değiştiği mutlaka belirtilmelidir. 
- PR birleştirmeden önce kod/doküman incelemesi yapılmalı ve varsa otomatik kontroller tamamlanmalıdır. 
- PR’ler, ilgili feature veya bugfix branch üzerinden açılmalıdır; main branch doğrudan değiştirilmemelidir. 

# Branch Yapısı 

- main: Her zaman güncel ve dağıtıma hazır ana şube 
- feature/<özellik-adı>: Yeni doküman, standart veya referans eklemeleri için 
- bugfix/<konu-adı>: Hata düzeltmeleri veya yanlış bilgilerin düzeltilmesi için 

# Doküman ve Standart Katkıları 

- Belgeler açık, anlaşılır ve takip edilebilir olmalıdır. 
- Yazım ve format standartlarına dikkat edin; başlıklar, boşluklar ve madde işaretleri tutarlı olmalıdır. 
- Gereksiz tekrar ve karmaşıklıktan kaçının. 
- Mevcut standartlarla (Standartlar.md) ve felsefi çerçeveyle (Manifesto.md) uyumlu olun. 
- Gerekirse doküman içerisine referans ekleyin: “Bu değişiklik X standardına uygundur” veya “Bu madde Manifesto.md’nin Y bölümüne uygun şekilde güncellendi” gibi. 

# Test ve Kontrol 

- Tüm değişiklikler gözden geçirilmelidir. 
- Yeni eklenen içerik anlaşılır ve takip edilebilir olmalıdır. 
- Kritik veya karmaşık değişikliklerde, bir başka ekip üyesinin onayı alınmalıdır. 
- Her değişikliğin Vynkrex projelerine etkisi düşünülmeli; sürdürülebilirliğe katkısı olmalıdır. 

# Katkı Referansı ve Örnek 

- Yeni bir standart eklerken, Standartlar.md’de benzer örneklere bakın ve formatı aynen uygulayın. 
- Doküman dili ve başlık yapısı PROJECTS.md ve README.md ile uyumlu olmalıdır. 
- PR açıklamasında “Bu ekleme X standardına referansla yapıldı” gibi kısa bir not bırakmak önerilir. 
- Örnek: “feature/etiket-standart ekleme” branch’inde yapılan PR, Standartlar.md’nin 3. bölümüne referans verir. 

# İletişim 

- Sorular, öneriler veya tartışmalar için GitHub Issues kullanılabilir. 
- Katkılar, Vynkrex projelerinin düzenli ve sürdürülebilir gelişimine doğrudan destek olur. 
- Bu rehber, Vynkrex projelerine katkı yapan herkes için referans noktasıdır ve zamanla güncellenebilir.
