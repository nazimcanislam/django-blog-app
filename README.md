# Django Blog Uygulaması

![intro](media/intro.png)

Python Django ile yaptığım küçük çaplı bir blog uygulaması. Basit, kolay ve hızlı...

## Bu bloğun özellikleri:
- Giriş/Kayıt
- Gönderi paylaşma
- Gönderi silme
- Gönderi düzenleme
- Profil düzenlemesi
- Şifremi unuttum (mail adresi gerekli)

## Kurulum ve sunucuyu çalıştırma

#### Öncelikle bir sanal ortam oluşturmakla başlayalım
```bash
python3 -m pip install virtualenv
python3 -m virtualenv venv
```

#### Sanal ortamı çalıştır
`Windows`
```bash
venv\Scripts\activate
```
`Linux` ve `macOS`
```
source venv/bin/activate
```

#### Son olarak kütüphaneleri yükle
```bash
python3 -m pip install -r requirements.txt
```


## Blog ugulamasını yerel olarak çalıştırma
```bash
python3 manage.py runserver
```

## Şifremi unuttum için mail adresi
Kök dizinde bulunan `email_user.txt` dosyasına içinde belirtildiği gibi bir `gmail` adresi ve `şifresi` girilmeli. Neden özellikle gmail? Çünkü bu proje mail sunucusu olarak `smtp.gmail.com` kullanıyor.
