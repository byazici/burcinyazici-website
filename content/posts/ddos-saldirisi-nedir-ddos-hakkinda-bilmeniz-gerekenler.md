+++
title = "DDoS Saldırısı Nedir? DDoS Hakkında Bilmeniz Gerekenler"
date = "2019-10-28T19:28:02+03:00"
slug = "ddos-saldirisi-nedir-ddos-hakkinda-bilmeniz-gerekenler"
categories = ["Internette Güvenlik"]
tags = ["ddos nasıl yapılır", "ddos nedir", "ddos saldırısı algılama", "ddos saldırısından korunma", "ddos saldırısının belirtileri", "ddos takibi", "ddos türleri nelerdir", "honeypot nedir", "önemli ddos saldırıları", "siber güvenlik", "siber saldırı haritaları"]
+++
<!-- wp:paragraph -->
<p><strong>26 Ekim 2019</strong> hafta sonu ülkemiz ciddi bir <strong>DDoS</strong> saldırısı ile karşı karşıya kaldı. Bu saldırıda <strong>Garanti BBVA</strong> ve <strong>Türk Telekom</strong> çok ciddi etkilendiler. Bu olaylardan hareketle DDoS Saldırılarıyla ilgili soruları cevaplayan bir yazı derledim. Bu yazıda DDoS'un anlamı, nasıl yapıldığı, neden yapıldığı, nasıl korunmak gerektiği gibi merak edilen soruların cevaplarını bulabilirsiniz.</p>
<!-- /wp:paragraph -->

<!-- wp:heading -->
<h2>DDoS Saldırısı Nedir?</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>DDoS ingilizce "<strong>distributed denial-of-service</strong>" kelimelerinin kısaltılmasıdır. DDoS, sunucuların gerçek görevlerini yerine getirmelerini geçici veya kalıcı olarak aksatmak maksadıyla yapılan bir saldırı türüdür. </p>
<!-- /wp:paragraph -->

<!-- wp:heading -->
<h2>DDoS Saldırısı Nasıl Yapılır?</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Bu saldırı tek bir merkezden değil <strong>dağıtık</strong> kaynaklardan aynı anda harekete geçilerek yapılır. Bu sebeple saldırıdan önce fayda sağlanacak olan bilgisayarlara <strong>kötü niyetli</strong> yazılımlar sayesinde ajanlar yerleştirilir (malware). Bu ajanlar emir almak için  hazırda beklerler. Saldırı sahibi saldırmak istediği hedefin <strong>IP</strong> numarasını ve saldırı <strong>zamanını</strong> kısa söre önce bildirir. Zaman gelince bir çok kaynaktan hedefe doğru kapasitesini aşacak şekilde istek yapılır.</p>
<!-- /wp:paragraph -->

<!-- wp:heading -->
<h2>Kaç Tür DDoS Saldırısı Vardır?</h2>
<!-- /wp:heading -->

<!-- wp:list {"ordered":true} -->
<ol><li><strong>Application Layer Attacks:</strong> Bu saldırıda bir hedef web sayfası belirlenip onu çok hızlı ve paralel şekilde çağırarak sunucuyu cevap vermez hale getirerek yapılır. Bu saldırıda her çağrı farklı bir yerden geliyor gibi gösterip algılanması oldukça zor olabilir.,</li><li><strong>Protocol Attacks:</strong> Bu saldırı ağdaki zayıflıklardan faydalanarak sunucu kaynaklarının tüketilmesini sağlar. Buna örnek "SYN Flood" saldırısında; çok hızlı bir şekilde ağ bağlantı açma isteği gönderilip cevabı beklenmeden aynı talep tekrar tekrar gönderilince sunucu kaynakları tükenmeye doğru gider. </li><li><strong>Volumetric Attacks: </strong>Bu saldırı türünde de sunucuya boyut olarak çok büyük <a href="https://burcinyazici.com/kategori/veri/">veri</a> paketleri gönderilir. Sunucu bunları alıp bir cevap dönmek üzere programlandığından; bu isteklerden binlercesini aynı anda göndererek sunucunun kaldırabileceği bant genişliği daraltılıp tıkanır. Böylece sunucu yine cevap vereme hale gelir.</li></ol>
<!-- /wp:list -->

