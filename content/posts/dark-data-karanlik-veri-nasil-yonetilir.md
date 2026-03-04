+++
title = "Dark Data (Karanlık Veri) Nasıl Yönetilir?"
date = "2015-08-01T01:16:10+03:00"
slug = "dark-data-karanlik-veri-nasil-yonetilir"
categories = ["Yazılım"]
tags = ["big data", "büyük veri", "dark data", "güvenlik", "karanlık veri"]
+++
Okumadıysanız öncelikle "<a href="https://burcinyazici.com/dark-data-karanlik-veri-nedir-neden-onemlidir-2642.html/">Dark Data (Karanlık Veri) Nedir? Neden Önemlidir?</a>" yazımı okumanızı tavsiye ederim. Yazıda<strong> karanlık veri</strong>nin nasıl ortaya çıktığından bahsetmiştim. Şimdi ise bu veriyi nasıl <strong>yöneteceğiz</strong> ona göz atalım.

<a href="https://burcinyazici.com/wp-content/uploads/2015/08/dark_data_manage.jpg"><img class="aligncenter size-full wp-image-2671" src="/images/2015/08/dark_data_manage.jpg" alt="dark_data_manage" width="259" height="194" /></a>

Bildiğiniz gibi yönetmemiz gereken büyük bir veri var. Gereksiz karanlık verinin oluşumu <strong>engellemek</strong> için başlıca önlemleri şöyle özetleyebiliriz:
<h2>Yeterince Analiz Yapın</h2>
"Şimdilik her bilgiyi alalım da sonra ayıklarız" veya "Biz herşeyi kaydedelim bakalım neleri kullanacağız..." gibi yaklaşımlarla <a href="https://burcinyazici.com/etiket/big-data/">büyük veri</a> analizlerine girmemek gerekiyor. Projemize yeterince <strong>vakit ayırıp</strong> bize gereken verileri dikkatlice <strong>süzerek</strong> analiz yapmalı ve sadece gereken verileri saklamalıyız. En başta alacağımız bu önlem ileride çok işimize yaracaktır. Haydi analize!
<h2>Verilerin Sadeleştirilmesi</h2>
Büyük verinin mutlaka "<strong>geçerlilik zamanı</strong>" vardır. Kaydedilen verileri <strong>ömürlerine</strong> göre sınıflandırarak; ömrünü tamamlamış olan verileri kalıcı olarak silebiliriz. Böylece gereksiz ve veri açığı doğurma riski bulunan eski verilerden kurtulabiliriz.
<h2>Verilerin Yedeklenmesi</h2>
Verilerin <strong>hacmi</strong> büyük ve<strong> üretim hızı</strong> yüksek olduğundan yedekleme çok önemli. Yedeklenmeyen bir yapı çok hızla <strong>performans</strong> sorunlarıyla karşı karşıya kalabilir. Halbuki yukarıda bahsettiğim sadeleştirmeden sonra hala daha durması gereken verileri yedekleyebiliriz. Fakat veri çok büyük olduğu için "<strong>bütün yedek</strong>" yöntemleri yerine "<strong>değişen verinin yedeklenmesi</strong>" mantığıyla çalışan modern yedekleme yöntemleri önerilmektedir. Aksi halde yedekleme işi kabusumuz olabilir! Yedekleme sonrası disk ihtiyacı daha rahat kontrol altında tutulabilir.
<h2>Verilerin Şifrelenmesi</h2>
Büyük verinin belki de en önemli tehlikesi "<strong>gizli</strong>" bilgilerin açığa çıkma tehlikesidir. Bunun önüne geçmek için verilerin "<strong>şifreli</strong>" olarak saklanması öneriliyor. Buna paralel olarak yedeklerimizi de<strong> şifreli tutacak yazılımlara</strong> yönelmek iyi bir çözüm olabilir. Şifreleme için "<strong>hassas</strong>" verinin en başta analiz edilmesi faydalı olacaktır. Yoksa sonradan başınıza bir dert açana kadar o veriyi hissetmezsiniz bile...

Yukarıda bahsettiğim önlemler "<strong>karanlık veri (dark data)</strong>" oluşumunu önceden azaltıcı etki sağlayacak ve yürüyen sisteminizi de karanlık verinin maliyetlerinden kurtaracaktır diye umuyorum.

Aydınlık veriler dileğiyle...

 