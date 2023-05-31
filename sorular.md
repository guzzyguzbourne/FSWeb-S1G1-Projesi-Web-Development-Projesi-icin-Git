# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
-Versiyonlama sistemi

2. Git ile GitHub arasında ne fark var?
- github, git kullanırken projeleri, bunları depoladığımız yer

3. Neden bir branch oluşturuyoruz?
-Yeni bir feature denemek için

4. Pull Request'in amacı nedir?
- Yapılan değişiklikleri, geliştirmeleri karşı tarafa gönderip, kontrol edilmesini ve codeların merge edilmesini sağlıyor

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın? -git checkout -b ile yeni branch oluşrururuz.
- git checkout "branch-name" komutu ile geçeriz. Haangi branchte olduğumuzu da git branch ile kontrol ederiz, yanında yıldız olan current branchi gösterir, main branche geçmek için git checkout "main" ile geçeriz

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
- git fetch: yeni yapılanları locale çekiyor, sadece bilgisini alıyor, bilgiyi alıyor ( yeni yapılan ne var diye bakmak için, sonra onları pull edip locale alırız)
- git pull ile değişmiş olan her şeyi alıp localde değişiklikle orginali hepsini alıyor, veriyi alıyor
-`git merge` ile değişiklikleri birleştiriyoruz, veriyi merge ediyor

7. Merge conflict nedir?
- aynı anda aynı değişiklikler yapılabilir, bu durumda uyarı geliyor zaten (aynı kaynak source üzerinde farklı kişiler değişiklik yapınca olabiliyor)

8. Merge conflict'i nasıl çözeriz?
- genelde pull req yapınca githubda hepsini gösteriyor, uyarı veriyor (her iki taraftaki yapılan işlemleri gösteriyor)
- gösterdiği seçeneklerden birini seçip devam edebiliyoruz, hangisi doğruysa onu seçip devam edebiliriz.