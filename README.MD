
```markdown
# Telegram Bot Soru Cevap

Bu projede, Telegram üzerinden bir bot aracılığıyla rastgele sorular soran bir uygulama geliştirilmiştir. Bot, kullanıcılara çeşitli soruları göndererek etkileşim sağlamaktadır.

## Nasıl Çalışır?

- Botunuzun bir Telegram botu olması gerekmektedir. Bot tokenini `main` fonksiyonunda belirtmelisiniz.
- Bot, `python-telegram-bot` kütüphanesini kullanmaktadır. Bu kütüphaneyi yüklemek için `pip install python-telegram-bot` yada `pip install python-telegram-bot==13.7` komutunu kullanabilirsiniz.
- Kod içerisindeki `soru` fonksiyonu, `/soru` komutuna yanıt olarak rastgele bir soru seçer ve kullanıcıya gönderir.
- Botunuzu çalıştırmak için `main` fonksiyonunu kullanabilirsiniz.

## Gereksinimler

- Python 3.x
- `python-telegram-bot` kütüphanesi

## Kurulum

1. Bu depoyu klonlayın:

```
git clone https://github.com/KULLANICI_ADINIZ/PROJE_ADINIZ.git
```

2. Python paketlerini yükleyin:

```
pip install python-telegram-bot
```

3. `main.py` dosyasında yer alan `token` değişkenini kendi Telegram bot tokeninizle güncelleyin.

4. Kodu çalıştırın:

```
python main.py
```

## Katkıda Bulunma

1. Bu depoyu fork edin.
2. Yeni bir dal (branch) oluşturun: `git checkout -b yeni-ozellik`
3. Değişikliklerinizi yapın ve bunları commit edin: `git commit -am 'Yeni özellik ekle'`
4. Dalınıza itmek için: `git push origin yeni-ozellik`
5. Bir Pull Talebi (Pull Request) oluşturun.

## Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Daha fazla bilgi için [LİSANS](LISANS) dosyasını inceleyebilirsiniz.
```

