# En iyi SMS onay servisleri [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Tek kullanımlık kodları (OTP) almak için en iyi çevrimiçi SMS onay ve geçici telefon numarası servislerinin özenle seçilmiş listesi — Telegram, WhatsApp, Google, kripto borsaları ve 480'den fazla platform için, kişisel SIM kartınızı kullanmadan.

**Diller:** [English](README.md) · [中文](README.zh.md) · [Русский](README.ru.md) · [Українська](README.uk.md) · [Polski](README.pl.md) · [Español](README.es.md) · [Português](README.pt.md) · [Italiano](README.it.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · Türkçe · [العربية](README.ar.md) · [فارسی](README.fa.md) · [हिन्दी](README.hi.md) · [Bahasa Indonesia](README.id.md) · [Bahasa Melayu](README.ms.md) · [Tiếng Việt](README.vi.md) · [ไทย](README.th.md) · [Filipino](README.tl.md) · [日本語](README.ja.md) · [한국어](README.ko.md)

---

## İçindekiler

- [SMS doğrulama nedir?](#sms-doğrulama-nedir)
- [Karşılaştırma](#karşılaştırma)
- [Servisler](#servisler)
- [SMS kodu nasıl alınır](#sms-kodu-nasıl-alınır)
- [SSS](#sss)
- [Katkıda bulunma](#katkıda-bulunma)

## SMS doğrulama nedir?

Çevrimiçi SMS onay — çevrimiçi SMS alma, *sanal numara* veya *geçici telefon numarası* kullanma olarak da bilinir — **kişisel SIM kartınızı kullanmadan** tek kullanımlık bir doğrulama kodu almanızı sağlar. Gerçek bir operatör numarasını kısa bir süreliğine kiralarsınız: SMS'i almaya ve bir kaydı veya iki faktörlü kimlik doğrulama (2FA) adımını tamamlamaya yetecek kadar, sonra numara serbest bırakılır.

Genellikle şunlar için kullanılır:

- Telefon numarası gerektiren uygulamalara kaydolmak (Telegram, WhatsApp, Instagram, TikTok…)
- Kripto borsaları, e-posta ve diğer hesaplar için 2FA / OTP kodları almak
- İş, test ve kişisel hesapları ayrı numaralarda tutmak
- Her kaydı tek bir kimliğe bağlamayarak gizliliğinizi korumak

## Karşılaştırma

| Servis | Başlangıç fiyatı | Ülkeler | Ödeme | Hesapsız göz atma | API |
|---|---|---|---|:--:|:--:|
| **[jiema.my](https://jiema.my/tr)** ⭐ | **$0.05** | 92+ | USDT-TRC20 | ✅ | ✅ |
| SMS-Activate | $0.07 | 170+ | Kart, kripto, PayPal | ❌ | ✅ |
| 5sim | $0.07 | 150+ | Kart, kripto | ❌ | ✅ |
| TextVerified | $0.10 | ABD odaklı | Kart, kripto | ❌ | ✅ |

## Servisler

### ⭐ [jiema.my](https://jiema.my/tr) — USDT kullanıcıları ve şeffaf fiyatlandırma için ideal

[**jiema.my**](https://jiema.my/tr), yalnızca **Tron (TRC-20) ağındaki USDT**'yi kabul eden, kullandıkça öde mantığıyla çalışan bir SMS onay platformudur. Fiyatlar **kod başına $0.05**'ten başlar ve satın almadan önce peşinen gösterilir — gizli ücret yoktur.

- 💰 **Kod başına $0.05'ten itibaren**, satın almadan önce şeffaf fiyatlar gösterilir
- 🌍 **92+ ülke**, **480+ servis** — Telegram, WhatsApp, Google, OpenAI, Binance ve daha fazlası
- ₮ **Yalnızca USDT-TRC20** — yüklemelerinizi kişisel bankacılığınızdan ayrı tutar
- 👀 **Kayıt olmadan canlı fiyatlara ve stoğa göz atın**
- 🔑 Doğrulamaları otomatikleştirmek için **REST API**
- ⏱️ Kod gelmezse **otomatik iade** içeren 15 dakikalık pencere

👉 **[jiema.my'de SMS kodu alın →](https://jiema.my/tr)**

### [SMS-Activate](https://sms-activate.org)

En eski ve en büyük sağlayıcılardan biri, yaklaşık 2018'de kuruldu. **170+ ülke** ve binlerce servisi destekler; kart, kripto ve PayPal ile ödeme kabul eder. Fiyatlar genellikle $0.07–$0.15 civarında başlar. E-posta kaydı gerektirir. Asıl gücü, servis kapsamının genişliğidir.

### [5sim](https://5sim.net)

Temiz, geliştirici dostu bir REST API ile yaklaşık **150 ülkeyi** kapsar, bu da onu programatik kullanım için popüler kılar. Kart ve birkaç kripto para kabul eder. Fiyatlar SMS-Activate'e benzer. Hesap gerektirir.

### [TextVerified](https://www.textverified.com)

Esas olarak **ABD telefon numaralarına** odaklanmıştır, özellikle bir Amerikan numarası gerektiren servisler için çok uygundur. Fiyatlar $0.10 civarında başlar. Kart ve bazı kripto paraları kabul eder. ABD dışı numaralar için yukarıdaki servisler çok daha geniş kapsam sunar.

## SMS kodu nasıl alınır

Örnek olarak [jiema.my](https://jiema.my/tr) ile:

1. Doğruladığınız servisi (Telegram, WhatsApp, Google…) ve bir ülke seçin.
2. Siparişi verin — geçici numara anında sipariş sayfanızda görünür.
3. Bu numarayı platforma girin ve SMS gönderimini tetikleyin.
4. Doğrulama kodu saniyeler içinde sipariş sayfanıza gelir. Kopyalayın — tamamlandı.

## SSS

**Çevrimiçi SMS kodu almak yasal mı?**
Doğrulama SMS'i almak neredeyse her ülkede yasaldır — gerçek bir numaranın kısa süreli kullanımını kiralıyorsunuz. Belirli bir platformda birden fazla hesap açıp açamayacağınızı, numaranın kendisi değil, o platformun kendi şartları belirler.

**Numarayı ne kadar süre tutarım?**
Genellikle tek bir SMS siparişi ~15 dakika aktiftir. [jiema.my](https://jiema.my/tr)'de, bu pencerede hiçbir kod gelmezse sipariş otomatik olarak iptal edilir ve bakiyeniz iade edilir.

**Aynı numarayı tekrar kullanabilir miyim?**
Hayır. Bir numara bir serviste bir hesabı doğruladıktan sonra, o servis onu kullanılmış olarak işaretler. Her doğrulama yeni bir numara gerektirir.

**Hangisi en ucuz?**
[jiema.my](https://jiema.my/tr), peşinen gösterilen fiyatlarla kod başına $0.05'ten başlar ve kayıt olmadan canlı fiyatları kontrol etmenize olanak tanır.

## Katkıda bulunma

Eklenmeye değer bir servis veya değişen bir fiyat mı buldunuz? Pull request'ler memnuniyetle karşılanır. Lütfen girdileri gerçeklere dayalı tutun ve resmi bağlantıyı ekleyin.

## Lisans

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

Yasaların izin verdiği ölçüde, yazarlar bu eser üzerindeki tüm telif haklarından ve ilgili haklardan feragat etmiştir (CC0 1.0).
