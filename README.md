# Github Giriş Dökümanları
Github'a yeni başlayan birisi için hazırlanmıştır. Detay konulara çok fazla girilmeden özet geçilmiştir. Detay konulara girebilmek için zamanla başka kaynaklara bakmanız gerekmektedir.

## Bilgisayarınıza Git Kurulumu ve kullanımı
Debian tabanlı bir dağıtım kullandığınızı düşünerek ilk olarak yönetici yetkisine sahip bir kullanıcıdan git kurulur.

* sudo apt-get install git

Daha sonra Git üzerinde kendinizi tanıtmanız gerekir:

* git config - -global user.name “Adınız Soyadınız”
* git config - -global user.email “email@adresiniz.com”

## Github'taki bir projeyi bilgisayarınıza çekmek
Aşağıdaki komutu girmeniz yeterlidir. Tabi ki uzak sunucu adresim yazan yere kendi ilgilendiğiniz github.com projesindeki git adresini yapıştırmanız gerekmektedir. (örneğin: https://github.com/alorak/github-giris.git) 

* git clone https://github.com/alorak/github-giris.git

## Projede değişiklikler yapmak
İşte burası size ve programlama yeteneğinize kalmış.

## Github Projesine değişiklikleri göndermek
Değişiklik yaptığınız dosyayı önce local git'e commit etmeniz gerekmekte (Eğer tüm dosyaları add yapmak isterseniz * koyabilirsiniz)

* git add dosya_ismi
* git commit -m "Yapılan ilk değişiklikler"

Dosyaları yerel depoya atmak için: (master yerine başka bir branch'e atmak isterseniz onu da yazabilirsiniz)

* git push origin master

Dosyaları Github'a göndermek için ise;

* git pull



