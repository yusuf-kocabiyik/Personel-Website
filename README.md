<h1><strong>Sprint Challenge: Kişisel Web Sitesi</strong></h1>

<h2><strong>Proje Açıklaması</strong></h2>
<p>
  Tebrikler, Frontend konularını tamamladın. Backend konularına geçmeden, şimdiye kadar öğrendiğin her konuyu kullanarak,
  kişisel web sayfası yapacaksın. Yaptığın siteyi kendi profil sayfanda da yayınlayacaksın. Bu senin Frontend konusunda ne seviyede olduğunu gösterecek.
</p>

<p>
  Workintech programını tamamladığında, görüştüğün şirketler yaptığın bu projeye de bakacaklar. O yüzden öğrendiğin her konuyu kullanmaya çalışman önemli.
  Projeni, tam çalışır durumda, gramer hatası olmayan bir proje yapmanı tavsiye ederiz.
</p>

<p>
  S12 içinde de Workintech eğitmenlerine, adeta bir teknik mülakattaymış gibi, bu projeyi sunmanı istiyoruz.
  Bu sunumda, 4 dk içerisinde, CSS'e döktüğün arayüzü ve de geliştirdiğin React JS sistemi anlatacaksın.
  İlk önce arayüzde nasıl bir kullanıcı deneyimi sunduğunu kısaca özetleyip, sonra altta kodların nasıl çalıştığını,
  nasıl bir veri akışı kurduğunu, açık bir şekilde ifade edebilmelisin.
</p>

<p>
  Kısaca: 4 dk içinde, önce arayüzü anlatıp, sonra kodun nasıl çalıştığını ifade edebilmelisin.
  Zaman kullanımı ve sunum tekniğin de değerlendirme kriterlerinde yer alıyor.
  Öncesinde, kendini videoya çekerek, sunum pratiği yapabilirsin.
</p>

<p>
  <strong>Not:</strong> Bu dökümanın en sonunda da, sunumda seni değerlendireceğimiz başlıkları bulabilirsin.
</p>

<h2><strong>Talimatlar</strong></h2>

<h3><strong>Görev 1: Proje Kurulumu</strong></h3>
<ul>
  <li><code>npm create vite@latest</code> komutuyla boş bir çalışma başlatabilirsin.</li>
  <li>Oluşturulan proje klasörüne gir.</li>
  <li><code>npm i</code> kullanarak, gerekli gördüğün kütüphaneleri projene ekleyebilirsin.</li>
</ul>

<p><strong>Örnek kütüphaneler:</strong></p>
<ul>
  <li>axios</li>
  <li>toastify</li>
  <li>tailwind</li>
  <li>cypress.io</li>
</ul>

<h3><strong>Görev 2: UI Tasarımı ve React JS Geliştirmeleri</strong></h3>
<p>
  Bu bağlantıda 3 farklı tasarım var. Hangisini beğenirsen onu kullanabilirsin.
  CSS stillerini ve HTML/JSX iskeletini geliştirirken, tasarımı bire bir yaptığından emin olana kadar kesinlikle özelleştirmemeni tavsiye ediyoruz.
</p>

<ul>
  <li>Tasarımdaki her bir section için ayrı bir component oluşturun.</li>
  <li>Her component'in style'ını ayarlayın.</li>
  <li>Verilerinizi kendi oluşturduğunuz verileri statik bir JSON dosyasından çekin.</li>
  <li>Dark Mode tasarımını da entegre edin.</li>
  <li>Türkçe-İngilizce içerik oluşturun.</li>
  <li>Responsive özelleştirmelerini yapın.</li>
  <li>Mobil ve tablet gibi farklı cihaz boyutları için, tasarımda biraz değişiklik yapabilirsin.</li>
  <li>Buralarda insiyatif kullanabilirsin.</li>
</ul>

