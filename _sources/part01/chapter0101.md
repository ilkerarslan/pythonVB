# Bilgisayarlar ve Programlama

Bundan 20 yıl önce çok az sayıda insanın kullandığı bir araç olan bilgisayarlar önce her eve sonra da hepimizin her anına girdi. Peki sürekli kullandığımız, kullanmak bir yana artık neredeyse 24 saat birlikte onunla yaşadığımız bilgisayar nedir? Klasik bir giriş yaparak kelime anlamıyla başlayalım. Türk Dil Kurumu, bilgisayarı aşağıdaki gibi tanımlıyor:

> Çok sayıda aritmetiksel veya mantıksal işlemlerden oluşan bir işi, önceden verilmiş bir programa göre yapıp sonuçlandıran elektronik araç, elektronik beyin.

Cambridge Sözlüğünün tanımı ise aşağıdaki gibi:

> Kelime, sayı ve resimleri saklama, düzenleme ve bulmak, hesaplama yapmak ve diğer makineleri kontrol etmek için kullanılan bir elektronik makine.

Son olarak Oxford Sözlüğünün tanımı ise aşağıdaki gibi:

> Bilgiyi (veriyi) belirli bir şekilde alarak önceden belirlenmiş fakat değişebilir bir dizi işlemden (program) geçiren ve bunun sonucunda da bilgi veya sinyal üretebilen elektronik alet.

Basitçe özetleyecek olursak bilgisayarlar, verileri okuyabilen, bunlar üzerinde önceden tanımlanmış işlemleri gerçekleştiren ve sonucunda da istenen bir çıktıyı üreten aletlerdir diyebiliriz. Burada, veri sayısal bir tablo olabileceği gibi, bir komut, fotoğraf, video, sıcaklık gibi çok farklı girdiler olabilir. Bu girdileri kullanıp işlemeye yarayan, bir başka deyişle bilgisayara ne yapması gerektiğini söyleyen talimatlar dizisine ise program deniyor. Bilgisayar bu talimatları takip ederek istenen çıktıyı üretir. Bilgisayarların istenen görevi yerine getirmesi için kullandığımız dile ise program ya da programlama dili diyoruz. Bu açıdan baktığımızda basit bir hesap makinesi de aslında bir bilgisayardır. Hesap makinesine iki veya daha fazla sayıyı girip bu sayılarla hangi işlemi yapması gerektiğini söyleriz. Bir mikro dalga fırınına yiyeceği koyup 30 dakikaya kurduğumuz zaman, fırın, 30 dakika boyunca çalışıp sonra durması gerektiğini anlar. Bu açıdan bakıldığında, kullandığımız akıllı telefonlar, akıllı saatler, trafik ışıkları özel birer bilgisayardır.

Yukarıda yer alan son tanımdaki diğer bir önemli nokta da programın değişebilir olmasıdır. Bir bilgisayar algıladığı, okuduğu verilerle ne yapması gerektiğini programlar ile iletilen talimatlar sayesinde bilir. Aslında bir bilgisayar, kendisine verilen talimatı adım adım izlemekten başka bir şey yapmaz. Bu talimatları, yani programı değiştirdiğimiz zaman bilgisayar farklı adımlar takip edecek ve büyük ihtimalle farklı çıktılar üretecektir. Bu da genel anlamıyla kullandığımız ve anladığımız bilgisayarı, hesap makinesi, mikro dalga fırın ya da trafik ışığı gibi özel bilgisayarlardan ayıran noktadır {cite}`zelle2009`  (J. Zelle Python Programming: An Introduction to Computer Science, Franklin Beedle & Associates, 2009). 

Günümüzde artık bilgisayarlar, kullandığımız telefonlardan kolumuzdaki saatlere, otomobil, gemi ve uçaklardan, televizyonlara kadar her yerde karşımızdalar. 

## Bilgisayarların Tarihi

