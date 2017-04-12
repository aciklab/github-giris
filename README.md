# Github Giriş Dökümanları
Github'a yeni başlayan birisi için hazırlanmıştır. Detay konulara çok fazla girilmeden özet geçilmiştir. Detay konulara girebilmek için zamanla başka kaynaklara bakmanız gerekmektedir.

Eğer ilk defa github ile tanışıyorsanız ve bir projeye dahil olmak istiyorsanız aşağıdaki 5 maddeden a şıklarından ilerlerseniz sorun yaşamayacaksınız. Daha sonra yeni git projeleri açarken ise b şıklarını takip edebilirsiniz.

## 1. Bilgisayarınıza Git Kurulumu ve kullanımı
Debian tabanlı bir dağıtım kullandığınızı düşünerek ilk olarak yönetici yetkisine sahip bir kullanıcıdan git kurulur.

* sudo apt-get install git

Daha sonra Git üzerinde kendinizi tanıtmanız gerekir:

* git config - -global user.name “Adınız Soyadınız”
* git config - -global user.email “email@adresiniz.com”

## 2.a) Github'taki bir projeyi bilgisayarınıza çekmek
Aşağıdaki komutu girmeniz yeterlidir. Tabi ki uzak sunucu adresim yazan yere kendi ilgilendiğiniz github.com projesindeki git adresini yapıştırmanız gerekmektedir. (örneğin: https://github.com/alorak/github-giris.git) 

* git clone https://github.com/alorak/github-giris.git

## 2.b) Yerel klasör üzerinde git oluşturmak 
Clone yapmazsanız ve boş bir klasörü github'taki deponuza göndermek isterseniz ilk olarak bulunduğunuz klasöre git ayarı yapılmas ıgerekmektedir. Bu aşağıdaki gibi yapılabilir:

* git init

## 3. Projede değişiklikler yapmak
İşte burası size ve programlama yeteneğinize kalmış.

## 4. Yerel projeye commit eklemek
Değişiklik yaptığınız dosyayı önce local git'e commit etmeniz gerekmekte (Eğer tüm dosyaları add yapmak isterseniz * koyabilirsiniz)

* git add dosya_ismi
* git commit -m "Yapılan ilk değişiklikler"

## 5.a) Varolan Projeyi Github'a göndermek
Dosyaları yerel depoya atmak için: (master yerine başka bir branch'e atmak isterseniz onu da yazabilirsiniz)

* git push origin master

Dosyaları Github'ta kontrol edip üzerine göndermek için pull kullanılır. pull komutu aslında fetch ve merge komutlarının bir karışımıdır. fetch github'ta değişiklik olup olmadığını kontrol edip merge iki kodu birleştirmektedir:

* git pull

## 5.b) Projeyi ilk defa github'a göndermek
Eğer projeyi ilk defa github'a gönderiyorsanız aşağıdaki gibi ayarlayıp, gönderebilirsiniz:

* git remote add origin https://github.com/alorak/test1.git
* git push -u origin master



