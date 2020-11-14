# II. Hafta Ödevleri

<h2> <strong>Yeni bir Github repository oluştururken, repomuza ekleyebileceğimiz lisanslar nelerdir, bu lisanslar arasındaki farklar nelerdir? </strong> </h2>
 
 <h3>1. MIT</h3>
 En yaygın kullanılan lisans türlerinden biridir. MIT tarafından yayınlandığı için adı da aynı şekilde MIT olarak geçer. Çok kullanışlıdır.
 
 <img src="https://miro.medium.com/max/1221/1*S6iMHfBXUJv07vyn5mo2RQ.png" alt="Image for post" title="Github’dan bir MIT Licence örneği">
 
 Örnek resimden de anlaşılabileceği gibi MIT licence sizi birçok konuda özgür kılar. Yani yazılıma ait kaynak kodu veya derlenmiş yazılımı istediğiniz gibi değiştirebilir, yayabilir, kullanabilirsiniz. Ticari olarak bile kullanımında herhangi bir sorun olmaz. Fakat sizi özgür kıldığı kadar yazılımı geliştirenleri de özgür kılar. Yani bir sorun çıkması durumunda geliştiriciler için herhangi bir yükümlülük söz konusu bile olamaz. Dolayısı ile MIT ile lisanslanmış bir yazılımı gönül rahatlığı ile kullanabilirsiniz. Sadece yazılımın buglardan temizlenmiş, yaygın bir kitle tarafından kullanılıyor olması sizi ilerde çıkabilecek yazılımsal sorunlar konusunda daha rahat ettirecektir.
Ayrıca MIT ile lisanslanmış bir yazılımı kullandığınızda, o yazılıma referans vermeniz gerekiyor.
 
 <h3>2. Apache Licence</h3>
Apache deyince aklıma direk özgür yazılım geliyor. Öğrencilik yıllarımdan hatırlıyorum Apacha Tomcat’i. Ön ekinde Apache bulunan bir çok yazılım, alanlarının en iyilerinden halen. Yazılım dünyasına katkıları yadsınamaz gerçekten.
Apache lisansının MIT’den bir farkı yok aslında. Sadece yazılımınızı dağıtırken kullandığınız Apache lisanslı ürünlerin lisanslarını da dağıtımınıza eklemeniz gerekiyor. Yani kısaca emeğe saygı konusu daha önemli tutulmuş bu lisansta.

 <h3>3. GNU General Public Licence</h3>
GNU lisansı da MIT gibi aynı şekilde size yazılımın kodlarına erişim konusunda herhangi bir kısıtlama getirmez. Fakat MIT lisansına göre kullanım açısından bazı kısıtlamalar getirir. Bu kısıtlamaların en önemlisi eğer yazılımında GNU lisansına sahip bir ürün kullandıysanız ve ürünü dağıtmaya başlarsanız sizin yazılımınız da GNU lisansına sahip olmalıdır. Yani yazılımın kendi geliştirdiğiniz kısımlarının da kaynak kodlarını paylaşmak zorundasınız. Dolayısı ile kaynak kodlarını paylaştığınız bir yazılımı ticari olarak satmak zor olacaktır.
Fakat MIT lisansı için aynı durum söz konusu değildir. MIT lisansına sahip bir ürünü kullanarak geliştirdiğiniz bir üründeki kendi kodlarınızı kimseyle paylaşmak zorunda değilsiniz. Yani kısaca GNU lisanslama konusunda kalıtsal davranır.
 
 
 
 <h2><strong>Merge - Squash-Rebase arasındaki farklar nelerdir?</strong></h2>
 <ul>
 <li>Merge commits: retains all of the commits in your branch and interleaves them with commits on the base branch</li>
    <img src="https://i.stack.imgur.com/3GuQE.png" alt="enter image description here">
 
 <li>Merge Squash: retains the changes but omits the individual commits from history</li>
    <img src="https://i.stack.imgur.com/Lh9LK.png" alt="enter image description here">
   
 <li>Rebase: This moves the entire feature branch to begin on the tip of the master branch, effectively incorporating all of the new commits in master</li>
    <img src="https://i.stack.imgur.com/1tGHe.png" alt="enter image description here">

 </ul>
 
 <h2><strong>Github Learning Lab'de First Day ve First Week kısımlarını bitiriniz.</strong></h2>
 <div style="color:blue"><strong>already finished...</strong></div>
 
 <h2><strong>Agile-Scrum-Kanban kavramlarını araştırınız</strong></h2>
   <h3>Agile metodunun tanımı</h3>

    Sprint, bir projenin belirli bir aşaması için ayrılan süredir. Sprintlerin süresi dolduğunda proje tamamlanmış sayılır. Ekip üyeleri arasında, gelişimin tatmin edici olup olmadığı konusunda anlaşmazlıklar olabilir;            ancak, projenin belirli bir aşamasında bu konuda daha fazla çalışma yapılmayacaktır. Projenin kalan aşamaları, kendi zaman dilimleri içinde geliştirilmeye devam edecektir.
 
   <h3>Kanban Nedir?</h3>

   Kanban, en basit haliyle, talepleri kapasite ile tartarak işi yönetmenin bir yoludur . Bu agile çerçeve, en yaygın olarak Toyota ile ilişkili olan yalın üretimden kaynaklanmaktadır.
     <img src="https://i1.wp.com/cdn-images-1.medium.com/max/1000/0*-WYIDPtZiUKBvKtx.png?w=750&amp;ssl=1" data-recalc-dims="1" class="jetpack-lazy-image jetpack-lazy-image--handled" data-lazy-loaded="1"  title="Kanban"> 
     Kanban, yazılım geliştirme konusunda popüler olmakla birlikte, işe alım, pazarlama projeleri ve liderlik girişimleri gibi diğer işletme alanlarıyla daha da popüler hale geliyor.

   Kanban’da proses etkinliğini belirlemek için kullanılan birincil ölçüm, döngü süresidir, ancak bu ölçüm herkes tarafından kullanılmaz.
   <h3>Scrum Nedir?</h3>
   
   Agile proje yönetim metodolojilerinden biridir. Kompleks yazılım süreçlerinin yönetilmesi için kullanılır. Bunu yaparken bütünü parçalayan; tekrara dayalı bir yöntem izler. Düzenli geri bildirim ve planlamalarla hedefe ulaşmayı sağlar. Bu anlamda ihtiyaca yönelik ve esnek bir yapısı vardır. Müşteri ihtiyacına göre şekillendiği için müşterinin geri bildirimine göre yapılanmayı sağlar. İletişim ve takım çalışması çok önemlidir. 3 temel prensip üzerine kurulmuştur;
