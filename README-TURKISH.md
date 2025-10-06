# UVdesk Community Edition - Türkçe Sürümü

Bu UVdesk Community Edition'un tamamen Türkçeleştirilmiş halidir.

## Değişiklikler

### 🇹🇷 Dil Ayarları
- Varsayılan dil Türkçe olarak ayarlandı
- Tüm çeviriler Türkçe'ye çevrildi
- URL yapıları Türkçe'ye çevrildi (/en/ → /tr/)

### 📁 Çeviri Dosyaları
- `translations/messages.tr.yml` - Tam Türkçe çeviriler
- Tüm UI elementleri Türkçeleştirildi
- Hata mesajları Türkçe'ye çevrildi

### ⚙️ Konfigürasyon Değişiklikleri
- `config/services.yaml` - locale: 'tr'
- `config/packages/translation.yaml` - default_locale: tr
- `public/scripts/wizard.js` - URL prefix'leri Türkçe
- `templates/base.html.twig` - Sayfa başlıkları Türkçe

## Kurulum

1. Bu klasörü web sunucunuzun root dizinine kopyalayın
2. Composer ile bağımlılıkları yükleyin:
   ```bash
   composer install
   ```
3. Veritabanı ayarlarını yapılandırın
4. Web kurulum sihirbazını çalıştırın

## Özellikler

✅ **Tam Türkçe Arayüz** - Tüm menüler, butonlar ve mesajlar Türkçe
✅ **Türkçe URL Yapısı** - SEO dostu Türkçe URL'ler
✅ **Yerelleştirilmiş Tarih/Saat** - Türkiye saat dilimi desteği
✅ **Türkçe E-posta Şablonları** - Otomatik e-postalar Türkçe
✅ **Türkçe Raporlama** - Raporlar ve analizler Türkçe

## Destek

Bu Türkçeleştirilmiş sürüm orijinal UVdesk Community Edition v1.1.8 tabanlıdır.
Teknik destek için UVdesk'in resmi dokümantasyonunu inceleyebilirsiniz.

## Lisans

UVdesk Community Edition ile aynı lisans koşulları geçerlidir.