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

## Blog ugulamasını yerel olarak çalıştırma
```bash
python3 manage.py runserver
```

## Şifremi unuttum için mail adresi
Kök dizinde bulunan `email_user.txt` dosyasına içinde belirtildiği gibi bir `gmail` adresi ve `şifresi` girilmeli. Neden özellikle gmail? Çünkü bu proje mail sunucusu olarak `smtp.gmail.com` kullanıyor.
