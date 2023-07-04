# Telegram Soru Botu

Bu proje, Telegram üzerinden rastgele soruları kullanıcılara gönderen bir Telegram botunu içerir. Bot, belirli bir komutla çağrıldığında rastgele bir soru seçer ve kullanıcıya gönderir.

## Nasıl Çalışır?

1. Python'un en son sürümünü indirin ve yükleyin.

2. `python-telegram-bot` kütüphanesini yükleyin. Bunun için terminale aşağıdaki komutu yazabilirsiniz:
   ```
   pip install python-telegram-bot
   ```

3. Telegram botunuzun API erişim belirtecini alın. Bunun için [BotFather](https://core.telegram.org/bots#botfather) ile konuşarak bir bot oluşturun ve erişim belirtecini alın.

4. `main.py` dosyasını düzenleyin ve `token` değişkenine botunuzun erişim belirtecini ekleyin.

5. Terminale aşağıdaki komutu yazarak botu çalıştırın:
   ```
   python bot.py
   ```

6. Bot çalışır duruma geldiğinde, Telegram'da botunuzun adını veya kullanıcı adını aratarak botunuzu bulabilir ve kullanmaya başlayabilirsiniz.

## Komutlar

Botunuz, aşağıdaki komutu tanır:

- `/soru`: Bu komutu gönderdiğinizde, bot rastgele bir soru seçer ve size gönderir.

## Soruları Düzenleme

Soru listesi `sorular` adlı bir liste içinde tanımlanmıştır. İstediğiniz soru sayısını ekleyebilir, çıkarabilir veya düzenleyebilirsiniz. Her çalıştırmada, bot rastgele bir soruyu seçecektir.

```python
sorular = [
    "En romantik anınız nedir?",
    "Bir ilişkide en önemli özellik nedir?",
    "En unutulmaz ilk buluşmanız nasıl geçti?",
    "Birlikte yapmaktan en çok keyif aldığınız etkinlik nedir?",
    "Hayalinizdeki tatil yerini anlatır mısınız?",
    "En sevdiğiniz aşk şarkısı hangisi?"
]


---

