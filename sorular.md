# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Yazılım geliştirme süreçlerinde dosya ve kod değişikliklerinin izlenmesi, kaydedilmesi ve yönetilmesi için kullanılan bir araçtır.

2. Git ile GitHub arasında ne fark var?
Git, dağıtık bir versiyon kontrol sistemi iken, GitHub, Git tabanlı projelerin barındırıldığı ve işbirliği yapılan bir bulut tabanlı platformdur.

3. Neden bir branch oluşturuyoruz?
Bir "branch" oluşturmanın temel amacı, mevcut kod tabanını ana projeden bağımsız bir geliştirme yoluna ayırmaktır.

4. Pull Request'in amacı nedir?
Pull Request, değişikliklerinizi bir dal üzerinde geliştirdikten ve tamamladıktan sonra, bu değişikliklerin ana projeye entegre edilmesini sağlayan bir işlem ve inceleme mekanizmasıdır.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git checkout main

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

git fetch, uzaktaki değişiklikleri getirir ancak yerel dalınızı güncellemez.
git merge, farklı dallardaki değişiklikleri birleştirir.
git pull, git fetch ve git merge işlemlerini birleştirir, uzaktaki değişiklikleri alıp doğrudan mevcut çalışma kopyasına entegre eder.

7. Merge conflict nedir?
Merge conflict, Git'te farklı dallardaki değişiklikleri birleştirirken karşılaşılan bir durumdur. 

8. Merge conflict'i nasıl çözeriz?
merge conflict'leri çözmek, etkilenen dosyalardaki çakışma işaretlerini düzenleyerek ve değişiklikleri uygun bir şekilde birleştirerek gerçekleştirilir. 