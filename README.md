# Twitter Giriş Ekranı

Bu proje, bir Twitter benzeri bir web uygulaması için bir giriş ekranı tasarlamak amacıyla oluşturulmuştur. Bu giriş ekranı, kullanıcıların Twitter hesaplarıyla oturum açmalarına izin vermektedir.

## Önizleme

![Giriş Ekranı](https://github.com/ufukcagris/twitter_login_screen/assets/51057559/9ea7fc99-4402-457d-b191-7223d933aa77)

## Özellikler

- Kullanıcıların Twitter hesaplarıyla oturum açmasını sağlar.
- Oturum açan kullanıcının adını ve profil resmini görüntüler.
- Oturum açma işlemi başarılıysa, kullanıcıyı ana sayfaya yönlendirir.
- Twitter API'si ile etkileşim kurar ve yetkilendirme sağlar.

## Nasıl Kullanılır?

1. İlk adımda, bu projeyi kendi bilgisayarınıza klonlamalısınız. Bunun için aşağıdaki komutu kullanabilirsiniz:

```shell
git clone https://github.com/ufukcagris/twitter_login_screen.git
```

2. Proje klasörüne gidin:
```shell
cd twitter_login_screen
```

3. Ana dizinde bir `.env` dosyası oluşturun ve aşağıdaki değişkenleri ekleyin:
```shell
API_KEY=your_twitter_api_key
API_SECRET=your_twitter_api_secret
CALLBACK_URL=http://localhost:3000/callback
```

Lütfen `your_twitter_api_key` ve `your_twitter_api_secret` değerlerini, kendi Twitter API anahtarlarınızla değiştirin.

4. Gerekli bağımlılıkları yüklemek için aşağıdaki komutu çalıştırın:
```shell
npm install
```

5. Uygulamayı başlatmak için aşağıdaki komutu kullanın:
```shell
npm start
```

6. Tarayıcınızda `http://localhost:3000` adresine gidin ve giriş ekranını görüntüleyin.

## Katkıda Bulunma

Bu projeye katkıda bulunmak isterseniz, aşağıdaki adımları izleyin:

1. Bu projeyi fork edin.
2. Kendi çalışma ortamınızda projeyi geliştirin.
3. Değişikliklerinizi commit'leyin ve push'layın.
4. Yeni bir pull talebi oluşturun.

## Lisans

Bu projenin lisans bilgileri için lütfen [LICENSE](LICENSE) dosyasına bakın.

---

Bu Readme dosyası, projenin amacı ve nasıl kullanılacağı hakkında bilgi sağlamak için oluşturulmuştur. Herhangi bir sorunuz varsa, lütfen iletişime geçmekten çekinmeyin. İyi kullanımlar!