<h3><strong>Önemli Notlar</strong></h3>
<ul>
  <li>Dil yönetiminde i18n gibi bir paket kullanmanızı <strong>asla</strong> istemiyoruz.</li>
  <li>useContext veya Redux kullanarak, veri yönetimi ve görüntüleme katmanının izole olduğu bir proje yapabildiğinizi görmek istiyoruz.</li>
  <li>Tasarımı birebir uygulamalısın.</li>
  <li>Resimleri ve projeleri kendi projelerinle güncelleyebilirsin.</li>
  <li>Yine de kesinlikle renkler ve yerleşimde değişiklik istemiyoruz.</li>
  <li>Sunumdan sonra dilersen sonrasında kendi portföyün için özelleştirebilirsin.</li>
  <li>
    Axios ile <code>https://reqres.in/api/workintech</code> (yereldeki data.js, POST) veya başka bir sahte API servisi ile
    dış kaynakla iletişim kurabildiğini gösterebilmelisin.
  </li>
  <li>Dış servis ile iletişim kurmayı projenin en sonuna atın. Önceliği en düşük kısımlardan biri bu.</li>
  <li>Daha detaylı dış servis kurmayı ileride öğreneceksiniz.</li>
  <li>
    <code>https://mockapi.io</code> veya benzeri bir servisle, projeniz bitmeden önce zaman kaybedip, asıl yapmanız gerekenleri
    öncelik sırasına göre yapmayıp, talimat dışına çıkarsanız düşük not alabilirsiniz.
  </li>
  <li>Data için reqres.in dışında bir servis kullanmaya zaman harcayanlar genelde yetiştiremiyor.</li>
  <li>Sunumdan sonra ayrıca isterseniz bakabilirsiniz.</li>
</ul>

<p>
  Böylece backende geçince de yönetim paneli yazıp, hem kod kalitesi hem yapabildiğiniz her şeyi tek projede birleştirmiş olacaksınız.
</p>

<h3><strong>Temsili Veri Akış Diagramı</strong></h3>
<p>Buraya veri akış diagramı görselini veya açıklamasını ekleyebilirsiniz.</p>

<img width="507" height="226" alt="ss" src="https://github.com/user-attachments/assets/134f6517-1ce2-4c87-8d47-75a9097ade56" />

<h3><strong>Görev 3: Yayına Almak</strong></h3>
<ul>
  <li>Projenizi vercel.com veya render.com üzerinde yayınlayın.</li>
  <li>Öncesinde geliştirdiğiniz bütün projelerin de Vercel'deki linklerini eklediğinize dikkat edin.</li>
</ul>

<h2><strong>Değerlendirme Kriterleri</strong></h2>

<h3><strong>1. Projesini zamanlamaya da dikkat ederek mülakattaymış gibi anlatabilir. (%4)</strong></h3>

<p><strong>1 - Beklentilerin Altında</strong></p>
<ul>
  <li>Demo ve kod sunumu için belirlenen zaman sınırlarına uymakta zorlanır.</li>
  <li>Demo, projenin çalışır durumunu etkili şekilde göstermez.</li>
  <li>Kodun önemli bölümlerini açıklamakta zorlanır.</li>
  <li>Temel algoritma ve tasarım kararlarını açıklayamaz veya yanlış bilgi verir.</li>
</ul>

<p><strong>2 - Gereklilikleri Karşılar</strong></p>
<ul>
  <li>Belirlenen süreler içinde demo ve kod sunumunu gerçekleştirir.</li>
  <li>Projenin ana özelliklerini ve işlevselliğini başarılı şekilde gösterir.</li>
  <li>Kodun önemli bölümlerini ve nasıl çalıştığını açıklayabilir.</li>
</ul>

<p><strong>3 - Gerekliliklerin Üzerinde</strong></p>
<ul>
  <li>Zamanı mükemmel şekilde yönetir.</li>
  <li>Demo, kullanıcı deneyimini ve ana özellikleri etkileyici biçimde gösterir.</li>
  <li>Kodun kritik bölümlerini derinlemesine ve açık şekilde açıklar.</li>
  <li>İleri seviye teknikler, tasarım desenleri ve optimizasyon stratejilerinden bahseder.</li>
</ul>

<h3><strong>2. Görseldeki bir tasarımı anlamlı bir HTML yapısı ve doğru semantik tagler kullanarak, hizalamalara ve CSS özelliklerine dikkat ederek koda dökebilir. (%12)</strong></h3>

