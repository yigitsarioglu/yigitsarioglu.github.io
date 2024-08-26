---
layout: post
title: 50 Soruda Yapay Zeka | Cem Say
date: 2024-08-26 00:00:00 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: blog_images/yapay_zeka.jpg # Add image post (optional)
tags: [Programming, Learn] # add tag
---
Merhabalar,

Bugünkü blog yazımızda yeni okuyup bitirme şerefine nail olduğum, çok değerli bir kitap olan “50 soruda yapay zeka” kitabını konu edineceğim. Boğaziçi Üniversitesi Bilgisayar Mühendisliği Bölümü öğretim üyesi Cem Say, bu kitapta yapay zekâ kavramını her yönüyle ve herkesin ilgisini çekebilecek biçimde anlatıyor. Yapay zekâ sistemlerinin dayandığı matematiksel altyapıyı, gelişim serüvenini, insan beyni dediğimiz doğal bilgisayarın çalışması hakkında verdiği ipuçlarını, güncel uygulamalarının nasıl çalıştığını ve nerelerde tıkandığını, yarattığı felsefi tartışmaları, bilinç ve özgür iradeyle ilgisini ve insanlığa olumlu/olumsuz etkilerini keyifli bir dille işliyor.

Kitaptan notlar :

-   11 Mayıs 1997 Deep Blue, New York’ta düzenlenen 6 oyunluk rövanş maçını (satranç) son oyunda Kasparov’u perişan ederek kazandı.
-   2016 yılında AlphaGo adında bir program (derin öğrenme tekniği ile go öğrenen bir program), Avrupa Go şampiyonunu ile maç yaptı ve bu maçı 5-0 kazandı.
-   Gottfried Wilhelm Leibniz, tarihteki ilk bilgisayar mühendislerindendir. Leibniz 25 yaşında iken, dört işlem yapabilen bir makine geliştirdi ve bunu 1673’te Londra Kraliyet Akademisine sundu.
-   George Boole, düşünce dilinin matematiksel gösteriminin bulunmasına katkıda bulundu. (0 ve 1’ler ile gösterim)
-   Gottlob Frege “düşünce dili” projesini tamamlayan kişi olarak görülebilir.
-   Kurt Gödel, matematiğin eksiksiz olduğuna, yani doğru olan her şeyin kanıtlanabileceğine dair düşünceyi 1930’da yerle bir etmiştir.
-   Alan Turing, bilgisayar biliminin babası ve yapay zekanın kurucusu olarak bilinir. 20.yüzyılın en büyük bilim adamı olan Turing, çok yönlü bir dehaydı. Turing makinesini tanımlamıştır.

<div style="text-align: center;">
<img src="{{site.baseurl}}/assets/img/blog_images/yapay_zeka.jpg" alt="Yapay Zeka" width="200"/>
</div>



## Turing Makinesi

İlk elektronik bilgisayar, İkinci dünya savaşı sırasında Bletchley Park’ta Alman Enigma kodunu kırmak için inşa edildi. Bu, yukarıda bahsedilen teorik makineyi geliştiren Alan Turing sayesinde oldu. Alan Turing 1936’da hesaplamanın matematiksel modelini kurdu. Bu modelde, günümüzde Turing makinesi olarak adlandırılan soyut bir makine vardır.

Turing makinesi aritmetik hesaplamalarının kağıt kalem ile yapılma sürecini taklit eden hayali bir cihazdı. Tam olarak nasıl çalıştığını anlamak için öncelikle fonksiyon kavramını düşünmelisiniz. Sonuçta fonksiyonlar da bir nevi makinelerdir. Bu makineye bazı girdiler verir ve çıktılar elde edersiniz.

Peki aynı fikri algoritmalar aracılığı ile bilgisayarlara uygulamak mümkün mü? Turing’in yaptığı da tam olarak buydu. _Günümüzde Turing makinesi_ olarak adlandırılan teorik bir bilgisayar modeli ile bunu gerçekleştirdi.

Alan Turing’in bilgisayar biliminin temellerini atarken tanımladığı soyut Turing makinelerinin çalışma ilkesi gayet basittir. Makine sonsuz uzunlukta olduğu varsayılan bir şeridin üzerindeki girdileri okur ve işler. Sonrasında da çıktıları yine bu şeridin üzerine yazar. Şerit, her biri sadece tek bir sembol içeren ya da boş olan karelere bölünmüştür. Makinede, her seferinde bandın bir sembolünü okuyan bir okuyucu yer alır.

Makine okuduğu veriyi işledikten sonra o karedeki sembolü silerek yeniden yazar ya da hiçbir şey yapmaz. Ayrıca makinenin okuma ve yazma işlemlerini yapan kafa kısmı işlemi tamamladıktan sonra bir birim sağa ya da sola hareket eder.

Bu eylemlerden hangisini gerçekleştirdiği ve gerçekten yaparsa hangi yeni sembolü yazdığı, içinde bulunduğu duruma bağlıdır. Daha sonra solda veya sağda bir sonraki sembolle karşılaştığında, yine içinde bulunduğu duruma göre tepki verir. Temsili bir Turing makinesini aşağıda görüyorsunuz.

![Turing Machine]({{site.baseurl}}/assets/img/blog_images/turing_machine.webp)

## Son

Son olarak şunları söyleyebilirim ki, bilgisayar bilimlerine ve yapay zeka çalışmalarına ilgisi olan herkesin kitabı okumasını öneririm. Yapay zekanın tarihsel serüvenini ve katkı sunan araştırmacıların/bilim adamlarını bu kitaptan öğreniyoruz.