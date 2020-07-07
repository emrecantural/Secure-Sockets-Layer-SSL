İnternet kullanımının yoğun olduğu günümüzde, SSL (Secure Sockets Layer) kavramı ile defalarca kez karşılıyoruz. Çoğu kullanıcının dikkat bile etmediği bu kavram, özellikle web sitesi sahipleri için daha tanınır bir kavram. Çünkü, eğer güvenilir bir web siteniz olsun istiyorsanız ve bunu yanında bu güvenilirliği kullanıcılarınıza da kanıtlamak istiyorsanız, SSL ile daha yakın olunur. Bu gibi durumlarda SSL sertifikasyonlarına başvurulur. Bu araştırma ile SSL kavramının ne olduğu detaylıca anlatılacaktır. Bunun yanında SSL ile ilgili kavramların ve bunun yanında diğer yan kavramların anlaşılması bu araştırmanın amaçları içerisindedir. 
## 1.	SSL Nedir
SSL, dilimize “Güvenli Giriş Katmanı” olarak çevrilmiştir. Kullanılmasındaki temel amaç, kullanıcı ile kullanılan web sitesi arasında güvenli bir ilişki kurulmasıdır. Kullanılış olarak SSL ile korunan siteler üzerinde girilen kredi kartı, şifre ve kimlik gibi bilgilerin üçüncü kişilerce asla erişilemez olmasını sağlar. Bu nedenle özellikle alışveriş siteleri için büyük önem taşımaktadır [1]. 

Çalışma mantığı ile ele aldığımızda sistemin kullanılır olması için server desteğine ihtiyaç duyulmaktadır. Server desteği sağlayan sunucuda bir şifre yani bir anahtar ve bunun yanında da bir sertifika olmalıdır [1,2]. 

SSL temelde standart bir algoritma üzerine kurulmuştur. SSL, sitede iletilen dokümanların ve yapılan alışveriş gibi işlemlerin tarih ve saatlerini kaydeder. Böylece yapılan işlemi doğrular ve doküman arşivinin oluşumuna katkı sağlamış olur. Bunların dışında, SSL ile veriyi gönderen ile alan arasında güvenli koridorun varlığı doğrulanmış olur. İşlemler sadece bu doğrulamanın mümkün olduğu durumlarda gerçekleştirilir. SSL sertifikasyonu ile web sitelerinde http protokolü yerine daha güvenli olan https protokolü kullanılmaya başlanmıştır [1,2]. 
### 1.1.	SSL Nasıl Çalışır?
Daha önce de bahsedildiği gibi SSL siteminin çalışması anahtar mantığına dayanır. Çalışma, sağlanan kodlama sisteminin varlığında mümkündür. Bu kodlama sisteminde public key ve private key olmak üzere iki adet anahtar bulunmaktadır. Bu anahtarların uyumu en üst düzeydedir. Anahtarlardan birinin kilitlediği bir veri ancak ikinci anahtar tarafından açılabilir [2,3]. 

Anahtarlardan biri her zaman için site tarafındır. Diğer şifre ise bağlantı kurulmak istenilen kişilere gönderilir. Bu sayede yönetici ve kullanıcı arasında çift taraflı güvenlik sağlanmış olur. Kullanılan SSL türüne göre 40 bit ile 128 bit arasında bir değerde şifreleme kullanılır [3].

## 2.	SSL Sertifikaları
SSL kullanabilmek için sertifikaya gerek duyulur. Sertifika içerisinde kullanacak kuruma ait bilgiler ve sertifika sahibinin açık anahtarı barındırılır. Bunun yanında sertifika veren kuruma ait Elektronik Sertifika Hizmet Sağlayıcısı elektronik imzası da bu sertifika ile belirtilir. 
SSL kullanımı için gerekli sertifika karşılığı ücrete tabidir. Bunun yanında hosting firması ile işler yürütülüyorsa firma size ücretsiz olarak bu servisi sağlayabilir. Dünya çapında birçok site kolay yoldan SSL sertifikasyonu yapmaktadır. 
### 2.1.	Sertifika Türleri
#### 2.1.1.	Domain Tipine Göre SSL Sertifikaları


| Sertifika |Özellikleri|
| ------ | ------ |
|Standart SSL Sertifikaları|Standart SSL sadece tek bir adet domain için SSL verilen sertifikalardır.|
|Multi-Domain SSL Sertifikaları|Multi yapılarda birden fazla domain için SSL verilmesi sağlanır. Genelde bir ana domain yanında farklı iki domaini barındıracak şekilde üç domain için kullanım sağlanır. Bunun yanında, ek ödemeler ile ek domainler de dahil edilebilir.|
|Wildcard SSL Sertifikaları|Sertifikaların kullanıldığı ana domain yanında tüm subdomainlerin de sertifikaya dahil edilmesini sağlayan sertifika tipidir. Wildcard SSL içerişinde subdomain bilimiti bulunmaksızın sertifikasyon yapılır.|

#### 2.1.2.	Doğrulama Türüne Göre SSL Sertifikaları

| Sertifika |Özellikleri|
| ------ | ------ |
|Domain Validation SSL|Doğrulama düzeyi en düşük olan SSL türüdür. Sadece sunucunun adını doğrular.|
|Organizational Validation SSL|İçerisinde alan adına sahip firmanın bilgilerini içerir. Bu bilgiler sunucu adına bağlı olarak sertifikayı üreten firma tarafından kontrol edilir. SSL alınırken başvuruda bulunan kişi ve şirket arasındaki bağlar doğrulanır. Bunun yanında kullanılan domain ve verilen bilgilerin doğruluğu kanıtlanmalıdır. DV’ye göre daha güvenlidir.|
|Extended Validation SSL| Güvenilirliği en yüksek olan sertifikadır. Sertifika sahibi firmanın hukuki ve ticari varlığı da incelemeye katılır.| 


### KAYNAKÇA

[1] Freier, A., Karlton, P., & Kocher, P. (2011). The secure sockets layer (SSL) protocol version 3.0. IETF, 3, 1-67.

[2] Freed, M., & Gannesan, E. (2006). U.S. Patent No. 7,149,892. Washington, DC: U.S. Patent and Trademark Office.

[3]   Chou, W. (2002). Inside SSL: the secure sockets layer protocol. IT professional, 4(4), 47-

[4] Thayer, W., Reilly, K., & Jilg, J. (2010). U.S. Patent No. 7,702,902. Washington, DC: U.S. Patent and Trademark Office.