<!-- wp:heading -->
<h2>DDoS Saldırısı Altında Olduğumuzu Nasıl Anlarız?</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>DDoS saldırısı altındaysanız aldığınız veya verdiğiniz hizmetlerde <strong>kesintiler</strong> yaşanır. Web erişimleri <strong>dengesiz</strong> olarak devam eder. Eğer saldırı hafif boyutta ise bunu geçici bir sıkıntı var diyerek görmezden gelir ve 1-2 dakika içinde <strong>normale</strong> dönebilirsiniz. Fakat ciddi bir saldırı varsa ve bir korumanız yoksa yüksek ihtimal tüm hizmetin <strong>kesilmesiyle</strong> sonlanabilir.</p>
<!-- /wp:paragraph -->

<!-- wp:heading -->
<h2>DDoS Algılama Metodları</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>DDoS saldırısından korunabilmek için saldırı altında olduğumuzu <strong>algılamak</strong> çok önemli. Başlıca metotlar şunlar:</p>
<!-- /wp:paragraph -->

<!-- wp:list {"ordered":true} -->
<ol><li><strong>Flow Sampling</strong>: Router cihazlarında gelen paketlerden örneklemeler alınıp paketlerin içeriği hakkında bilgiler toplanır.</li><li><strong>Package Analysis</strong>: DDoS azaltma donanımları gelen ve giden tüm paketleri algılayarak trafiğin saldırı olup olmadığını denetler. Bu işi simetrik ve asimetrik olarak yapabilir. </li><li><strong>Mirrored Data Packets</strong>: Bu yöntemle paketler aynalanır ve derinlemesine analiz edilir. Böylece saldırı olup olmadığına bakılır. Bu yöntem de etkilidir fakat trafik hızının artışına göre ölçeklemek konusunda güçlü değildir. </li></ol>
<!-- /wp:list -->

<!-- wp:heading -->
<h2>DDoS Saldırısından Nasıl Korunuruz?</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Bu tür saldırıları algılamak için bir çok <strong>dijital</strong> hizmet olmakla birlikte burada <strong>insan</strong> faktörü de çok önemlidir. Ağları görsel olarak izlemek için <strong>paneller</strong> yaparak gözle de gözlemlemek gerekir. Burada bir yatırım yapmak gerekiyor. Bu yatırıma potansiyel kaybın boyutuna göre karar vermelisiniz. <strong>DDoS</strong> saldırılarına karşı bazı önerileri paylaşıyorum:</p>
<!-- /wp:paragraph -->

<!-- wp:list {"ordered":true} -->
<ol><li>Bant genişliği çok önemli. Trafik %30 artınca sınıra geliyorsanız saldırı önleme çözümleri dahi size yardımcı olmayabilir.</li><li>Ağınızı görsel olarak takip edebileceğiniz yazılım ve donanımlar edinebilirsiniz.</li><li>Firewall ve ağların güvenlik yamalarını mutlaka güncel tutun. Saldırıların bir kısmı güncellenmemiş donanımlarda oluşan açıklar sayesinde yapılıyor. </li><li>Bu konuda profesyonel destek almaktan çekinmeyin. Ağ güvenliğinde uzman firmalarla görüşüp bir çözüm önerisi isteyebilirsiniz. Unutmayın bu iş uzmanlık gerektirir.</li></ol>
<!-- /wp:list -->

<!-- wp:heading -->
<h2>Saldırı Altında Ne Yapmak Gerekir?</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Eğer saldırıya uğruyorsanız <strong>hızlıca</strong> almanız gereken bazı <strong>önlemler</strong> var. Kısaca değinmek gerekirse:</p>
<!-- /wp:paragraph -->

<!-- wp:list {"ordered":true} -->
<ol><li>"DDoS mitigation systems" denen DDoS saldırılarını azaltılcı faydası olan yazılımlardan edinip kullanmaya başlamanız gerekiyor.</li><li>IP adres değişikliği önemli.</li><li>DNS kayıtlarının maksimum güvenlik için ayarlanmış olduğun emin olun.</li><li>Özellikle bir yerden saldırı alıyorsanız o kaynağı doğrudan bloklayabilirsiniz</li><li>E-posta iletişimi ve buna benzer hassas servisleri ağınızdan ayrı bir yerde barındırıp saldırı anında iletişimin etkilenmesini de engelleyebilirsiniz.</li></ol>
<!-- /wp:list -->

<!-- wp:heading -->
<h2>Tarihteki En Önemli 5 DDoS Saldırısı</h2>
<!-- /wp:heading -->

