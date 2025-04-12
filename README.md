# Diode

. Sistemi Güncelle
```
sudo apt update && sudo apt upgrade -y
```

### 🔹 2. Snap Paket Yöneticisi Kurulu mu Kontrol Et
(Genellikle Ubuntu’da yüklüdür, ama emin olalım)
```
sudo apt install snapd -y
```


### 🔹 3. Diode Node Paketini Kur
```
sudo snap install diode-node
```
Kurulumdan sonra diode-node arka planda çalışmaya başlar.



### 🔹 4. Düğüm Bilgilerini Kontrol Et
```
diode-node.info
```
Bu komut, düğümünüzün kimliği, bağlı olduğu ağ, çalışma durumu gibi bilgileri gösterir.



### 🔹 5. Diode İstemcisiyle Örnek Bir Web Yayını (İsteğe Bağlı)

Bir dizini Diode Ağı üzerinden yayınlamak istersen:
```
mkdir mysite
echo "Hello Diode" > mysite/index.html
diode publish mysite
```
Bu işlemden sonra sana özel bir *.diode.link URL’si oluşur. Web tarayıcında bu adresi ziyaret ederek içeriğini görebilirsin.


### 🔹 6. (İsteğe Bağlı) Düğüm Sürekli Çalışsın Diye Logları İzle
```
journalctl -u snap.diode-node.daemon -f
```
Bu komutla arka plandaki düğüm loglarını takip edebilirsin.


#### Diode 

https://diode.io/joinzone/#close

- Sağ yukardan get app diyelim. uygun olanı indir kur ( kendi pcmiz yerine baska bir yere indirebilrisek daha iyi olur sınucta test ben uyarayımda)

![image](https://github.com/user-attachments/assets/625589b0-4a88-42de-a6dc-473c5ed415aa)

- Kurduk açtık isim yazdık kaydolduk sonra aşağıdaki şekilde yeni zone bağlanıyoruz. Burada sync uzun sürebilir dismiss diyip atlayalım.

![joincode-entry-example](https://github.com/user-attachments/assets/0a61fb5e-af27-4f0b-9ddc-001c33b455b2)


#### Platforma bağlanalım cüzdan bağlayalım

- https://diodenetwork.io/app/  adresine gidelim ve sıfır bir evm cüzdan olusturalım bağlıyalım. Bundan sonraki işlemlere masaüstünden devam.





