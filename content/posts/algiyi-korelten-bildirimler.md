+++
title = "Algıyı Körelten Bildirimler"
date = "2023-10-15T21:00:00+03:00"
slug = "algiyi-korelten-bildirimler"
categories = ["Teknoloji"]
tags = ["bildirim", "datadog", "gözlem yazılımları", "monitoring", "Nagios", "SolarWinds", "veritabanı", "yazılım", "Zabbix"]
+++
<!-- wp:paragraph -->
<p></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>İster yeni bir <strong>girişim</strong> olun, ister büyük bir <strong>işletme</strong> olun yazılım, donanım ve ağlarınızı mutlaka <strong>gözlemlemeniz</strong> gerekiyor. Bununla birlikte alınan bildirim mesajları <strong>arttıkça </strong>bu bildirimleri "<strong>görmezden gelmek</strong>" şeklinde bir refleks gelişebilir. Bunun nedenlerine ve çözüm önlemlerini göz atalım.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Günümüzde <strong>riskleri azaltma</strong>, <strong>kalite standartları</strong>nı yerine getirme ve <strong>verimliliği artırmak</strong> için kritik öneme sahip sistemlerimizi gözleyen ve gerektiğinde uyarı üreten çözümler kullanıyoruz. Bunlar bazen bulut servisler, açık kaynak yazılımlar veya iç ekipler tarafından geliştirilmiş yazılımlar olabiliyor. </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Bu konuda en çok kullanılar çözümler; <strong>Zabbix</strong>, <strong>Nagios</strong>, <strong>SolarWinds</strong> ve <strong>Datadog</strong> diyebiliriz. Ben aktif olarak Datadog kullanıyorum ve yüzlerce gözlemi Datadog üzerinden yapıyoruz.</p>
<!-- /wp:paragraph -->

<!-- wp:heading -->
<h2 class="wp-block-heading">Bildirim Örnekleri</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Bildirimler genellikle <strong>hata</strong> bildirimi, <strong>durum</strong> gözlemleme ve <strong>rapor</strong> üretme amacıyla kullanılır. Bildirimlere çok kullanılan bir kaç örnek verelim:</p>
<!-- /wp:paragraph -->

<!-- wp:list -->
<ul><!-- wp:list-item -->
<li>Her gece çalışan bir görevin çalışıp çalışmadığının takibi.</li>
<!-- /wp:list-item -->

<!-- wp:list-item -->
<li>Sunucu veya veritabanındaki boş diskin gözlemlenesi.</li>
<!-- /wp:list-item -->

<!-- wp:list-item -->
<li>Hizmet olarak sunduğumu bir API servisinin çalışır durumda olduğunun gözlemlenmesi (api health).</li>
<!-- /wp:list-item -->

<!-- wp:list-item -->
<li>Veritabanı/sunucu yedeklerinin başarıyla alındığının takibi.</li>
<!-- /wp:list-item -->

<!-- wp:list-item -->
<li>Veritabanına düzenli sorgular göndererek bazı özet bilgileri yorumlayıp uyarı oluşturmak vb.</li>
<!-- /wp:list-item --></ul>
<!-- /wp:list -->

<!-- wp:paragraph -->
<p>Örnekler çoğaltılabilir... </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Çoğunlukla başımıza bir <strong>sorun</strong> çıkmadan bu tür uyarılar da kullanmayız. Günü kurtarıp sonra hemen bir uyarı mekanizmasıyla <strong>takip</strong> etmeye başlarız. Bu uyarıların sayısı arttıkça <strong>bir risk </strong>oluşur...</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Diyelim ki her gün<strong> başarılı</strong> bir <strong>yedekleme</strong> sonrası BT bölümünün <strong>mail</strong> veya <strong>slack</strong> kanalına uyarı mesajı gönderiyoruz. İlk günlerde bu keyifli ve <strong>güven verici</strong> olur. Fakat her gün benzer mail gelmeye başladığında zamanla bir <strong>körelme </strong>meydana gelir ve diğer mesajların arasında bunu atlamak çok doğal hale gelir.</p>
<!-- /wp:paragraph -->

<!-- wp:heading -->
<h2 class="wp-block-heading">Algımızı Nasıl Canlı Tutarız?</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p><strong>Zamanla oluşan algı körelmesini önlemek için şunları tavsiye edebilirim:</strong></p>
<!-- /wp:paragraph -->

<!-- wp:list {"ordered":true} -->
<ol><!-- wp:list-item -->
<li>Aksiyon <strong>alamadığınız</strong> bildirimleri kapatın veya tekrar düşünün. Gerekirse <strong>parametreleri</strong> değiştirin.</li>
<!-- /wp:list-item -->

<!-- wp:list-item -->
<li>Her <strong>başarılı</strong> süreç için bildirim <strong>göndermeyin</strong>. Gerekiyorsa "<strong>haftalık rapor</strong>" şeklinde bildirim gönderin.</li>
<!-- /wp:list-item -->

<!-- wp:list-item -->
<li>Özellikle <strong>hata</strong> ve <strong>risk</strong> durumlarına yoğunlaşın.</li>
<!-- /wp:list-item -->

<!-- wp:list-item -->
<li>Ortamların (staging/live) bildirim kanallarını <strong>ayrıştırın</strong>. Canlı ortama gelen bir bildirim çok yüksek öncelikli olmalı.</li>
<!-- /wp:list-item -->

<!-- wp:list-item -->
<li>Bildirimleri genellemeyin, <strong>açıklayıcı</strong> olun ve <strong>aksiyon</strong> önerisinde bulunun.</li>
<!-- /wp:list-item --></ol>
<!-- /wp:list -->

<!-- wp:paragraph -->
<p>Yazılım ve donanımlar <strong>hata</strong> yapabilir. Bunu erken farkedip <strong>önlem</strong> alırsak sorunları aşarız. Siz de doğru bir yaklaşımla <strong>etkin</strong> bir <strong>bildirim</strong> sistemine sahip olabilirsiniz.</p>
<!-- /wp:paragraph -->