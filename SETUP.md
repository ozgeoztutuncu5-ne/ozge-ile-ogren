# GitHub'a Yükleme Talimatları

Bu belge, çarpım tablosu oyununu GitHub'a nasıl yükleyeceğinizi açıklar.

## 1. GitHub Repository Oluşturma

1. GitHub hesabınıza giriş yapın (https://github.com)
2. Sağ üst köşedeki "+" simgesine tıklayın
3. "New repository" seçeneğini seçin
4. Repository adı olarak `ozge-ile-ogren` girin
5. Açıklama: "İlkokul çocuklarına çarpım tablosunu öğreten interaktif oyun"
6. Repository'yi Public olarak ayarlayın (isteğe bağlı)
7. "Create repository" düğmesine tıklayın

## 2. Yerel Repository'i GitHub'a Bağlama

Repository oluşturduktan sonra, GitHub size verilen komutları çalıştırın:

```bash
cd /home/ubuntu/ozge-ile-ogren

# Remote repository'i ekle (YOUR_USERNAME yerine GitHub kullanıcı adınızı yazın)
git remote add origin https://github.com/YOUR_USERNAME/ozge-ile-ogren.git

# Ana branch'i main olarak ayarla
git branch -M main

# Dosyaları push et
git push -u origin main
```

## 3. SSH Anahtarı Kullanarak Push Etme (Opsiyonel)

Şifre girmek istemiyorsanız SSH anahtarı kullanabilirsiniz:

```bash
# SSH URL'sini kullan
git remote set-url origin git@github.com:YOUR_USERNAME/ozge-ile-ogren.git

# Push et
git push -u origin main
```

## 4. Başarılı Yükleme Kontrolü

Repository'nin GitHub'da başarıyla yüklendiğini kontrol edin:

1. GitHub'da repository sayfasına gidin
2. Tüm dosyaların görüldüğünü doğrulayın
3. README.md dosyasının düzgün görüntülendiğini kontrol edin

## 5. GitHub Pages ile Yayınlama (Opsiyonel)

Oyunu GitHub Pages aracılığıyla canlı olarak yayınlamak için:

1. Repository ayarlarına gidin (Settings)
2. Sol menüden "Pages" seçeneğini seçin
3. "Build and deployment" bölümünde:
   - Source: "GitHub Actions" seçin
   - Vite için önceden yapılandırılmış workflow'u seçin
4. Birkaç dakika sonra oyun şu adreste yayında olacak:
   - `https://YOUR_USERNAME.github.io/ozge-ile-ogren/`

## 6. Gelecekteki Güncellemeler

Oyunda değişiklik yaptıktan sonra GitHub'a yüklemek için:

```bash
# Değişiklikleri stage et
git add -A

# Commit yap
git commit -m "Açıklayıcı commit mesajı"

# Push et
git push origin main
```

## Sorun Giderme

### Kimlik Doğrulama Hatası
```bash
# Git kimlik bilgilerini ayarla
git config --global user.name "Adınız"
git config --global user.email "email@example.com"
```

### Remote URL Hatası
```bash
# Mevcut remote'i kontrol et
git remote -v

# Remote'i güncelle
git remote set-url origin https://github.com/YOUR_USERNAME/carpim-tablosu-oyunu.git
```

### Push Hatası
```bash
# Yerel değişiklikleri pull et
git pull origin main

# Çatışmaları çöz ve tekrar push et
git push origin main
```

## Ek Kaynaklar

- GitHub Docs: https://docs.github.com/
- Git Tutorial: https://git-scm.com/doc
- GitHub Pages: https://pages.github.com/

---

Sorularınız varsa, GitHub Issues aracılığıyla soru sorun!

