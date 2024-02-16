# Bad-USB Nedir?
Bad USB, USB aygıtlarını kötü niyetli amaçlar için kullanmayı sağlayan bir tür saldırı ve kötü niyetli bir donanım (malware) türüdür.


Bad USB genellikle USB bellek sürücüleri, klavyeler, fareler veya diğer USB cihazları gibi yaygın kullanılan USB aygıtlarına benzer görünecek şekilde tasarlanır. Ancak bu cihazlar, bilgisayara takıldıklarında istenmeyen eylemler gerçekleştirebilirler.

# Amaç
Bu projede Raspberry Pi Pico sayesinde daha düşük maliyetle yapabileceğiniz USB Rubber Ducky cihazının; yapabildiği her şeyi yapan, bu cihazın nasıl kurulduğundan çok ne tür senaryolarda ne tür Payload'lar işimize yarar bunları derleyip göstermek istedim. 

Bu cihazın en güçlü olduğu senaryo fiziksel erişimimizin olduğu yerlerdir. Fiziksel erişimimizin olduğu yerlerde yapabileceklerimizin gerçekten de sınırı yok. 

Fiziksel erişimimizin olduğu yerlerde zamandan tasarruf ederek istediğimiz kodları çalıştırabilir, antivirüs'ü kapatabilir, kurban bilgisayardan dosya indirebilir veya kurban bilgisayara yükleyebilir, silebilir ve oluşturabiliriz.

# Yasal Uyarı
Ufak bir hatırlatma bu projedeki kaynakları tamamen eğitim üzerine, kendinizi geliştirmek için kullanınız. Aksi takdirde yasal yaptırımlarının olduğunu unutmayınız :)

# Cihazlar Arasındaki Fiyat Farkı
![USB RUBBER DUCKY](https://github.com/ozcanpng/Bad-USB/assets/127627278/fdeb20cc-b1ac-4a2e-bd97-8742939016b2)
![Pi Pico](https://github.com/ozcanpng/Bad-USB/assets/127627278/c82eb623-d654-40fb-b0e2-f2d392fd663a)

# Cihaz 
Cihazı merak edenler için buraya [tıklayıp](https://www.amazon.com.tr/Raspberry-Pi-SC0915-Pico/dp/B09KVB8LVR/ref=asc_df_B09KVB8LVR/?tag=trshpngglede-21&linkCode=df0&hvadid=510499475756&hvpos=&hvnetw=g&hvrand=5826631902843730337&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9056808&hvtargid=pla-1596335753242&psc=1&mcid=b7261fa1640b3b5bbecaa0daa4137f37) güncel fiyatını öğrenebilirsiniz.

# Cihazın Kurulumu
Cihaz kurulumu için vermiş olduğum [projeye](https://github.com/dbisu/pico-ducky) bakıp nasıl kurulduğunu görebilirsiniz. 

# Payloadlar
İndirmiş olduğunuz Payload'lar "payload.dd" adı ve uzantısı altında çalışmaktadır ve tüm Payload'ları [buradan](https://github.com/ozcanpng/Bad-USB/tree/main/Payloads) görebilirsiniz.

Aşağıda "Wifi+Sysinfo+IPinfo.dd" Payload'ıyla neler yapabileceğinizi gösteren bir örnek video var.

https://github.com/ozcanpng/Bad-USB/assets/127627278/7db798c4-c61e-44de-b8fb-5ac11ad5a7e4








