+++
title = "Agar.io Detayları, Hileleri ve Yazılım Altyapısı"
date = "2015-06-11T19:36:46+03:00"
slug = "agar-io-detay-hile-altyapi"
categories = ["Blog"]
tags = ["agar", "agar game", "agar.io", "agar.io hack", "agar.io hile", "oyun"]
+++
Agar.io ortalığı kasıp kavurmaya devam ediyor. Ben de oyu hakkında öğrendiğim ilginç bilgileri toparladım ve paylaşmak istedim.
<h2>Agar.io'da Hile Yapmak</h2>
Oyunun ilk zamanlarında bazı açık kapıları bulunmuş ve hileler yapılabilmiş. Şimdi bile oyunu kırmak için bir çok girişim var. Oyun tarayıcı tabanlı olduğu için çeşitli "<strong>Javascript Gömme</strong>" yöntemler, sunucudan gelen istek ve dönen cevapları "<strong>araya girerek</strong>" yanıltma gibi yöntemlerle sistemi yanıltmak mümkün olabilir.

Oyunda en büyük yapılmak istenen şeyler; görünmez olmak, daha hızlı hareket edebilmek, hızlı büyüyebilmek. Bunu yapabilen birileri oyunu kırabilir. Fakat yapımcının söylediğine göre bunları yapmak artık imkansız. Bence çok kesin konuşmamak lazım :)
<p style="text-align: justify;"><img class="aligncenter wp-image-2479 size-medium" src="/images/2015/06/agar-300x176.png" alt="agar.io ekran" width="300" height="176" /></p>
<!--more-->

Bunların yanında hile sayılmasa da bir de şu var; oyun sizi rastgele sunuculara atıyor. Bazı yöntemlerle aynı sunucuya düşmeyi sağlayabiliyorsunuz. Bu da takım halinde hareket edip güç kazanmaya imkan sağlıyor. Bildiğim kadarıyla bunun önüne geçilebilmiş değil ve zor gibi de görünüyor.
<h2>İlginç Bilgiler</h2>
<a href="http://webvaluecheck.com/agar.io" target="_blank" rel="noopener">webvaluecheck</a> deki bilgiye göre şu an sitenin değeri <strong>48000 dolar </strong>ve Giderek de artıyor. Oyuna bir günde bağlanan toplam oyuncu sayısı Mayıs 2015 sonunda "bir milyon" değerine ulaşmış.
Oyunu herkes kırmaya çalışıyor.

Google.com'da "site:agar.io" araması yaptım. İlginçtir 7 adet sonuç çıktı. Çok popüler olup bu kadar az sonuç çıkması da ayrıca ilgi çekici. Bazılarını sıralıyorum;
<ul>
	<li>"<strong>agar.io/interviews.txt</strong>"
<ul>
	<li>Türkiye'den bir arkadaşımız yapımcı ile röportaj yapmış. Kanıt için de linkini siteye eklemesini rica etmiş. Yine ilginç :)</li>
</ul>
</li>
	<li><strong>http://m.agar.io/?_=1430382293424</strong>
<ul>
	<li>Sanırım sunucu ile haberleşmek için dışarı açıp bir api çağrısı bu.</li>
</ul>
</li>
	<li><strong>http://agar.io/privacy.txt</strong>
<ul>
	<li>Klasik bir gizlilik politikası. En son Kasım 2014'te güncellenmiş. Açık bilgileri alıyorlarmış. Bilgilerinizi satmayız, paylaşmayız diyor.</li>
</ul>
</li>
	<li><strong>http://agar.io/changelog.txt</strong>
<ul>
	<li>Güncelleme dokümanında hep tarih veya versiyon olur. Burada yok :) Amatör ruhu gösteriyor bence. Yazılımcıysanız tek tek okumanızı tavsiye ederim.</li>
</ul>
</li>
	<li><strong>http://m.agar.io/fullInfo, http://m.agar.io/info</strong>
<ul>
	<li>Oyunun canlı istatistiklerini buradan JSON formatında sunmuşlar. Hangi bölgede kaç sunucu, kaç oyun alanı ve kaç oyuncu olduğu bilgisi yer alıyor. Bunları gün gün tutup bir log tutmak mümkün ki bunu yapan siteler olmuş :)</li>
</ul>
</li>
</ul>
Ayrıca siteden olmayan bir sayfayı çağırdığınızda (ki buna <strong>404</strong> hata kodu deniyor) karşımıza "0.0.0.0:443" cevabı dönüyor. Demek ki arkadaşlar sunucu/istemci kafasıyla düşünüyorlar :)
<h2>Sosyal Medyada Agar.io</h2>
Agar.io'nun sosyal mesajlaşma ağı reddit.com. https://www.reddit.com/r/Agario/ adresinden <strong>agar.io</strong> sevenlerin tüm paylaşımlarını takip edebilirsiniz. Ayrıca burada üretici ekibin yayınladığı gelişmeler ve haberler de mevcut.

Ayrıca<strong><a href="http://twitch.tv" target="_blank" rel="noopener"> twitch.tv</a></strong>'de oyunu canlı olarak oynayan bir sürü fan var. Ben birkaçına baktım. Oyunda senaryo olmadığından daha çok yanında sohbet ağırlıklı olarak oynuyorlar.

Bunların yanında oyun piyasanın devlerinden steam de agar.io'yu<a href="http://steamcommunity.com/sharedfiles/filedetails/?id=436491794" target="_blank" rel="noopener"> kendi platformuna</a> eklemiş.
<h2>Agar.io'nun Yazılım Altyapısı</h2>
Agar.io web tabanlı bir oyun. Web tarafını HTML5 destekli web soket mimarisiyle yazmışlar. Böyle bir oyunu yazmak için en az orta düzeyde bir bilgi gerekir. Bu oyun sunucu ile haberleşen bir istemci aslında. Tüm hesaplamalar sunucuda yapılıyor. Sunucu da C++ ile yazılmış bir program.

Elbette herkesi bir sunucuya yönlendirmek mümkün değil. Bu sebeple sanırım istek alan bölgeler göz önünde bulundurularak yeni sunucular eklenmiş. Web sitesi sizi ülkenize göre ve sonra yoğunluğa göre sunuculara yönlendiriyor.