Kitabımız bilgisayar tarihi kitabı değil ancak bilgisayarlar ve programcılık ile ilgilenen herkesin bilgisayarın gelişimi konusunda genel de olsa bilgi sahibi olması gerektiğini düşünüyorum. Bizler, zamanımızın neredeyse tümünü bilgisayarlarla geçirdiğimiz için bilgisayarsız bir hayatı düşünemez hale geldik. Buna karşın, bilgisayarlar oldukça uzun bir tarihsel gelişim sürecinden sonra bugünkü hale geldiler. Bu bölümde bilgisayar tarihini çok genel olarak anlatıyoruz. Konuya ilgi duyan okuyucular bu konudaki kaynaklara göz atabilirler (örneğin Ceruzzi, A History of Modern Computing, MIT Press, 2003; Levy, Hackers: Heroes of Computer Revolution, O'Reilly Media, 2010; Aspray, A History of Modern Computing, MIT Press, 2003).

Tarihte bilinen ilk hesap makinesinin, Asya'da icat edilen abaküs olduğu kabul edilir. Basit toplama ve çıkarma işlemleri yapmak için kullanılan abaküs Orta Çağın sonlarına kadar kullanılmıştır. 

Fransız filozof ve matematikçi Blaise Pascal’ın 1642 yılında icat ettiği ve Pascaline ismini verdiği hesap makinesi, sekiz basamağa kadar toplama işlemi yapılmasında kullanılabiliyordu.

:::{figure-md} pascal-fig
<img src="figures/pascaline.jpg" alt="pascaline">

Blaise Pascal tarafından icat edilen Pascaline isimli hesap makinesi ([Kaynak](https://upload.wikimedia.org/wikipedia/commons/7/78/Pascaline-CnAM_823-1-IMG_1506-black.jpg))
:::

Alman matematikçi ve filozof Leibniz, 1673 yılında, Pascal'ın makinesini daha da geliştirerek çarpma ve bölme işlemlerini de yapabilir hale getirmiştir. Leibniz aynı zamanda ikili sayma sisteminin de savunucusuydu. İkili sayma sistemi, makineler ve bilgisayarlar için ideal olarak kabul edilegelen sistemdir. Bir makine, anahtarlardan oluşur. Bir anahtar da açık ve kapalı olmak üzere iki halde bulunabilir. Bu iki hal en iyi sıfır ve bir ile temsil edilir. Leibniz’in ölümünden sonra onun fikirleri İngiliz matematikçi George Boole tarafından geliştirilmiş ve Boole Cebiri oluşturulmuştur. Bugün, tüm programlama dillerinde yer alan ve True, False (Doğru, Yanlış ya da 1, 0) değerlerinden birini alabilen Boole ya da Boolean türü değişken, ismini George Boole’dan almıştır.  

:::{figure-md} leibniz-fig
<img src="figures/leibniz.jpg" alt="leibniz">

Leibniz tarafından geliştirilen hesap makinesi ([Kaynak](https://commons.wikimedia.org/wiki/File:Rechenmaschine_von_Leibniz_(Nachbau)_04.jpg))
:::

1819 yılında bir Fransız dokumacı Joseph Jacquard, dokuma aletlerinde delikli kartlar kullanmak suretiyle iğnelerin istenen sırayı izlemesini ve kumaşın istenilen renk ve desene sahip olmasını sağladı. Kartlardaki deliklerin yerleri değiştirilerek kumaşın renk ve desenleri de değiştirilebiliyordu. Yirminci yüzyılda geliştirilen ilk bilgisayarlar da delikli kartlar kullanılarak programlanıyordu. Bu açıdan, Joseph Jacquard'ın icadı bilgisayarların gelişimi için son derece önemli bir adım olmuştur (Malik, C++ Programming Program Design Including Data Structures, Course Technology Cengage Learning, 2011).

İngiliz matematikçi Charles Babbage, bugünkü anlamdaki bilgisayarları ilk kez tasarlayan kişi olarak kabul edilmekle birlikte, Babbage, tasarladığı bilgisayarları hayata geçirememiştir. Babbage’ın tasarladığı bilgisayarlarda girdi, hafıza, işlemci ve çıktı üniteleri yer almaktaydı. Bu nedenle Babbage’ın çalışma defterleri 1930’larda bulunduğunda, Babbage bilgisayarın babası olarak nitelendirildi. Babbage’ın yapmayı hayal ettiği makine ancak 1991 yılında Londra Bilim Müzesindeki bir ekibin altı yıllık çalışması sonunda hayata geçirilebildi. Tamamen Babbage’ın zamanındaki teknik imkanlarla yapılan makine doğru bir şekilde çalıştı ve onun fikirlerinin doğruluğunu ortaya koydu. 

Bell laboratuvarlarında çalışan George Stibitz, 1937 yılında röleleri kullanarak Boolean Mantığı ile çalışan basit bir düzenek yaptı ve bu devre 1940 yılında yine George Stibitz tarafından yapılan bir hesap makinesinde kullanıldı.

İkinci Dünya Savaşı dönemine denk gelen izleyen yıllarda bilgisayar çalışmaları, Amerikan ve İngiliz ordularının, Almanların meşhur Enigma şifrelerinin kırılması ve topçu atışlarının hesaplanması çalışmaları doğrultusunda gelişti. Bu dönemde Almanlar da 22-bitlik işlemler yapabilen ve aerodinamik hesaplamalarda kullanılan Zuse Z3 bilgisayarını geliştirmişlerdi. 

Yirminci yüzyılda bilgisayarın gelişimi açısından en büyük aşama 1947 yılında ENIAC (Electrical Numerical Integrator and Calculator) isimli bilgisayarın yapılması olmuştur. Bunun öncesinde 1942 yılında John V. Atanasoff ve Clifford Berry tarafından Atanasoff-Berry Bilgisayarı ilk elektronik bilgisayar olarak kabul edilebilir. İngiliz Mühendis Tommy Flowers tarafından yapılan Colossus isimli bilgisayar da önemli bir adım olarak kabul edilir. Nazilerin şifrelerinin kırılmasında kullanılan bu bilgisayar 2500 vakum tüpü ile çalışıyordu. Bu bilgisayar Nazilerin mesajlarının kırılma süresini birkaç haftadan birkaç saate indirmişti.

John W. Mauchly ve J. Presper Eckert tarafından yapılan ENIAC, yaklaşık 18.000 vakum tüpü ile çalışıyordu, bir oda büyüklüğünde ve 30 ton ağırlığındaydı. Önceki hesaplama makinelerinden farklı olarak 10 basamağa kadar sayıları hafızasında tutabiliyordu. ENIAC, anahtarlar ve kablolar ile programlanıyor ve 10 basamaklı iki sayıyı 2800 mikrosaniyede çarpabiliyordu. Programlaması çok zor olduğu için önce kâğıda yazılan programlar daha sonra günlerce süren uğraşlarla bilgisayara aktarılıyordu. 

Manchester Üniversitesinde 1948 yılında geliştirilen ve “Manchester Bebeği” ismi verilen bilgisayar, belleğe sahip ve hafızasında program saklanabilen ilk bilgisayardı. Frederic Williams, Tom Kilburn ve Geoff Toothill tarafından geliştirilen bu bilgisayar, yine Kilburn tarafından yazılmış olan 17 satırlık bir programı hafızasında saklayıp çalıştırabiliyordu. Yine aynı yıl IBM tarafından geliştirilen SSEC (Selective Sequence Electronic Calculator) isimli bilgisayar bir saniyede 50 adet 14 basamaklı iki sayının çarpımı işlemini gerçekleştirebiliyordu. Bu bilgisayar 1969’da Aya giden uzay mekiği Apollo’nun uçuş yörüngesinin hesaplanmasında da kullanıldı.

1950’lerden sonra Bell Laboratuvarları tarafından geliştirilen transistörler, vakum tüplerinin yerini almaya başladı. Bu gelişme bilgisayarların çok daha hızlı çalışmasına olanak verdi.  1951 yılında UNIVAC 1 (Universal Automatic Computer) isimli ilk ticari amaçlı bilgisayar tanıtıldı. Yine bu dönemde IBM (International Business Machine), tarafından üretilen 650 ve 700 model bilgisayarlar ilk seri üretim bilgisayarlardır. 

Entegre devrelerin icadıyla birlikte 1960’lardan itibaren üçüncü nesil bilgisayarlar üretilmeye ve kullanılmaya başlandı. Bu gelişme sayesinde bilgisayarlar çok daha küçük, güçlü ve birden fazla programı aynı anda çalıştırabilir hale geldiler. Intel ilk mikroişlemcisini 1971 yılında tanıttı. İlk Intel mikroişlemcisi olan Intel 4004, saniyede 90.000 işlem gerçekleştirebiliyordu.

1980 yılında Microsoft Disk Operating System (MSDOS) tanıtıldı. İzleyen yılda IBM ev ve ofis kullanımı için ilk kişisel bilgisayarı tanıttı. 1984 yılında Apple Macintosh, grafik ara yüzlü ilk bilgisayarı tanıttı. Bunu da 90’larda Microsoft tarafından sunulan Windows işletim sistemi izledi.

:::{figure-md} eniac-fig
<img src="figures/eniac.jpg" alt="eniac">

ENIAC, bir oda büyüklüğündeydi. Bozuk bir vakum tüpünü bulmak ve değiştirmek 18000 vakum tüpünü tek tek kontrol etmek anlamına geliyordu.
:::

Doksanlı yıllardan sonra bilgisayarların gelişimi ve kullanımı giderek ivmelenen bir seyir izledi. Bu dönemde bilgisayarların giderek güçlenip hızlanırken aynı zamanda küçüldüğüne tanık olduk. Masa üstü bilgisayarların yerini diz üstü ve tablet bilgisayarlar aldı. İnternet kullanımının yaygınlaşması daha önceden sadece bilgisayarlar tarafından gerçekleştirilebilen işlemleri yapabilen akıllı telefonların kullanımını hızlandırdı. 

Günümüzde neredeyse kredi kartı büyüklüğündeki Arduino ve Raspberry Pi bilgisayarların kullanımı giderek artıyor. Diğer yandan quantum bilgisayarlara ilişkin çalışmalar devam ediyor. 

İnternet, artık sadece bilgisayarlardan oluşan bir ağ değil, nesnelerin interneti haline geldi. Evlerde kullanılan klima, buzdolabı fırın gibi eşyalar, spor saatleri, üretim bantlarında kullanılan alıcılar gibi çok sayıda nesne IP adresiyle internete bağlı ve ağa sürekli olarak veri gönderir hale geldi. İnsanların cep telefonları ile daha işteyken evlerinin sıcaklığını ayarlamaları artık bilim kurgu sahnesi değil. 

Yapay zekâ ve yapay öğrenme alanındaki çalışmalar sonucunda kendi kendine öğrenen algoritmalar, bilgisayarlar ve programlar üretilmeye başlandı. İşçilerin değil robotların ve makinelerin çalıştığı "karanlık" fabrikalar inşa edilmeye başlandı. Amazon firması Amerika'da, siparişleri otonom dronelar ile teslim etmeye başladı. Zaten bu siparişlerin depolanması ve depolardan bulunup çıkarılması da otonom robotlar tarafından gerçekleştiriliyor.

Bu gelişmeler, işi ne olursa olsun herkesin hayatına bilgisayarı soktuğu gibi programcılığı da herkes için gerekli bir yetkinlik kılıyor. Ünlü yapa zekâ araştırmacısı, akademisyen Andrew Ng, yapay zekanın 21. yüzyılın elektriği olduğunu söylüyor. Andrew Ng'ye göre nasıl ki 20. yüzyılda elektriğin önemi, elektrik elektronik mühendisliğini bu yüzyılın en önemli mesleklerinden birisi haline getirdi ise 21. yüzyılda da yapay zekâ aynı öneme sahip olacaktır. Yapay zekâ, yapay öğrenme, derin öğrenme gibi konularda ilerlemek de ileri derecede matematik, istatistik bilgisinin yanı sıra bir o kadar programcılık bilgisine sahip olmaktan geçiyor. Nitekim, gelişmiş ülkeler çocuklara küçük yaşlardan itibaren programlama dersleri vermeye başladılar bile. 

Günümüzde, ne iş yapıyor olursanız olun, ekonomist, sosyolog, mühendis, öğretmen, doktor ya da bankacı, mesleğinizde başarılı olabilmek için mutlaka en az bir programlama dilini bilmeniz gerekiyor. Geleceğin Dünya’sına, dijital dünyaya hâkim olan ulusların söz sahibi olacağı artık herkes tarafından kabul ediliyor. Bilgisayarlara hâkim olmanın yolu da onların dilini öğrenmekten geçiyor. 

:::{figure-md} raspberry-fig
<img src="figures/raspberry.jpg" alt="raspberry">

Yaklaşık bir kredi kartı büyüklüğündeki Raspberry Pi Bilgisayarı
:::

## Bilgisayarların Yapısı

Nasıl ki otomobil kullanabilmek için otomobil ve motor yapısı hakkında derinlemesine bilgi sahibi olmak gerekmiyorsa da iyi bir programcı olmak için de bilgisayarın işleyişi ve bilgisayar parçaları hakkında derin bilgi sahibi olmanız gerekmez. Ancak, yine de her programcının, bilgisayarların yapısı ve işleyiş prensipleri konusunda yüzeysel de olsa bilgi sahibi olmasında fayda vardır. 

Her ne kadar çok farklı tipte ev türde olsa da bir bilgisayar donanım olarak adlandırılan fiziksel parçalar ile yazılım olarak adlandırılan ve bilgisayarı çalıştırmaya yarayan programlardan oluşur. Donanım, bilgisayarın ana kartı, işlemcisi, ekran kartı, klavyesi gibi fiziksel parçaları, yazılım ise bilgisayara yüklenmiş olan işletim sistemi ve diğer programlardır. 

Bir bilgisayarın donanımı genel olarak girdi, çıktı, hafıza (random access memory, RAM), işlemci (central processing unit, CPU), ikincil hafıza birimlerinden oluşur. 

Girdi ünitesi, bilgisayara veri okutmak için kullanılan tüm ünitelerin genel adıdır. Masaüstü veya dizüstü bilgisayarların klavye ve fareleri, tablet bilgisayarların dokunmatik ekranları, CD, DVD, USB bellek girdi üniteleri olarak tanımlanabilir. Genel anlamıyla düşünülecek olursa bir bilgisayara veri aktarmak için kullanılan her türlü araç ya da arayüz girdi ünitesidir. Bu açıdan, harekete duyarlı bir alıcıdan veri okuyan bilgisayar için alıcı, girdi ünitesidir. 

Çıktı ünitesi, bilgisayarda gerçekleşen işlemin sonucunun aktarıldığı birimdir. Bilgisayar ekranında bir fotoğrafa baktığımızda, kulaklıklarla müzik dinlediğimizde, USB belleğe bir dosya kaydettiğimizde, yazıcıda bir belge bastırdığımızda çıktı birimlerini kullanmış oluyoruz. 

Bilgisayarda bir programın çalışması sırasında ihtiyaç duyulan kısa süreli hafıza birincil hafıza ya da bellek (Random Access Memory, RAM) olarak tanımlanır. RAM, programların çalışması sırasında kullanılır. Bilgisayar kapatıldığında ise bellekteki bilgiler kaybolur. 

İşlemci, programı çalıştıran ve komutları sırasıyla gerçekleştiren, verileri işleyen birimdir. Bu açıdan, işlemci genellikle insan beynine benzetilir. 

Son olarak ikincil hafıza ise bilgisayardaki sabit bellek, taşınabilir bellekler, USB bellek, CD, DVD gibi program veya dosya gibi verilerin kaydedilip saklanmasında kullanılan araçlardır.  

## Bilgisayarlarda Veri Yapısı

Bilgisayarların en temel veri yapıları bit’lerdir. Bit, “binary digit” yani ikili basamak teriminin kısaltmasıdır. Bit, sadece 0 veya 1 değerlerinden birisini alabilir. Bilgisayarların gerçekleştirdiği bütün işlemlerin temelinde, bir bit değerinin okunması, bite değer atanması ya da değerin değiştirilmesi şeklinde bitler üzerinde yapılan basit işlemler yer alır. Sekiz bit, bir byte’a eşittir.  Bir byte ise bir karakteri saklayabilir. Aşağıdaki tabloda çeşitli karakterlerin byte karşılıkları örnek olarak gösterilmiştir. 

| Karakter | Onluk Düzende Karşılığı |      İkili     |
|:--------:|:-----------------------:|:--------------:|
|    A     |        65               |      1000001   |
|    B     |        66               |      1000010   |
|    C     |        67               |      1000011   |
|    D     |        68               |      1000100   |
|    a     |        97               |      1100001   |
|    b     |        98               |      1100010   |
|    c     |        99               |      1100011   |
|    d     |       100               |      1100100   |
|    0     |        48               |       110000   |
|    1     |        49               |       110001   |
|    2     |        50               |       110010   |
|    3     |        51               |       110011   |
|    4     |        52               |       110100   |
|    @     |        64               |      1000000   |
|    +     |        43               |       101011   |
|    /     |        47               |       101111   |

Byte ikili sayma sistemindedir ve onluk düzendeki karşılığı ikili sayma sistemindeki sayıyı onluk sisteme çevirerek bulunabilir. İkilik sayma sisteminin onluk sisteme nasıl çevrileceği aşağıdaki tabloda gösterilmiştir. 

|                       |           |
|:----------------------|:---------:|
| İkili Sistemdeki Sayı |   1       |    0     |    1     |    0     |   0     |    1    |   0     |    1    |
| Basamak               | $2^7=128$ | $2^6=64$ | $2^5=32$ | $2^4=16$ | $2^3=8$ | $2^2=4$ | $2^1=2$ | $2^0=1$ |
| Basamak Değeri        |   128x1   |   64x0   |   32x1   |   16x0   |    8x0  |    4X1  |   2x0   |    1x1  |

İkilik düzendeki 10100101 sayısının onluk sistemdeki karşılığı 128 + 32 + 4 + 1 = 165 olarak bulunur. 

Bilgisayara bir kelime ya da bir sayı yazdığımızda bilgisayar aslında bu kelimedeki her bir karakterin ikili düzendeki değerini hafızasına alır ve bunları kullanarak işlem yapar. 

:::{figure-md} veri-yapisi-fig
<img src="figures/veri_yapisi.png" alt="veri yapısı">

Bilgisayarda Veri Yapısı
:::

Yukarıdaki şekilde "Eren", "Fizikçi", "2006" gibi değerler birer alanı temsil eder. Bu alanlar yan yana gelerek bir satır ya da kayıt oluştururlar. Çok sayıda kaydın bir araya gelmesiyle de bir dosya oluşur. Yukarıdaki şekilde her bir alanda kişi ismi, mesleği ya da doğum yılı saklanıyor. Bir kişinin isminin, mesleğinin ve doğum yılının yan yana gelmesiyle de bir kayıt meydana geliyor. Bütün kayıtlar bir arada dosyayı oluşturuyor.  Bilgisayar hafızasında kayıtların yan yana ya da alt alta olmaları gibi bir durum söz konusu değildir. Bilgisayar tüm bilgileri sıralı 0 ve 1'ler şeklinde algılar. Sadece anlamayı kolaylaştırmak için bu şekilde aktarıyoruz. 

Harf ve rakamlar gibi tüm sembol ve işaretlerin de (+, !, %, & vb.) ikili düzendeki değerleri vardır. Dünya'da kullanılan karakter setleri için farklı standartlar geliştirilmiştir. Bunlardan en çok kullanılanlar Unicode ve ASCII (American Standard Code for Information Interchange) standartlarıdır.

Sekiz bitin bir byte ettiğini söylemiştik. Günlük hayatta megabyte ya da gigabyte terimlerini çok sık duyarsınız. Günümüzde veri büyüklükleri o kadar arttı ki megabyte ve gigabyte yerine artık terabyte konuşulmaya başlandı. Bu terimlerin ne anlama geldiği aşağıda belirtiliyor.

| Büyüklük       | Anlamı    | Yaklaşık Değeri |
|:---------------|:---------:|:---------------:|
| Kilobyte (KB)  | 1024 Byte |  ~$10^3$ Byte   |
| Megabayte (MB) | 1024 KB   |  ~$10^6$ Byte   |
| Gigabyte (GB)  | 1024 MB   |  ~$10^9$ Byte   |
| Terabyte (TB)  | 1024 GB   |  ~$10^12$ Byte  |
| Petabyte (PB)  | 1024 TB   |  ~$10^15$ Byte  |
| Exabyte (EB)   | 1024 PB   |  ~$10^18$ Byte  |
| Zettabyte (ZB) | 1024 EB   |  ~$10^21$ Byte  |


## Programlama Dilleri

Dil, “İnsanların düşündüklerini ve duyduklarını bildirmek için kelimelerle veya işaretlerle yaptıkları anlaşma” olarak tanımlanıyor ([TDK](https://www.tdk.gov.tr/)). Bu açıdan, bilgisayarların ne yapmaları gerektiğini programlar yardımı ile anladıklarını düşünürsek bu programların yazılmasına ilişkin kuralları da programlama dili olarak tanımlamak yanlış olmaz. Nasıl ki Dünya üzerinde konuşulan çok sayıda dil varsa bilgisayarların insanlarla ve birbirleriyle konuşması için kullanılan birçok programlama dili vardır. 

Programlama dilleri genel olarak üç sınıfa ayrılabilir (Deitel & Deitel, Java How to Program, Pearson, 2015):

1.	Makine dilleri
2.	Assembly dilleri
3.	Yüksel seviye diller

Makine dili ve Assembly dili düşük seviyeli diller olarak isimlendirilir. Bunun sebebi bu dillerin doğrudan işlemci ve hafıza ile konuşuyor olmalarıdır. Makine dilleri, bilgisayarların doğrudan anlayabilecekleri şekilde sayılar kullanılan dillerdir. Her bilgisayar tipi için kullanılan makine dili farklıdır. Aşağıda, 1'den n'ye kadar olan sayıların toplamını bulan örnek bir makine dili kodu yer almaktadır:

0000100010010011\
0001100100000011\
0010100000010011\
0000011110010100\
0001100000000011\
0000101010010101\
0111100000000111

Bu dilleri kullanmak çok zor olduğu gibi kullanımı ve programlaması da son derece yavaş olabilir. Bu nedenle, konuşma diline daha yakın olan genellikle kısaltmalardan oluşan, Assembly programlama dilleri geliştirilmiştir. Assembly dili kullanılan bilgisayarın özelliklerine ve işletim sistemine bağlı bir dildir. Bu dilde program yazan kişi doğrudan mikroişlemci ve hafızaya ulaşır ve burada değişiklik yapar. Assembly dilinde yazılan programlar bir derleyici (assembler) aracılığıyla makine diline çevrilir. Yukarıda görülen programın assembly dilindeki karşılığı aşağıdaki gibidir:

```
L28	movf		_n,f\
    Btfsc		STATUS, Z\
    goto		L41\
    movf		_n,f\
    addwf		_sum, f\
    btfsc		STATUS, C\
    incf		_sum+1, f\
    decf		_n,f\
    goto		L28\
L41
```

Assembly dili, makine diline göre daha açık ve anlaşılır olmakla birlikte yine de öğrenmesi ve program yazması uzun süre alan bir dildir. Ayrıca basit işlemler için bile uzun kodlar yazmak gerekmektedir. Bunu da aşabilmek için çok daha anlaşılır ve basit olan yüksek seviye programlama dilleri geliştirilmiştir. Makine dilinden, yüksek seviyeli dillere gidildikçe program konuşma diline daha çok benzemeye başlar. Python, C, C++, Java, Fortran vb. bu diller arasındadır. Yukarıdaki kodla aynı işi yapan Python programı aşağıdaki gibidir.

```Python
while n > 0:
    sum += n
    n -= 1
```

Her ne kadar makine ve assembly dillerinin kendilerine göre (işlemci ve hafızaya doğrudan erişim gibi) avantajları olsa da bu dillerde çok basit işlemleri gerçekleştirmek için bile uzun kodlar yazmak gerekebilmektedir. Bu zorluğu aşmak için yüksek seviyeli, öğrenilmesi, yazması ve anlaşılması kolay olan diller geliştirilmiştir.

Geçmişte ve günümüzde yaygın olarak kullanılan programlama dillerinden bazılarına aşağıda örnek olarak yer verilmiştir. 

**COBOL:** 1950’li yıllarda Amerikan Savunma Bakanlığının bir projesi kapsamında geliştirilmiştir. “Common Business Oriented Language” kelimelerinden türetilmiştir. Daha çok iş ve finans uygulamaları için kullanılmıştır. Yakın zamanlara kadar iş dünyasında, bankacılık ve finans alanlarında yayın şekilde kullanılmaktaydı. Cobol’un İngilizce’ye çok benzeyen, okunması kolay bir yapısı vardır. 

**FORTRAN:** IBM tarafından 1950’lerde geliştirildi. Formula Translator (Formül Çevirici) ifadesinin kısaltılmış halidir. Karmaşık matematiksel işlemlerin gerçekleştirilmesi amacıyla geliştirildi ve daha çok bilim ve mühendislik uygulamalarında kullanıldı. 

**BASIC:** 1960’lı yıllarda Dartmouth College tarafından yeni başlayanlara programcılık öğretmek amacıyla geliştirilmiştir.

**PASCAL:** Niklaus Wirth tarafından 1970 yılında öğrencilere programlamayı öğretmek amacıyla geliştirilmiştir. Pascal uzun yıllar üniversitelerde öğretilen programlama dili olmuştur. Daha sonra Pascal’dan türetilen ve daha hızlı bir versiyonu olan Turbo Pascal uzun süre oldukça popüler programlama dillerinden olmuştur. Pascal’dan türetilen diğer diller Object Pascal (ve daha sonra Delphi), Borland Pascal, ADA’dır.

**C:** 1970’lerin başında Bell Laboratuvarlarında çalışan Dennis Ritchie tarafından geliştirilmiştir. Bugüne kadar en yaygın olarak kullanılan programlama dillerinden birisi olmuştur. Birçok uygulama ve program C dilinde yazılmıştır. 

**C++:** 1980’lerin başında Bell Laboratuvarlarında çalışan Bjarne Stroustrup tarafından geliştirilmiştir. C++ dili performans, hız ve esneklik açılarından en önde gelen dillerden biridir. Ayrıca, nesne yönelimli bir programlama dilidir. 

**C#:** Genel kullanım amaçlı nesne yönelimli bir programlama dili olup Microsoft tarafından .NET platformunda kullanılmak üzere geliştirilmiştir. 

**JAVA:** Genel kullanımlı nesne yönelimli bir programlama dili olup platformdan bağımsız bütün işletim sistemi ve bilgisayarlarda çalıştırılabilecek programlar yazılabilmesi amacıyla geliştirilmiştir. Birçok özelliğini C ve C++ dillerinden almakla birlikte bunlara göre daha yüksek seviyeli bir dildir.  

**JAVASCRIPT:** Web uygulamalarına kullanıcı etkileşimi gibi dinamik uygulamalar kazandırmak amacıyla geliştirilmiş bir dildir. 

**MATLAB:** Matrix Laboratory (Matris Laboratuvarı) sözlerinden türetilmiştir. Matworks firması tarafından, matematiksel işlemlerin gerçekleştirilmesi için geliştirilmiştir. Veri işleme ve analiz, fonksiyon ve grafik uygulamalarında oldukça kullanışlıdır. Vektör ve matris tabanlı kullanım yapısı diğer dillerden farklı olarak işlemlerin uzun döngüler olmaksızın hızlı bir şekilde gerçekleştirilebilmesini sağlamaktadır. 

**R:** 1993 yılında Auckland Üniversitesinden Ross Ihaka ve Robert Gentleman tarafından geliştirilmiştir. Öncelikle istatistiksel uygulamalar için geliştirilmiş olmakla birlikte zamanla genel kullanım amaçlı bir dil haline gelmiştir. Son yıllarda büyük veri uygulamalarının yaygınlaşması ile birlikte özellikle büyük veri ve yapay öğrenme alanlarında Python ile birlikte kullanımı en çok artan programlama dillerinden birisi olmuştur. 

## Python Programlama Dili

Python, 1989 yılında Guido van Rossum tarafından geliştirilen bir programlama dilidir. Guido van Rossum, Python ismini ünlü komedyen Monthy Python’dan esinlenerek bulmuştur. Python açık kaynak kodlu bir programlama dilidir ve ücretsizdir. 

Python orijinal olarak C dilinde yazılmıştır. Bunun dışında Java'da geliştirilen (Jhython) ve Microsoft .NET ortamında C# ile geliştirilen (IronPython) versiyonları da bulunmaktadır.

Python bugüne kadar iki farklı koldan ilerledi: Python 2 ve Python 3. Python 2, 2000 yılında yayınlandı ve kitabın yazıldığı tarihte 2.7.14 sürümü mevcuttu. Python 3 ise 2008 yılında yayınlandı. Aslında iki sürüm arasında çok fazla fark bulunmamaktadır. Bu iki sürüm birbirinin devamı olarak değil, iki farklı koldan ilerlemektedir. Bu dillerden birini biliyorsanız diğerini de kolayca anlarsınız. Ancak bunlardan birisinde yazılan program diğerinde çalışmaz. Python 2 daha eski ve daha oturmuş olmakla birlikte, Python 3, Python 2'deki birçok eksikliği gidermiştir. Bir değişiklik olmaz ise Python 2’nin geliştirimi 2020 yılında sona erecek ve geliştirim Python 3 ile devam edecektir. Biz bu kitapta Python 3 sürümünü kullanacağız. 

Çok sayıda programlama dili arasında neden Python öğreneyim diye soruyor olabilirsiniz? Öncelikle Python son derece güçlü bir dil olduğu kadar aynı zamanda öğrenmesi de çok kolay bir dildir. Bazı dillerin aksine Python’un standart kütüphanesi çok gelişmiştir. Bu nedenle çoğu zaman çok fazla kod yazmanıza da gerek kalmaz. Öte yandan, Python için geliştirilmiş numpy, pandas, matplotlib gibi çok güçlü ve kullanışlı birçok kütüphane de bulunmaktadır. Bundan dolayı Python, web programlama, bilimsel programlama, veri bilimi, yapay öğrenme, derin öğrenme gibi farklı alanlarda yaygın olarak kullanılmaktadır.

Yüksek kullanıcı trafiği olan Youtube, Dropbox, Instagram gibi siteler web geliştirme için Python’da geliştirilmiş web geliştirme kütüphanaleri Django, Flask ya da Pyramid kullanmaktadır. 

Python’da geliştirilmiş olan NumPy ve SciPy kütüphaneleri, bilimsel programlamalar için çok hızlı programlamaya imkân vermektedir. 

Son yıllarda önemi ve kullanımı giderek artan yapay öğrenme uygulamaları için de Python’da çok sayıda kütüphane geliştirilmiştir. TensorFlow, Keras ve Scikit Learn bunlardan en önemlileridir. Ayrıca Python, Pandas, Matplotlib ve Bokeh kütüphaneleriyle de veri analizi ve görselleştirme de çok kolaydır.

Tüm bunlar, Python’u finanstan, biyolojiye, fizikten, web tasarımına kadar çok geniş bir perspektifte kullanılabilen bir programlama dili haline getirmiştir.

Bu kadar işlevselliğin yanı sıra Python, yazması, okuması ve öğrenmesi de çok kolay olan bir programlama dilidir. Bu nedenle öğrencilere programlama öğretmede en fazla kullanılan dillerden birisidir. Python, C, C++ ve Java gibi dillere göre çok daha anlaşılır bir yazı stiline sahiptir. Aşağıda, iki sayının toplamını bulan programların C++, C ve Java dillerindeki örnekleri yer alıyor. Önce C++ uygulamasına bakalım.

```C++
using namespace std;
int main()
{
 int a, b, c;

  cout << "İki tam sayı giriniz: \n";
  cin >> a >> b;

  c = a + b;
  cout << "İki sayının toplamı = " << c << endl;

  return 0;
}
```
Aynı programın C versiyonu aşağıdaki gibidir:

```C
# include<stdio.h>
int
main()
{
    int a, b, c;

    printf("İki tam sayı giriniz: \n");
    scanf("%d%d", & a, & b);

    c = a + b;

    printf("İki sayının toplamı =  %d\n", c);

    return 0;
}
```
Şimdi de Java versiyonunu görelim:

```Java
import java.util.Scanner;

class AddNumbers
{
    public static void main(String args[])
    {
        int x, y, z;
        System.out.println("İki tam sayı giriniz: ");
        Scanner in = new
        Scanner(System. in);
        x = in.nextInt();
        y = in.nextInt();
        z = x + y;
        System.out.println("İki sayının toplamı =  " + z);
    }
}
```

Aynı işlemi yapan Python programı ise aşağıdaki gibidir. Bu bölümdeki kodları anlamıyorsanız endişe etmenize gerek yok. Hepsi ilerideki bölümlerde adım adım anlatılacaktır. Burada sadece Python ile diğer diller arasındaki yapısal farklılıkları aktarmaya çalışıyoruz.

Python’da, döngüler ve koşullu ifadelerde diğer dillerin çoğunda olduğu gibi parantezler kullanılmaz. Bunun yerine girintiler kullanılır. Örneğin, C++’ta (diğer dillerde de benzerdir) fonksiyon aşağıdaki şekilde tanımlanır:

```Cpp
int max(int sayi1, int sayi2) {
    int sonuc;
    if (sayi1 > sayi2)
       sonuc = sayi1;
    else
       sonuc = sayi2;

    return sonuc;
}
```

Yukarıdaki C++ fonksiyonu, iki sayıdan büyük olanı bulur. Fonksiyonun, argümanların, fonksiyon içindeki geçici değişkenlerin veri tipinin tanımlanması gerekiyor. Fonksiyon metni { } parantezleri arasında olmak zorunda. Ayrıca her satırın sonunda noktalı virgül olması gerekiyor. 

Python’da ise bunların hiçbirine gerek yok. Değişkenlerin türünü baştan belirtmeye gerek yok. C++ ya da Java gibi dillerde değişkenler statik olarak tanımlanır. Yani bir değişkenin tipi başlangıçta tanımlanır ve sonradan değiştirilemez. Python da ise değişkenler dinamik olarak tanımlanır. Yani değişken tipi önceden tanımlanmaz. Program çalıştığı zaman otomatik olarak algılanır ve program sırasında da değişebilir. 

Python'un bir diğer önemli farkı da fonksiyon ve koşullu ifadelerin içeriğinin girintilerle belirlenmesi.

```Python
def max(sayi1, sayi2):
    if sayi1 > sayi2:
        sonuc = sayi1
    else:
        sonuc = sayi2
    return sonuc
```

Görüldüğü gibi Python’da bir fonksiyon ya da koşullu ifade veya bir döngü, iki nokta, (:), işareti ile belirtiliyor. Hangi ifadelerin ilgili fonksiyon ya da döngüye ait olduğunu belirtmek için de izleyen satırdan itibaren girinti kullanılıyor. Bu durum aşağıdaki şekilden daha iyi anlaşılabilir. 



Fonksiyon tanımlamak için ilk satırda görülen def kelimesi kullanılıyor. Satır sonunda da (:) işareti olmalı. Fonksiyona ait kodlar, bu satıra göre daha içeriden başlamak zorunda. Şekilde, 1 ile başlayan tüm satırlar ilgili fonksiyonun parçası. Fonksiyon tanımlanması bittikten sonra tekrar satırın en başından başlayarak devam edilir. Aynı şekilde, ileride göreceğimiz gibi if ve else bloklarına ait komutlar da (2 ve 3 ile başlayan satırlar) bu komutlara göre daha içeriden başlamalı. 

Diğer dillerde bu durum bir zorunluluk değil sadece kodun okunabilir olması için önerilen bir uygulama. Yani başka dillerde, tüm satırlar aynı hizada olsa da bir sorun olmaz ancak Python’da def ile başlayan fonksiyon tanımından sonraki satırlar aynı hizada olursa aşağıdaki gibi bir hata mesajı alınır:

<span style="color:red">IndentationError: expected an indented block</span>

Bu mesaj, ilgili satırların hizalamasında sorun olduğu ve satırın daha içeriden başlaması gerektiği anlamına gelir.

Terminalde ya da bir Python editöründe fonksiyon ya da bir döngünün ilk satırının sonuna (:) işareti getirip Enter tuşuna bastığınızda, imlecin alt satırda daha içeriden başladığını görürsünüz. Terminal ekranında fonksiyon ya da döngü gövdesi içinde olduğunu göstermek için satır başında yan yana üç nokta görülür. Bu üç noktadan sonra boşluk tuşu veya tab tuşunu kullanarak satır içine gidilmelidir. Aksi halde aşağıdaki gibi bir hata mesajı alınır. 

```Python
for i in range(10):
print (i)
File "<stdin>", line 2
    print (i)
        ^
IndentationError: expected an indented block
```

Genel olarak kabul edilen boşluk uzunluğu dört boşluk veya bir tab kadardır. Ancak aynı kod içinde hem boşluk hem de tab tuşunu aynı anda kullanmamaya dikkat edilmelidir. Ayrıca, aynı kod içinde aynı boşluk sayısını bırakmaya da dikkat edilmelidir. Özellikle aynı blok içinde farklı uzunlukta boşluk bırakılması hata mesajı alınmasına yol açacaktır.

```Python
for i in range(2):
     for j in range(3):
         print (str(i) + " * " + str(j) + " = " + str(i*j))
```

```
0 * 0 = 0
0 * 1 = 0
0 * 2 = 0
1 * 0 = 0
1 * 1 = 1
1 * 2 = 2
```
Fonksiyon ya da döngü bloğundan çıkmak istendiğinde satıra herhangi bir şey yazılmadan enter tuşuna basılır. Python’daki boşluk kuralı kodun kolay okunmasını sağlar ve diğer dillerde yer alan parantezlerin yanlış kullanılmasından kaynaklanan hatalara meydan vermez.  

### Python Geliştirme Standartları

Python'da programlama tarzının önemli olduğunu belirtmiştik. Bu nedenle Python için yazım standartları ve rehberleri yayınlanmakta ve bunlar sürekli olarak geliştirilmektedir. Bu rehberler PEP (Python Enhancement Proposals) olarak bilinir. Tüm PEP'ler bu kitapta yer verilemeyecek kadar fazladır. PEP'leri incelemek için https://www.python.org/dev/peps/  sayfası incelenebilir.  Bu sayfada yer alan PEP 0, tüm PEP dokümanlarının listesini vermektedir. Bunlar içinde yer alan “PEP 8: Python Kodu için Üslup Rehberi”, kod yazım standartlarını anlatmaktadır.

PEP'lerden bahsetmişken Tim Peters tarafından yazılmış olan Python'un Zeni (The Zen of Python) yazısından da bahsetmek gerekir. Bu kısa yazı Python'da kodlamanın ana ilkelerini özetler. Kullanılan Python editörüne import this komutu girildiğinde aşağıdaki yazı çıkar. Python’un Zeni aynı zamanda PEP 20’de yer almaktadır. 

>The Zen of Python, by Tim Peters\
>Beautiful is better than ugly.\
>Explicit is better than implicit.\
>Simple is better than complex.\
>Complex is better than complicated.\
>Flat is better than nested.\
>Sparse is better than dense.\
>Readability counts.\
>Special cases aren't special enough to break the rules.\
>Although practicality beats purity.\
>Errors should never pass silently.\
>Unless explicitly silenced.\
>In the face of ambiguity, refuse the temptation to guess.\
>There should be one-- and preferably only one --obvious way to do it.\
>Although that way may not be obvious at first unless you're Dutch.\
>Now is better than never.\
>Although never is often better than *right* now.\
>If the implementation is hard to explain, it's a bad idea.\
>If the implementation is easy to explain, it may be a good idea.\
>Namespaces are one honking great idea -- let's do more of those!

**Türkçesi:**

>Python'un Zeni, Tim Peters\
>Güzel, çirkinden iyidir.\
>Açık, gizliden iyidir.\
>Basit, karmaşıktan iyidir.\
>Karmaşık, karışıktan iyidir.\
>Düz olan iç içe geçmişten iyidir.\
>Aralıklı olan sık olandan iyidir.\
>Okunabilirlik önemlidir.\
>Özel durumlar, kuralları çiğneyecek kadar özel değildir.\
>Uygulanabilirlik, saflığı yense de\
>Hatalar asla sessizce geçiştirilmemelidir.\
>Açıkça yapılmadıysa.\
>Belirsizlik karşısında, tahmin yürütmenin cazibesinden kaçın.\
>Bir şeyi yapmanın -tercihen sadece- bir tek belirgin yolu olmalıdır.\
>Tabii, Hollandalı  değilseniz bu yol ilk başta belirgin olmayabilir.\
>Şimdi, hiçbir zamandan daha iyidir.\
>Asla, çoğu zaman *hemen* şimdiden daha iyi olsa da\
>Açıklanması zor olan uygulama, kötü fikirdir. \
>Açıklanması kolay olan uygulama, iyi fikir olabilir.\
>Ad uzayı muhteşem bir fikir – onlardan daha çok yapalım!

### Python Kurulumu

#### Windows Kullanıcıları için Python Kurulumu

Bilgisayarınızda Python’un kurulu olup olmadığını görmek için “command” ekranını açıp “Python” yazın. Aşağıdakine benzer bir ifade ile başlayan bir yazı ve >>> ile başlayan satırı görüyorsanız bilgisayarınızda zaten Python kuruludur. Bunun yerine “Bad command or file name” gibi bir mesaj alıyorsanız Python kurulu değildir. 

```
Python 3.6.0 (default, Dec 23 2016, 11:57:41)…
Type “help”, “copyright", “credits” or licence for more information.
>>>
```

Python programını kurmak için https://www.python.org sayfasından Download linkini kullanarak en güncel Python sürümünü indirebilirsiniz. Kitap yazıldığında en güncel sürüm Python 3.6.5 idi. Python 64 bit sürümünü indirmek için https://www.python.org/downloads/windows sayfasından “Download Windows x86-64 executable installer” linkini kullanabilirsiniz. İndirilen kurulum dosyası çalıştıktan sonra aşağıdaki adımlar takip edilerek Python kurulumu tamamlanır. İlk gelen kurulum penceresinin altında yer alan "Install launcher for all users" ve "Add Python 3.6 to PATH" seçimlerinin işaretli olması önerilir. 


:::{figure-md} python-kurulumu-fig
<img src="figures/python_kurulum.png" alt="python kurulumu">

Windows için Python kurulum adımları
:::

Bundan sonra Command Prompt ekranında (Windows için PowerShell ekranı da olabilir) Python yazarak programı kullanmaya başlayabilirsiniz. 

:::{figure-md} python-cmd-fig
<img src="figures/py_cmd.png" alt="cmd ekrani">

Command Prompt ekranında Python kullanımı
:::

#### Linux Kullanıcıları için Python Kurulumu

Linux Ubuntu dağıtımı için kurulum adımları aşağıdaki gibidir. Öncelikle, kurulu Python sürümü olup olmadığını görmek için terminal ekranında aşağıdaki kod yazılır:

```
$ python3 -V
Python 3.5.2
```

Ubuntu için kurulum komutları aşağıdaki gibidir:

```
$ sudo apt-get update
$ sudo apt-get install python3.6
```

Python paketlerini kurmak ve yönetmek için gerekli olan pip kurulumu aşağıdaki şekilde yapılır. 

```
$ sudo apt-get install -y python3-pip
```

Sonrasında istenilen bir paketi kurmak için aşağıdaki kod yazılır:

```
$ pip3 install paket_ismi
```

Komutta yer alan “paket_ismi” yerine istenilen paketin adı yazılır. Örneğin, numpy, pandas, django, matplotlib gibi. 

Ubuntu’da da Python'u kullanmak için aynı şekilde terminal ekranı açılır ve python3 yazılır.


#### Linux Kullanıcıları için Python Kurulumu

Mac OS X 10.8 sürümü Python 2.7 kurulu olarak gelir. Python 3 kurmak için yine www.python.org sayfasındaki Download linkinden Mac OS X sekmesini seçerek ya da doğrudan https://www.python.org/downloads/mac-osx/ sayfasından istenilen Python sürümü indirilip kurulabilir. Kurulum sonrasında, Applications (Uygulamalar) klasöründe MacPython 3.6 klasörü yer alır. Bu klasörde, Python’un standart geliştirme ortamı olan IDLE uygulaması kullanılabilir. Ya da doğrudan terminal ekranında python3 yazarak Python ortamına geçilebilir.

### Python Editörleri

Python kurulumunu gerçekleştirdikten sonra, işletim sisteminin terminal (komut ekranı, command screen) kullanarak program yazmaya başlayabilirsiniz. Ancak, bunun yerine geliştirilmiş olan çok sayıda Python editörü (entegre geliştirme ortamı, integrated development environments) daha kullanışlı ve zevkli kodlama deneyimi sunmaktadır. Aşağıda, en çok kullanılan Python editörleri listelenmiştir. Bunların dışında çeşitli editörler de mevcuttur. 

**PyCharm:** JetBrains firması tarafından sunulan son derece gelişmiş ticari bir Python editörüdür. Bununla birlikte ücretsiz sürümü de bulunmaktadır. Python’la proje geliştirme, sürüm kontrolü, otomatik komut tamamlama, gelişmiş hata ayıklama gibi özelliklere sahiptir. https://www.jetbrains.com/pycharm/ adresinde yer alan Download linkinden Community seçeneği ile ücretsiz sürümü indirilip kurulabilir. Windows, MacOS ve Linux sürümleri bulunmaktadır.

:::{figure-md} pycharm-fig
<img src="figures/pycharm_ide.png" alt="Pycharm">

PyCharm Python IDE
:::

**Wing IDE:** Wingware firması tarafından geliştirilmiştir. Ticari bir program olmasına karşın, ücretsiz sürümü de mevcuttur. Wing IDE de PyCharm gibi entegre bir kodlama ortamı sunmaktadır. https://wingware.com sayfasında yer alan Download linkinden Wing Personal veya Wing 101 sürümlerinden birisi ücretsiz olarak indirilip kurulabilir. Wing IDE, Windows, MacOS ve Linux’ta çalışmaktadır. 

**Anaconda:** Anaconda bir Python editörü ya da geliştirme ortamı olmayıp farklı Python ve R geliştirme ortamlarını bir arada sunan bir platformdur. Jupyter notebook, Spyder, qtconsole, gibi Python editörlerini sunmaktadır. Ayrıca, Learning linki ile çok sayıda eğitim sayfasına erişmek ya da Community linki ile Python haberleşme, forum sayfalarını görüntülemek mümkündür. 


:::{figure-md} anaconda-fig
<img src="figures/anaconda_ide.png" alt="Anaconda">

Anaconda Platformu
:::

Spyder editörü, PyCharm ve Wing IDE gibi entegre bir Python geliştirme ortamı sunmaktadır. 

:::{figure-md} spyder-fig
<img src="figures/spyder_ide.png" alt="Spyder">

Spyder Python IDE
:::

Jupyter ise web tabanlı, interaktif bir kodlama ara yüzüdür. Diğer editörlerden farklı olarak hem metin (markdown) hem de kod yazmaya olanak sağlayan bir programdır. Jupyter dosyaları .pynb (Python notebook) uzantılı olarak kaydedilir. Hem kod hem de Markdown ile metin yazmaya izin veren bir formata sahiptir. Jupyter özellikle veri analizi çalışmalarında daha çok kullanılmaktadır.

:::{figure-md} jupyter-fig
<img src="figures/jupyter_ide.png" alt="Jupyter">

Jupyter Editörü
:::

Kitabın basıma hazırlandığı tarihlerde henüz beta sürümü kullanımda olan JupyterLab editörü Jupyter editörü ile dosya ve veri yönetimini bir arada gerçekleştirmeyi mümkün kılmıştır. 

:::{figure-md} jupyterlab-fig
<img src="figures/jupyterlab.png" alt="Jupyterlab">

JupyterLab Ekranı
:::

Microsoft Visual Studio’da Python kullanmak için geliştirilmiş olan Python Tools for Visual Studio (PTVS) editörü de mevcuttur. Özellikle Microsoft Visual Studio programını kullanmaya alışkın olan programcılar için PTVS cazip bir programlama ortamı sunmaktadır. https://www.visualstudio.com/vs/python/ adresinden Microsoft Visual Studio ve PTVS indirilip kurulabilir.

Son olarak Visual Studio Code (https://code.visualstudio.com/) editöründe Python uzantısını kurarak da Pyhon kullanabilirsiniz. 

Nispeten kısa ya da veri analizi veya görselleştirmeye yönelik programlamalarda Python terminal ekranı ya da Jupyter çok iyi bir ortam sunsa da daha büyük projeler için PyCharm ya da Spyder gibi entegre ortamları kullanmanız önerilir. Uzun bir program yazacaksanız ilgili kodu .py uzantılı bir dosyaya kaydedip daha sonra tekrar tekrar kullanabilirsiniz. Bu dosyalar Python komut dosyası (script) olarak isimlendirilir.

Ben başlangıçta daha çok Jupyter notebook ortamını tercih etsem de son yıllarda tüm kodlamalarını VSCode ortamında yapıyorum. 
