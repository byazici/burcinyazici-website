+++
title = "Firefox Optimizasyonu"
date = "2007-09-03T19:05:56+03:00"
slug = "firefox-optimizasyonu"
categories = ["Yazılım"]
+++
Günden güne popülerliğini artıran Firefox da "gelişmenin" verdiği zorlukları yaşıyor. Eklentilerin yapılabilmesi, temalar ve RSS desteği derken en son baktığımda bellekten 185MB lık yer kullanıyordu. Dolayısıyla tıkanmaya çatlamaya başladı. Eğer sizin benzer problemlerle karşılaşıyorsanız aşağıda hazırladığım listeyi uygulayarak daha hızlı bir Firefox elde edebilirsiniz.
<ol>
	<li>Öncelikle çok cafcaflı olmayan bir tema kullanın. Mümkünse öntanımlı temayı tercih edin.</li>
	<li>Kurduğunuz her yeni "eklenti" firefox'u yavaşlatabilir. Bu sebeple gerçekten gerekli olmayan eklentileri siliniz. Örneğin internete bağlanıp bilgi çeken bir eklenti tab geçişlerini yavaşlatır.</li>
	<li>Adres çubuğuna "<strong>about:config</strong>" yazarak gelen listede "c<strong>onfig.trim_on_minimize</strong>" değerini aratın. Eğer var ise; değerini "<strong>true</strong>" yapın. Eğer yok ise; <strong>sağ klik -&gt; "New -&gt; Boolean"</strong> yardımıyla "<strong>config.trim_on_minimize</strong>" değerini yaratın.  Değerini de "<strong>true</strong>" olarak seçin. Şimdi firefoxu tekrar başlatın. Bu ayar sayesinde firefox uygulamasını her aşağıya attığınızda hafıza kullanımı ayarlanır hale gelecektir. Bu çok performans sağlayan bir ayardır.</li>
	<li>Madde 3'teki yöntemle "<strong>network.http.pipelining</strong>" ve "<strong>network.http.proxy.pipelining</strong>" değerlerini "<strong>true</strong>" yapın, "<strong>network.http.pipelining.maxrequests</strong>" değerini ise "<strong>20</strong>" ye çıkarın. Bu sayede firefox network kullanımını daha etkili yapacak ve sayfa çizimi de hızlanacaktor.</li>
	<li>Manuel değişiklikler yapmak istemiyorsanı <strong>Mozdev.org</strong> tarafından geliştirilen Fasterfox 2.0.0 eklentisi bu tür optimizasyonları başarıluı bir şekilde yapıyor.</li>
</ol>