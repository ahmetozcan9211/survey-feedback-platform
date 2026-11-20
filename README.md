# Kurumsal Anket ve Geri Bildirim Platformu

Müşteri memnuniyeti ve ürün geri bildirimi toplamak için geliştirilmiş, çok dilli (TR/EN) kurumsal anket sistemi. Yanıtlar, bir otomasyon aracılığıyla ilgili ekibe anlık bildirilir.

> Bu depo bir proje vitrinidir. Kaynak kod paylaşılmamaktadır.

## Özellikler

- **Dinamik anket editörü:** Çoktan seçmeli, puanlama ve metin soruları; soru sıralaması ve zorunluluk ayarları
- **Tek tıkla çeviri:** Anket soruları Türkçe ile İngilizce arasında otomatik çevrilir
- **Bot koruması:** Matematiksel CAPTCHA ve istek sınırlama (rate limit)
- **KVKK uyumu:** Entegre onay metni ve modal
- **PDF çıktıları:** Tüm yanıtları içeren toplu tablo ve her yanıt için ayrı ayrıntılı form, tam Türkçe karakter desteğiyle
- **Yönetici paneli:** Yanıt takibi, anket yönetimi, istatistikler
- **Sunucu tarafı doğrulama:** Tüm girdiler Zod şemalarıyla doğrulanır

## Teknolojiler

`Vue 3` · `Vite` · `Vue Router` · `jsPDF` · `Node.js` · `Express` · `Prisma` · `SQLite` · `Zod` · `TypeScript`
