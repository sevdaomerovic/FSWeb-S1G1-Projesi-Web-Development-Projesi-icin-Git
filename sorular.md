# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
   Açık kaynak kodlu bir versiyon kontrol sistemidir. Bir web sitesinin çeşitli geliştirme/güncellemeler öncesi ve sonrasında, sitenin geçirdiği tüm revizyonları görmemize olanak sağlayan bir sistemdir. Aynı anda birden fazla kullanıcının branch oluşturarak proje üzerinde çalışmasına olanak verir.

2. Git ile GitHub arasında ne fark var?
   Git bir versiyon kontrol sistemi iken, GitHub en yaygın kullanılan Git uygulamalarından biridir.

3. Neden bir branch oluşturuyoruz?
   Üzerinde çalıştığımız kaynak kodun orijinalini korumak, çalışmalarımız devam ederken diğer kullanıcıların da projenin orijinaline erişimlerini kaybetmemelerini sağlamak için branch oluşturuyoruz.

4. Pull Request'in amacı nedir?
   Kaynak üzerinde yaptığımız değişikliklerin master branche eklenmesi için proje yöneticisine onaya göndermektir.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
   "git checkout main" komutunu kullanırız.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
   git fetch : Başka bir sunucunun tüm içeriğini ve verilerini kendi sunucumuza çekmemizi sağlar.
   git merge : Kendi bilgisayarımızda yaptığımız değişiklikleri main branche eklemeyi sağlar.
   git pull : Başka bir sunucunun içeriği ve verilerini kendi sunucumuza çekmemizi sağlarken, Git fetch'ten farklı olarak bunu merge ederek yapmaktadır. Diğer sunucuda yapılan değişiklikleri kendi sunucumuzla kıyaslamadan verileri otomatik olarak merge eder.

7. Merge conflict nedir?
   Aynı dosyada aynı satırın/aynı verinin birden fazla kişi tarafından aynı anda güncellenmesi ve git'in otomatik olarak bunları merge edememesi durumuna merge conflict denir. Hangi revizenin kabul edilip hangi revizenin ignore edileceği belirsiz olduğu durumlarda merge conflict oluşur.

8. Merge conflict'i nasıl çözeriz?
   Merge conflicti çözmek için çakışmalı olan kısımların kullanıcı tarafından manuel olarak düzeltilmesi ve tekrar merge işlemi yapılması gerekir.
