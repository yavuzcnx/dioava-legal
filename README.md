# dioava-legal

Dioava uygulamaları için merkezi yasal belge reposu (Gizlilik Politikası, Kullanım Koşulları vs.).

## Yapı

```
dioava-legal/
├── index.html              # Ana sayfa — tüm uygulamaların listesi
├── chloris/
│   ├── privacy-tr.html     # Chloris TR gizlilik politikası
│   └── privacy-en.html     # Chloris EN gizlilik politikası
└── dumenden/               # (Gelecekte — Dümenden için)
```

## GitHub Pages Kurulumu

1. GitHub'da yeni bir **public** repo oluştur: `dioava-legal`
2. Bu klasördeki dosyaları repo'ya push et
3. Repo **Settings → Pages**
4. **Source:** "Deploy from a branch" seç
5. **Branch:** `main` (veya `master`) / `/ (root)` seç
6. **Save**
7. 1-2 dakika bekle, yayınlanacak

## URL'ler

Kurulum sonrası URL'ler şöyle olacak (GitHub kullanıcı adını `yavuzcan` varsayıyorum):

- Ana sayfa: `https://yavuzcan.github.io/dioava-legal/`
- Chloris TR: `https://yavuzcan.github.io/dioava-legal/chloris/privacy-tr.html`
- Chloris EN: `https://yavuzcan.github.io/dioava-legal/chloris/privacy-en.html`

**Play Console'a yapıştırılacak URL (Chloris için):**
```
https://yavuzcan.github.io/dioava-legal/chloris/privacy-tr.html
```

## Notlar

- Politika metninde bir şey değişirse (yeni third-party servis, yeni özellik vs.) `privacy-tr.html` ve `privacy-en.html` dosyalarını güncelle ve "Son güncelleme" tarihini değiştir.
- Dümenden için ileride aynı yapıda `dumenden/privacy-tr.html` eklenebilir.
