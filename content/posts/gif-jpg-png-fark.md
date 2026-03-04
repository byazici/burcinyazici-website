+++
title = "GIF, JPG ve PNG Arasındaki Farklar Nelerdir?"
date = "2011-03-20T15:48:48+03:00"
slug = "gif-jpg-png-fark"
categories = ["Internet", "Yazılım"]
tags = ["grafik", "ipucu", "webmaster"]
+++
Bilgisayarın iş hayatına girdiği yıllarda etkin olarak kullanıldığı sektörleirn başında "<strong>basın/yayın</strong>" önemli yer tutmuştur. Henüz <strong>oyun </strong>sektörü bile canlanmamışken bilgisayarlarla <strong>gazete </strong>tasarlanabiliyordu. Kısacası<strong> bilgisayar destekli grafik</strong> olgusu internetten çok daha eskiye dayanır. Böyle olunca da gelişen internetle birlikte grafik formatları da zaman içinde <strong>şekillendi, değişti.</strong>

Günümüzde internette yer edinmek (web sitesi, günlük vb.) artık çok daha kolay ve pratik. Bunu yaparken elbette çeşitli <strong>görseller </strong>de kullanırız. Peki <strong>hangi dosya formatlarını</strong> kullanmalıyız? Web tasarımında e<strong>n çok kullanılan </strong>görsel dosya formatlarını merak ediyorsanız ve bunlar arasından hangi formatı <strong>nasıl seçmemiz </strong>gerektiği konusunda bilgi edinmek isterseniz buyrun okuyun:
<h2>GIF (Graphics Interchange Format)</h2>
<h3>GIF Nedir?</h3>
Web ortamında kullanılan en eski formatlardandır. <strong>1980</strong>'lerde sırasıyla <strong>87a </strong>ve <strong>89a </strong>adıyla iki ayrı formatta çıktı. GIF formatında maksimum <strong>256 </strong>renk (8 bit) seçeneği mevcuttur. GIF, <strong>LZW </strong>sıkıştırmasını kullanır. Yapısal olarak ne kadar az renk varsa GIF o kadar çok sıkıştırabilir. Bunların yanında  web yüklemeleri için <strong>serpiştirme </strong>(interlacing) özelliği de mevcuttur. Bu sayede resim <strong>bulanık </strong>olarak çıkar ve yüklendikçe <strong>netleşir</strong>. GIFlerin en önemli iki özelliği de "<strong>saydamlık</strong>" ve "<strong>hareketli grafik</strong>" desteklemesidir. Bu özellikler 89a formatlarıyla eklenmiştir.
<h3>GIF ne zaman tercih edilmeli?</h3>
<ul>
	<li><strong>Hareketli </strong>resim kullanmak istiyorsanız (flash vs. kullanmayacaksanız) başka seçeneğiniz yok.</li>
	<li> <strong>Az </strong>renkli grafik, çizimler için GIF kullanabilirsiniz.</li>
	<li> <strong>Renk geçişi</strong> olan grafikler GIF formatında çok başarılı olamazlar. Çünkü renk geçişleri büyük bir renk paleti gerektirir.</li>
	<li>Eğer<strong> anti-alias</strong> kullanılmazsa daha küçük boyutlarda GIF elde edersiniz.</li>
</ul>
<h2>JPEG (Joint Photographic Experts Group)</h2>
<h3>JPEG Nedir?</h3>
<strong>16.7 milyon</strong> renk seçeneğiyle "gerçek renk" desteği sağlar. JPEG'in <strong>sıkıştırma yüzdesi</strong> sayesinde %0-%100 arasında sıkıştırma sağlanabilir. Fakat JPEG sıkıştırırken görselin <strong>renklerinde kayıplara</strong> neden olur. O yüzden en yaygın oran olan<strong> %75 </strong>dışında bir oran kullanırken dikkat olmak gerekir. "<strong>Progressive JPEG</strong>" denilen format ise GIFteki "serpiştirme" özelliğine benzer bir özellik sağlar.
<h3>JPEG Ne Zaman Tercih Edilmeli?</h3>
<ul>
	<li>Her türlü <strong>fotoğraf </strong>ve<strong> zengin renk </strong>içeren görüntüler için JPEG kullanılabilir.</li>
	<li>Eğer GIF'teki görüntüsünü beğenmediğiniz bir görsel varsa alternatif olarak JPEG formatını seçebilirsiniz.</li>
	<li>Eğer görselleriniz "<strong>gölgeleme</strong>", <strong>"renk geçişleri</strong>", "<strong>degrade</strong>" gibi geniş bir renk paleti isteyen görseller ise JPEG uygun olacaktır.</li>
	<li>Bir resim büyük olsa da eğer<strong> 16 renkten daha az</strong> renk içerirse JPG pek uygun olmaz.</li>
</ul>
<h2>PNG (Portable Network Graphics format)</h2>
<h3>PNG Nedir?</h3>
Grafik formatların <strong>en yenisidır. </strong>Ortaya çıkışı diğer formatların <strong>patentlerine </strong>ödenen ücretlerden kaynaklanmıştır. <strong>1995 </strong>yılında ortaya çıkmıştır. "ping" diye telaffuz edilir. <strong>16.7 milyon</strong> (24 bit) renk destekler. JPEGin aksine resimlerde r<strong>enk kayıpları olmadan</strong> sıkıştırabilir. Sıkıştırması GIFten daha iyi olduğu test edilmiştir. GIF'in hareketlilik desteğinden dolayı onu <strong>tahtından </strong>indirmesi <strong>biraz zor</strong> ama zamanla daha yaygın kullanılmaya başlandığı kesin.
<h3>PNG Ne Zaman Tercih Edilmeli?</h3>
<ul>
	<li>Nispeten yeni bir format olduğundan<strong> eski nesil tarayıcılar</strong> desteklemeyebilir. Böyle bir riski var.</li>
	<li><strong>Sıkıştırma </strong>özelliği ve <strong>yüksek renk </strong>desteğinden dolayı GIF yerine PNG tercih edilebilir.</li>
	<li><strong>Küçük </strong>ama <strong>çok renkli</strong> grafikler için ne GIF ne de JPEG uygundur. PNG bu tür grafiklerde uygun olur.</li>
	<li>PNG formatının <strong>patenti </strong>olmadığından herkes rahatça kullanabilir.</li>
</ul>
Renk paletlerinin bir resmi nasıl etkilediğini görmek için wikipedia'daki "<strong><a href="http://en.wikipedia.org/wiki/Color_depth" target="_blank">Renk Derinliği (Color Depth)</a></strong>" yazısındaki göresellere bakmanızı öneririm.
<h3>Özetlemek gerekirse;</h3>
<ol>
	<li>Hareketli veya saydam grafikler için <strong>GIF</strong></li>
	<li>GIFin yeterli olmadığı veya kayıplı sıkıştırmanın kabul edilebildiği grafiklerde <strong>JPEG</strong>,</li>
	<li>Çok renkli ve kayıpsız grafiklerde ise <strong>PNG</strong></li>
</ol>
<strong>kullanılması tavsiye edilir.</strong>