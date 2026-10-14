# Harcama Takip

Basit, tek sayfalık harcama takip uygulaması. Günlük harcama limiti belirleyebilir, her harcamaya isim/tutar/tarih/not ekleyebilirsin. Veriler tarayıcının `localStorage`'ında, yani sadece kullandığın cihazda/tarayıcıda saklanır.

## Yerelde çalıştırma

Ekstra kuruluma gerek yok. `index.html` dosyasını herhangi bir tarayıcıda çift tıklayarak açman yeterli.

## GitHub'a yükleme

```bash
git init
git add .
git commit -m "İlk sürüm: harcama takip uygulaması"
git branch -M main
git remote add origin https://github.com/KULLANICI_ADIN/REPO_ADIN.git
git push -u origin main
```

## GitHub Pages ile yayınlama (ücretsiz, internetten erişilebilir link)

1. GitHub'da reponu aç → **Settings** → sol menüden **Pages**.
2. "Build and deployment" altında **Source** olarak **Deploy from a branch** seç.
3. **Branch** kısmında `main` ve klasör olarak `/ (root)` seç, **Save**'e bas.
3. Birkaç dakika içinde uygulaman şu adreste yayında olacak:
   `https://KULLANICI_ADIN.github.io/REPO_ADIN/`

## Not

Veriler cihaza özel olduğu için farklı bir tarayıcı veya cihazdan açtığında harcama geçmişini görmezsin. Birden fazla cihazdan senkron erişim istersen bir backend/veritabanı eklemek gerekir — istersen bu konuda da yardımcı olabilirim.