<p><strong>1 - Beklentilerin Altında</strong></p>
<ul>
  <li>Semantik tagler yeterince veya hiç kullanılmamıştır.</li>
  <li>HTML yapısı düzensiz veya anlamsızdır.</li>
  <li>CSS kullanımı çok basit veya hatalıdır.</li>
  <li>Hizalama tasarıma uygun değildir.</li>
</ul>

<p><strong>2 - Gereklilikleri Karşılar</strong></p>
<ul>
  <li>Anlamlı ve mantıklı bir HTML yapısı kullanılmıştır.</li>
  <li>Semantik tagler doğru yerlerde kullanılmıştır.</li>
  <li>Renkler, fontlar, boşluklar ve hizalama tasarıma uygundur.</li>
</ul>

<p><strong>3 - Gerekliliklerin Üzerinde</strong></p>
<ul>
  <li>HTML yapısı semantik anlamda çok güçlüdür.</li>
  <li>Erişilebilirlik ve SEO'ya katkı sağlayacak şekilde optimize edilmiştir.</li>
  <li>ARIA roller ve HTML5 özellikleri kullanılmış olabilir.</li>
  <li>CSS3, flexbox, grid, animasyonlar ve ileri düzey tasarım teknikleri etkili şekilde uygulanmıştır.</li>
</ul>

<h3><strong>3. Yaptığı sayfayı responsive hale getirebilir, karanlık tema ekleyebilir. (%15)</strong></h3>

<p><strong>1 - Beklentilerin Altında</strong></p>
<ul>
  <li>Sayfa farklı ekran boyutlarında düzgün görüntülenmez.</li>
  <li>Responsive yapı eksiktir veya hatalıdır.</li>
  <li>Mobil ve tablet deneyimi zayıftır.</li>
  <li>Karanlık tema hiç yoktur veya yetersizdir.</li>
</ul>

<p><strong>2 - Gereklilikleri Karşılar</strong></p>
<ul>
  <li>Sayfa çoğu cihaz ve ekran boyutunda düzgün görüntülenir.</li>
  <li>İçerikler ekran boyutlarına uyum sağlar.</li>
  <li>Kullanıcı deneyimi iyi düzeydedir.</li>
  <li>Karanlık tema temel düzeyde tutarlı şekilde entegre edilmiştir.</li>
</ul>

<p><strong>3 - Gerekliliklerin Üzerinde</strong></p>
<ul>
  <li>Tüm cihaz ve ekran boyutlarında çok iyi görüntülenir.</li>
  <li>Performans ve erişilebilirlik optimize edilmiştir.</li>
  <li>Karanlık tema hem görsel hem mimari olarak güçlü şekilde uygulanmıştır.</li>
  <li>Kullanıcı tercihine bağlı tema değişimi desteklenir.</li>
</ul>

<h3><strong>4. Kodu componentlere bölebilir, bu componentları map metodu ile kullanabilir. (%7)</strong></h3>

<p><strong>1 - Beklentilerin Altında</strong></p>
<ul>
  <li>Kod yeterince bileşenlere ayrılmamıştır.</li>
  <li><code>map</code> metodu yanlış kullanılmıştır veya hiç kullanılmamıştır.</li>
  <li>Props ve state yönetimi zayıftır.</li>
</ul>

<p><strong>2 - Gereklilikleri Karşılar</strong></p>
<ul>
  <li>Kod mantıklı bileşenlere ayrılmıştır.</li>
  <li><code>map</code> metodu listeleri render etmek için doğru kullanılmıştır.</li>
  <li>Veri akışı props ve state ile uygun şekilde yönetilmiştir.</li>
</ul>

<p><strong>3 - Gerekliliklerin Üzerinde</strong></p>
<ul>
  <li>Kod yeniden kullanılabilir bileşenlere çok iyi ayrılmıştır.</li>
  <li><code>map</code> ile karmaşık veri yapıları etkili şekilde render edilmiştir.</li>
  <li><code>key</code> gibi ileri düzey kavramlar doğru kullanılmıştır.</li>
  <li>Global state yönetimi ile veri akışı daha etkili hale getirilmiştir.</li>
