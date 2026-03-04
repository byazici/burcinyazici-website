+++
title = "Trafik Işıkları Nasıl Çalışıyor? Benim Bir Önerim Var!"
date = "2010-12-16T13:16:25+03:00"
slug = "trafik-isiklari-nasil-calisiyor-benim-bir-onerim-var"
categories = ["Blog"]
tags = ["öneri", "program"]
+++
<strong>İstanbul</strong>'daki trafiği anlamak zaten mümkün değil. Sanırım binlerce parametreye bağlı bir <strong>fonksyion</strong>! Her gün geçtiğim cadde çoğunlukla kalabalık olur. Bugün sabah geçtiğimde bomboştu(!) Hafif yağmur da vardı ama yine de cadde boştu .

Fakat garip bir durumla karşılaştım. Arabayla kırmızıda bakliyorum. Sonra yeşil yanınca devam ediyorum... Fakat bir sonraki ışıklara yaklaşırken <strong>tekrar </strong>kırmızı yanıyor. Bu  tekrar 4-5 ışık boyunca böyle oldu hep. Sanırım ışıklar<strong> sıkışık trafiğe</strong> göre ayarlanmış ve yol boş olunca <strong>sorun </strong>oluyor :)

Acaba bu ışıklar nasıl <strong>çalışıyor</strong>? Tahminim <strong>saat </strong>ve/veya<strong> tatil günleri </strong>bazında bir takım düzenlemeker vardır.
<h3>Peki şöyle olsa nasıl olurdu:</h3>
Belli güzergah üzerindeki ışıklar ölçtüğü <strong>verileri </strong>merkeze gönderse ve merkezde koşan bir <strong>algoritma </strong>bu verileri çarpsa ve bölse sonra da yeni<strong> ışık yanma sürelerini</strong> trafik ışığına <strong>geri gönderse</strong> nasıl olurdu? Çok güzel olurdu ama basit bir cümleyle anlatılan bu konu için ciddi bir donanım maliyeti ve bir o kadar da önemlisi bu verileri alınca düzgün değerlendiren bir yazılım. Bu yazılı yazacak çok yetenekli programcılar var Türkiye'de. Bu noktada sorun yok ama ilk yatırımların yapılmasında biraz düşünmek gerekiyor. Olmayacak şey değil bence. Deneme için önemsiz bir kaç güzergah seçilip deneme yapılabilir.
<h3>Yazılım açısından;</h3>
Önce "Porblem" tanımları belirlenebilir. Örneğin kırmızı ışıkta bekleyen araç sayısı saat ve gün bazında  kaydedilip bir önceki haftanın kayıtlarıyla karşılaştırılabilir. Böylelikle uygulanan algoritmanın başarısına bakılabilir. Ayrıca "standart sapma" ların önemi de büyük. Eğer hafta içi günlerden birisi "23 Nisan" a rastlarsa elbette trafik yoğunluğu farklı olur. Belkide bunu da parametre olarak eklemek lazım.
<h3>İlk aklıma gelen parametreler:</h3>
<ol>
	<li>Saat</li>
	<li>Hafta sonu/hafta için günleri</li>
	<li>Resmi tatil/bayram vs.  olup olmadığı</li>
	<li>Hava durumu</li>
	<li>Kapalı yollar ve bakım çalışmaları</li>
	<li>Trafiğe çıkan araç sayısı (ay ay tescillenen)</li>
</ol>
<strong>Bunlar neden olmasın güzel Türkiye'mde?</strong>