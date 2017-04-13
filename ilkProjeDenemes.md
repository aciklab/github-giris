# İlk Proje Denemesi Hakkında

Bu denemenin amacı https://github.com/alorak/github-giris adresinde yer alan projeyi kendi github alanınıza çatallayıp, kendi bilgisayarınıza indirerek ufak bir değişiklik yaptıktan sonra tekrar github üzerine atmanızı sağlamaktır.

## 1. Projeyi Çatallama(Fork):
Öncelikle https://github.com/alorak/ilkDeneme adresine girip aşağıdaki gibi fork'a basarak kendi alanınıza çatallamanız gerekmekte.

![alt tag](https://github.com/alorak/github-giris/blob/master/fork.png)

## 2. Kendi alanınızda projeyi görme:
Projeyi başarılı bir biçimde çatalladıysanız kendi adınızın bulunduğu sayfada (https://github.com/adiniz/) artık çatallanmış olarak "ilkDeneme" uygulamasını göreceksiniz.

## 3. Projeyi bilgisayarınıza klonlama
Projeyi kendi alanınızda gördükten sonra projenin kendi alanınızdaki sayfasına girin ve aşağıdaki gibi klonlanacak adresi öğrenin.

![alt tag](https://github.com/alorak/github-giris/blob/master/clone.png)

Daha sonra bilgisayarınıza gelerek bir boş klasör oluşturun. Klasör içerisinde uçbirimde, yukarıda öğrendiğiniz bilgiye göre aşağıdaki komutu yazın:

* git clone https://github.com/adiniz/ilkDeneme.git

## 4. Projede düzenleme yapmak.
Bu aşamada github üzerindeki dosyalar bilgisayarınızdaki boş klasöre gelecektir. "merhaba.py" dosyasını herhangi bir metin editörü ile açıp, 

* print "Merhaba Dünya"

yazısı yerine 

* print "Merhaba Dünya, Merhaba"

yazıp kaydedin.

## 5. Commit ekleme
Dosyadaki değişiklikleri commit olarak eklemek için aşağıdaki komutları giriniz:

git add merhaba.py
git commit -m "İlk deneme, ilk commit"

## 6. Değişiklikleri Github'a göndermek
Yaptığınız değişiklikleri github'a göndermek için aşağıdaki iki komutu yazabilirsiniz.

git push origin master
git pull