<ul>
<li>Şeffaflık; Projenin ilerleyişi, sorunlar,gelişmeler herkes tarafından görülebilir olmalıdır.</li>
 <li>Denetleme; Projenin ilerleyişi düzenli olarak kontrol edilir.</li>
 <li>Uyarlama; Proje, yapılabilecek değişikliklere uyum sağlayabilmelidir.</li>
</ul>
     <img alt="Image for post" width="640" height="544" src="https://miro.medium.com/max/800/0*Yn_O2-N315idD9Du.jpg" sizes="640px">
 
 <h2><strong>Gang of Four(GOF) araştırınız.</strong></h2>
    <a href="https://www.javabrahman.com/design-patterns/gof-gang-four-design-patterns/" target="_blank">GOF hakkında bilgi için tıklayınız.</a>
 
 <h2><strong>Interface ve Abstract sınıflar arasındaki farklar nelerdir?</strong></h2>
  <h3>Abstract ile Interface Arasındaki Fark</h3>
   Abstract ile interface arasındaki fark; <a href="http://www.movsumov.com/author/admin/Ferid" target="_blank">Ferid Mövsümov</a> blogunda çok kapsamlı ve detaylı bir şekilde yazılmış. Bu farkları aşağıda alıntıladım.

   <ul>
   <li>Interfaceler çoklu kalıtımı sağlamaya yardımcı abstract classlar ise çoklu kalıtımı desteklemez.</li>
   <li>Interfacelerde metodların içerisini dolduramayız ama abstract classlarda doldurabiliriz Böylece bütün alt sınıfların belli bir özelliğe sahip olmasını sağlayabiliriz.</li>
   <li>Interface ile yapabildiğimiz herşeyi hatta daha fazlasını abstract classlar ile de yapabiliriz.</li>
   <li>Eğer türeteceğimiz classlarda belli başlı varsayılan özellikleri tekrar tekrar kopyala-yapıştır yapmak istemiyorsak o zaman abstract class kullanmamız gerekir. Çünkü            abstract classlarla bir metodu tüm alt classlarda varsayılan metod şeklinde tanımlayabiliriz ve alt classlarda bunları tekrar yazmamıza gerek kalmaz kalıtımla aktarılmış        olur.</li>
   <li>Kalıtım sağlamak istiyorsak abstract classlar kullanmamız gerekir.</li>
   <li>Abstract classları kullanmak hız açısından avantaj sağlar.</li>
   <li>Interface de yeni bir metod yazdığımız zaman bu interfaceden implement ettiğimiz tüm classlarda bu metodun içini tek tek doldurmak gerekiyor ancak abstract classlarda           durum farklıdır burada bir metod tanımlayıp içini doldurduğumuzda abstract sınıfımızdan türetilmiş bütün sınıflar bu özelliği kazanmış olur.</li>
   
   </ul>
  
