# Sevde Portfolio

React + Vite ile hazırlanmış, Türkçe/İngilizce destekli kişisel portfolyo sitesi.

## Çalıştırma

```bash
npm install
npm run dev
```

## CV dosyası

CV PDF dosyası `public/cv/NakiyeSevdeSADIK_cv_.pdf` konumunda bulunmalıdır. Bu projeye eklenen PDF, daha önce paylaşılan CV dosyasından alınmıştır. Farklı/güncel bir CV kullanmak istersen aynı isimle bu dosyanın üzerine kopyalayabilirsin.

CV sayfası `/#cv` adresinden açılır. İndirme butonu PDF dosyasını indirir.

## Proje detayları

Ana sayfadaki proje kartları `/#project/ai-kombin`, `/#project/robark` ve `/#project/netagroup` adreslerinde ayrı detay görünümleri açar. Proje içerikleri `src/App.jsx` içindeki `content.tr.items` ve `content.en.items` alanlarından düzenlenebilir.

## Kişiselleştirme

- Hakkımda metni: `src/App.jsx` içindeki `content` nesnesi
- Yetenekler: `skills` dizisi
- Proje detayları: `content.tr.items` ve `content.en.items`
- E-posta, GitHub ve LinkedIn adresleri: `src/App.jsx` içinde `hello@example.com`, `https://github.com/` ve `https://www.linkedin.com/` değerlerini değiştir.