</ul>

<h3><strong>5. State, props ve veri akışı gibi React'ın temel çalışma prensiplerini anlayabilir ve kullanabilir. (%8)</strong></h3>

<p><strong>1 - Beklentilerin Altında</strong></p>
<ul>
  <li>State ve props kavramları karıştırılmaktadır.</li>
  <li>State güncellemeleri doğru yönetilememektedir.</li>
  <li>Tek yönlü veri akışı iyi anlaşılmamıştır.</li>
</ul>

<p><strong>2 - Gereklilikleri Karşılar</strong></p>
<ul>
  <li>State'in ne olduğu ve nasıl yönetileceği anlaşılmıştır.</li>
  <li>Props ile veri aktarımı doğru yapılmaktadır.</li>
  <li>Top-down veri akışı doğru uygulanmaktadır.</li>
</ul>

<p><strong>3 - Gerekliliklerin Üzerinde</strong></p>
<ul>
  <li>useState, useReducer gibi yapılar etkili kullanılır.</li>
  <li>Immutability ve performans optimizasyonu bilinmektedir.</li>
  <li>Context API, Redux, React Query gibi yapılarla uygulama genelinde veri akışı yönetilebilir.</li>
</ul>

<h3><strong>6. Uzak bir veri kaynağından (API) axios yardımıyla veri alabilir ve bu veriyi kullanabilir. (%7)</strong></h3>

<p><strong>1 - Beklentilerin Altında</strong></p>
<ul>
  <li>Axios kullanımı eksik veya hatalıdır.</li>
  <li>Hata yakalama ve istek yönetimi yetersizdir.</li>
  <li>Veri UI'da yeterince iyi gösterilmemiştir.</li>
</ul>

<p><strong>2 - Gereklilikleri Karşılar</strong></p>
<ul>
  <li>Axios ile GET ve POST istekleri yapılabilir.</li>
  <li>Veri uygun şekilde işlenip kullanıcıya sunulur.</li>
  <li>Yüklenme, hata veya başarı durumlarından en az biri kullanıcıya gösterilir.</li>
</ul>

<p><strong>3 - Gerekliliklerin Üzerinde</strong></p>
<ul>
  <li>Merkezi Axios instance oluşturulmuştur.</li>
  <li>İleri seviye veri işleme ve soyutlama yapılmıştır.</li>
  <li>Kapsamlı hata yönetimi ve performans iyileştirmeleri uygulanmıştır.</li>
</ul>

<h3><strong>7. Yazılımcı ve/veya kullanıcı deneyimini iyileştirmek için Tailwindcss, react-toastify gibi ek kütüphaneler ekleyebilir ve kullanabilir. (%10)</strong></h3>

<p><strong>1 - Beklentilerin Altında</strong></p>
<ul>
  <li>Kütüphaneler eksik veya hatalı entegre edilmiştir.</li>
  <li>Kullanımları düzensiz, etkisiz veya hatalıdır.</li>
  <li>Performans ya da uyumluluk sorunları olabilir.</li>
</ul>

<p><strong>2 - Gereklilikleri Karşılar</strong></p>
<ul>
  <li>Gerekli kütüphaneler doğru şekilde projeye eklenmiştir.</li>
  <li>Tailwind CSS ve React-Toastify uygun şekilde kullanılmıştır.</li>
  <li>Kütüphaneler uygulamayla uyum içinde çalışır.</li>
</ul>

<p><strong>3 - Gerekliliklerin Üzerinde</strong></p>
<ul>
  <li>Kütüphanelerin gelişmiş özellikleri etkili şekilde kullanılmıştır.</li>
  <li>Özelleştirme ve kullanıcı deneyimi açısından güçlü entegrasyon yapılmıştır.</li>
  <li>Performans optimizasyonu gözetilmiştir.</li>
</ul>

<h3><strong>8. LocalStorage kullanarak site dili, renk teması gibi tercihleri saklayabilir ve kullanabilir. (%8)</strong></h3>