<!-- wp:list {"ordered":true} -->
<ol><li><strong>Github</strong>: 1.35 Tbps, 2018</li><li><strong>Occupy Central</strong>, Hong Kong: 500 Gbps, 2014</li><li><strong>CloudFlare</strong>: 400 Gbps, 2014</li><li><strong>Spamhaus</strong>: 300 Gbps, 2013</li><li><strong>Amerikan Bankaları</strong>: 60 Gbps, 2012</li></ol>
<!-- /wp:list -->

<!-- wp:heading -->
<h2>DDoS Saldırılarını Nasıl Takip Ederiz?</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Siber atakları takip etmek için bu konuda hizmet<strong> veren web siteleri</strong> mevcut. Bu haritalar bilgileri güvenlik şirketlerinin dünyadan elde ettikleri verilerden alırlar. Bunlar genellikte kaynak-hedef mantığına dayanarak harita üzerinde yapılan saldırıları görsel olarak sunmaktadırlar. Bu haritalar <strong>canlı</strong> gibi görünse de bir çoğu <strong>gecikmelidir</strong>.</p>
<!-- /wp:paragraph -->

<!-- wp:heading -->
<h2>En Çok Bilinen Canlı Siber Saldırı Haritaları</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p><strong>Siber saldırı</strong> haritaları anlık olarak nereden nereye bir saldırı olduğunu bize görsel olarak sunan canlı haritalardır. Çok bilinen bazı siber saldırı haritaları aşağıdaki gibidir:</p>
<!-- /wp:paragraph -->

<!-- wp:list {"ordered":true} -->
<ol><li><a aria-label=" (yeni sekmede açılır)" rel="noreferrer noopener" href="https://cybermap.kaspersky.com/" target="_blank">https://cybermap.kaspersky.com/ </a></li><li>https://www.deteque.com/live-threat-map/</li><li><a aria-label="https://threatmap.fortiguard.com/  (yeni sekmede açılır)" rel="noreferrer noopener" href="https://threatmap.fortiguard.com/" target="_blank">https://threatmap.fortiguard.com/</a></li><li>https://www.fireeye.com/cyber-map/threat-map.html</li><li><a aria-label=" (yeni sekmede açılır)" href="https://threatmap.bitdefender.com/" target="_blank" rel="noreferrer noopener">https://threatmap.bitdefender.com/</a></li><li><a href="https://comparite.ch/ransomwaremap" target="_blank" rel="noreferrer noopener">https://comparite.ch/ransomwaremap</a></li></ol>
<!-- /wp:list -->

<!-- wp:heading -->
<h2>Siber Saldırı Haritaları Nasıl Çalışır?</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Yukarıda örneğini verdiğimiz haritaların nasıl çalıştığını merak ettiniz mi? Dünya çapında organize olmuş büyük güvenlik şirketlerinin çeşitli <strong>ağlara</strong> yayılmış ve "<strong>honeypot</strong>" adı verilen sensörleri mevcuttur. Bunlar <strong>yazılım</strong> veya <strong>donanım</strong> olabilirler. Bu sensörlerden elde edilen bilgileri biz haritalar üzerinde görüyoruz.</p>
<!-- /wp:paragraph -->

<!-- wp:image {"id":4234} -->
<figure class="wp-block-image"><img src="/images/2019/10/siber-saldiri-haritasi.png" alt="" class="wp-image-4234"/><figcaption><a href="https://cybermap.kaspersky.com/">https://cybermap.kaspersky.com</a></figcaption></figure>
<!-- /wp:image -->

<!-- wp:heading {"level":3} -->
<h3>Honeypot Nedir?</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p><strong>Honeypot</strong>, gerçek bir yazılım veya donanım gibi görünen yapıların adıdır. Bilerek üzerinde açıklar bırakılıp <strong>saldırı</strong> için <strong>çekici</strong> hale getirilmişlerdir. Bu tür noktalara yapılan saldırıların sonuçları merkezde toplanıp özel <strong>ağlarda</strong> değiş tokuş edildiği gibi <strong><a href="https://burcinyazici.com/acik-veri-nedir-4194.html/">açık veri</a></strong> olarak da yayınlanmaktadır. Dünya çapındaki binlerce honeypot sayesinde nerelere saldırı yapıldığına dair verileri elde edebiliyoruz.</p>
<!-- /wp:paragraph -->

<!-- wp:heading -->
<h2>Son Söz</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Bu yazımda <strong>DDoS saldırısıyla ilgili kavramları</strong> ve sıkça sorulan sorulara değinmeye çalıştım. Eğer yazımı beğendiyseniz <strong>sosyal ortamlarda paylaşmanızı rica ederim.</strong></p>
<!-- /wp:paragraph -->