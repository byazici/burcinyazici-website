+++
title = "Wordpress Yazılarını Kelime Sayısına Göre Nasıl Listelerim?"
date = "2012-02-29T00:42:11+03:00"
slug = "wordpress-yazilarini-kelime-sayisina-gore-nasil-listelerim"
categories = ["Yazılım"]
tags = ["mysql", "php", "wordpress", "wordpress eklenti", "wordpress plugin"]
+++
<p title="Google Page Layout">Google, en son yaptığı <strong>panda</strong> güncellemesiyle <strong>SEO</strong> kurallarındaki bazı kavramların değişmesine yol açtı. Bildiğimiz gibi sayfanın <strong>görünen kısmındaki</strong> içeriğin kalitesine göre (bkz: <a title="Google Page Layout" href="https://burcinyazici.com/google-page-layoutsayfa-duzeni-algoritmasi-nedir-kimleri-etkiler-nasil-onlem-almali-2220.html">Google Page Layout Algoritması</a>) sonuçların sıralama değerlerini yeniden hesapladı. Günlük ziyaretleri <strong>ani düşüş</strong> yaşayan site sahipleri bazı çözümler için düzenlemelere gittiler.</p>
Panda güncellemesi kapsamında yapılan düzenlemelerden birisi de "<strong>thin content</strong>" denilen değeri olmayan yazıları bulunup temizlenmesidir. Bunun için iki ana teknik var:
<ol>
	<li>Uzun süredir<strong> ziyaret edilmemiş</strong> yazıların temizlenmesi.</li>
	<li>İçeriği <strong>yetersiz</strong> ve çoğunlukla çok<strong> az kelime içeren</strong> yazıların temizlenmesi (unutmayalım, yazı uzunluğunun kısa olması içeriği kesinlikle değersiz kılmaz!).</li>
</ol>
<a href="https://burcinyazici.com/wp-content/uploads/2012/02/thinContentWordCount.gif"><img class="aligncenter size-full wp-image-2349" title="thinContentWordCount" src="/images/2012/02/thinContentWordCount.gif" alt="" width="582" height="344" /></a>

Ben şu an<strong> 2nci maddeyi</strong> rahat bir şekilde irdelemek için bir <a title="wordpress" href="https://burcinyazici.com/etiket/wordpress"><strong>wordpress</strong></a> kodu yazdım ve bunu <strong>paylaşmak</strong> istiyorum. Şu an <strong>wordpress-plugin</strong> yapamadım ama en kısa sürede yapacağım. Aşağıdaki <strong>thinContentWordCount.php</strong> dosyasını indirip kullanmak istediğiniz dizine kopyalayıp hemen kullanabilirsiniz.
<ol>
	<li>Sadece <strong>admin</strong> <strong>yetkili</strong> olan kullanıcılar listeyi görebilir.</li>
	<li>Listede yazıların <strong>kelime sayıları</strong> dökülmektedir (+/-1 yaklaşık sonuç olabilir).</li>
	<li>Yazıları <strong>görüntülemek</strong> ve <strong>güncellemek</strong> için linkler yer almaktadır.</li>
	<li><strong>Kelime sayılarını</strong> tek tek yazılar üzerinde dönerek değil doğrudan <strong>mysql</strong> ile sorguladım. Böylece çok hızlı şekilde sonuç alabildim.</li>
</ol>
Bunu kullanarak içeriği <strong>yetersiz</strong> olan yazılara göz atabilirsiniz. Fakat yazılarınızı silerken <strong>dikkat</strong> edin. Her zaman bir yazının ziyaret edilmemesi yazının <strong>zayıf</strong> olduğunu göstermez. Belki içerik dönemsel olarak aranmıyor da olabilir. Burada son kararı siz vereceksiniz.
<p style="text-align: center;"><strong><a href="https://burcinyazici.com/wp-content/uploads/thinContentWordCount.rar">İndirmek için tıklayınız</a></strong></p>