<p><strong>1 - Beklentilerin Altında</strong></p>
<ul>
  <li>LocalStorage kullanımı yüzeyseldir.</li>
  <li>Kullanıcı tercihleri tutarlı şekilde saklanmaz veya uygulanmaz.</li>
  <li>Kullanıcı deneyimine anlamlı katkı sağlamaz.</li>
</ul>

<p><strong>2 - Gereklilikleri Karşılar</strong></p>
<ul>
  <li>Site dili ve tema gibi tercihler LocalStorage ile saklanır.</li>
  <li>Uygulama açıldığında bu tercihler okunur ve uygulanır.</li>
  <li>Kullanıcı deneyimini olumlu etkiler.</li>
</ul>

<p><strong>3 - Gerekliliklerin Üzerinde</strong></p>
<ul>
  <li>Custom hook ile LocalStorage kullanımı soyutlanmıştır.</li>
  <li>Tercihler anlık güncellenir ve kaydedilir.</li>
  <li>Performans dikkate alınarak yapı kurulmuştur.</li>
</ul>

<h3><strong>9. Uygulama verilerini contextApi, Redux veya benzeri bir Global Store kullanarak yönetebilir. (%25)</strong></h3>

<p><strong>1 - Beklentilerin Altında</strong></p>
<ul>
  <li>Redux veya Context API hiç kullanılmamış ya da yanlış kullanılmıştır.</li>
  <li>Dil ve tema gibi global tercihler lokal state'lerde dağınık tutulmaktadır.</li>
  <li>Mantık hataları kullanıcı deneyimini bozmaktadır.</li>
</ul>

<p><strong>2 - Gereklilikleri Karşılar</strong></p>
<ul>
  <li>Global store, uygulama verilerini yönetmek için etkili şekilde kullanılmıştır.</li>
  <li>Dil seçimi ve tema değişikliği global yapı üzerinden yönetilmektedir.</li>
  <li>Veri akışı mantıklı ve anlaşılırdır.</li>
</ul>

<p><strong>3 - Gerekliliklerin Üzerinde</strong></p>
<ul>
  <li>Global state yönetimi çok iyi yapılandırılmıştır.</li>
  <li>Kullanıcı tercihleri uygulama genelinde anında yansıtılır.</li>
  <li>Performans, erişilebilirlik ve genişletilebilirlik gözetilmiştir.</li>
</ul>

<h3><strong>10. Yaptığı projeleri vercel.com, render.com gibi bir servis kullanarak yayınlayabilir. (%4)</strong></h3>

<p><strong>1 - Beklentilerin Altında</strong></p>
<ul>
  <li>Yayınlama sürecini tam anlayamamıştır.</li>
  <li>Çok az sayıda yayınlanmış proje vardır.</li>
  <li>Hata çözme ve konfigürasyon bilgisi yetersizdir.</li>
</ul>

<p><strong>2 - Gereklilikleri Karşılar</strong></p>
<ul>
  <li>Projelerini Vercel veya Render üzerinde yayınlayabilir.</li>
  <li>Temel konfigürasyonları doğru yapabilir.</li>
  <li>Yayınlama hatalarını çözebilir.</li>
</ul>

<p><strong>3 - Gerekliliklerin Üzerinde</strong></p>
<ul>
  <li>Özel domain, CI/CD, branch yapısı gibi ileri düzey yayınlama özelliklerini kullanabilir.</li>
  <li>Portfolyo + 3 veya daha fazla proje yayınlamıştır.</li>
  <li>Deploy öncesi test ve akış yönetimi kurulmuştur.</li>
</ul>

<h2><strong>Soru-Cevap</strong></h2>
<ul>
  <li>useState'ten Redux Store'a ne zaman geçmek gerekir?</li>
  <li>useContext ile state/store farklı mıdır?</li>
</ul>

<h2><strong>Açık Uçlu Sorular</strong></h2>
<p>Bu bölümde proje, mimari tercihleri ve geliştirme yaklaşımı hakkında ek sorular yer alabilir.</p>
