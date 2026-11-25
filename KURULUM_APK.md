# Kelime Tombala — PC'ye Kurulum Yapmadan APK Oluşturma Rehberi

Bilgisayarında yönetici izni olmadan, sadece tarayıcı üzerinden 3 dakikada telefonuna kurabileceğin `.apk` dosyasını oluşturabilirsin:

1. **GitHub hesabı aç (ücretsiz):** https://github.com adresine girip giriş yap.
2. **Yeni depo (Repository) oluştur:** Sağ üstteki `+` → **New repository** de, adını örneğin `kelime-tombala` yap ve **Create repository** butonuna tıkla.
3. **Dosyaları tarayıcıdan yükle:**
   - İndirdiğin `kelime-tombala-android.zip` dosyasını aç.
   - GitHub'da **uploading an existing file** linkine tıkla ve klasörün içindeki tüm dosya ve klasörleri (`.github` klasörü dahil!) sürükleyip bırak, ardından **Commit changes** de.
4. **APK'yı indir ve telefona kur:**
   - Depoda üst menüden **Actions** sekmesine tıkla.
   - **Build Android APK** işleminin yeşil tik olmasını bekle (~2 dakika).
   - İşlemin içine gir, en alttaki **Artifacts** bölümünden **kelime-tombala-apk** dosyasına tıklayıp indir.
   - İnen zip içindeki `app-debug.apk` dosyasını Android telefonuna gönder (WhatsApp / Google Drive / USB) ve üzerine dokunup kur ("Bilinmeyen uygulamalara izin ver" uyarısı çıkarsa onaylayabilirsin).

## İleride Yeni Özellik Eklemek
Yeni bir özellik istediğinde sadece `app/src/main/assets/index.html` dosyasını güncellemen yeterli; GitHub birkaç dakika içinde güncel APK'yı otomatik üretir.
