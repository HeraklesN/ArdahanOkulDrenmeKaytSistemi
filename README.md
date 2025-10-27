# Ardahan Okul Dışı Öğrenme Kayıt Sistemi

Modern Android uygulaması ile eğitim kayıtlarınızı kolayca yönetin.

## 🚀 Proje Hakkında

Ardahan Okul Dışı Öğrenme Kayıt Sistemi, eğitim kurumlarının öğrenci kayıtlarını ve eğitim süreçlerini dijital ortamda yönetmelerini sağlayan modern bir Android uygulamasıdır.

## ✨ Özellikler

- **Öğrenci Kayıt Sistemi**: Öğrencilerinizi kolayca kaydedin ve bilgilerini güncelleyin
- **İlerleme Takibi**: Öğrencilerinizin eğitim ilerlemesini takip edin
- **Bulut Senkronizasyonu**: Firebase entegrasyonu ile verileriniz bulutta güvenle saklanır
- **Modern Arayüz**: Jetpack Compose ile tasarlanmış kullanıcı dostu arayüz
- **Güvenli Kimlik Doğrulama**: Firebase Authentication ile güvenli giriş sistemi
- **Web Entegrasyonu**: WebView desteği ile web tabanlı içeriklere erişim

## 🛠️ Teknolojiler

- **Android**: Native Android geliştirme
- **Kotlin**: Modern programlama dili
- **Jetpack Compose**: Modern UI toolkit
- **Firebase**: Backend servisleri
  - Firebase Database: Gerçek zamanlı veritabanı
  - Firebase Authentication: Kimlik doğrulama
- **Material Design 3**: Modern tasarım sistemi

## 📱 Proje Bilgileri

- **Paket Adı**: `com.example.ardahanokuldrenmekaytsistemi`
- **Versiyon**: 1.0
- **Min SDK**: 24 (Android 7.0)
- **Target SDK**: 36 (Android 14)
- **Compile SDK**: 36

## 🔧 Firebase Konfigürasyonu

- **Proje ID**: okul-disi-ogrenme
- **Database URL**: okul-disi-ogrenme-default-rtdb.europe-west1.firebasedatabase.app
- **Storage Bucket**: okul-disi-ogrenme.firebasestorage.app
- **Bölge**: Europe West 1

## 🚀 Kurulum

1. Projeyi klonlayın:
```bash
git clone https://github.com/yourusername/ArdahanOkulDrenmeKaytSistemi.git
```

2. Android Studio'da projeyi açın

3. Firebase konfigürasyonunu yapın:
   - Firebase Console'da yeni proje oluşturun
   - `google-services.json` dosyasını `app/` klasörüne ekleyin

4. Uygulamayı derleyin ve çalıştırın

## 📦 Bağımlılıklar

```kotlin
dependencies {
    implementation(libs.androidx.core.ktx)
    implementation(libs.androidx.lifecycle.runtime.ktx)
    implementation(libs.androidx.activity.compose)
    implementation(platform(libs.androidx.compose.bom))
    implementation(libs.androidx.ui)
    implementation(libs.androidx.ui.graphics)
    implementation(libs.androidx.ui.tooling.preview)
    implementation(libs.androidx.material3)
    
    // Firebase
    implementation(platform(libs.firebase.bom))
    implementation(libs.firebase.database.ktx)
    implementation(libs.firebase.auth.ktx)
    
    // WebView
    implementation(libs.accompanist.webview)
}
```

## 🎨 Ekran Görüntüleri

Uygulamanın ekran görüntüleri için [GitHub Pages](https://yourusername.github.io/ArdahanOkulDrenmeKaytSistemi/) sayfasını ziyaret edin.

## 📄 Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Detaylar için [LICENSE](LICENSE) dosyasına bakın.

## 👨‍💻 Geliştirici

- **Ad**: [Geliştirici Adı]
- **Email**: [email@example.com]
- **GitHub**: [@yourusername](https://github.com/yourusername)

## 🤝 Katkıda Bulunma

1. Bu projeyi fork edin
2. Feature branch oluşturun (`git checkout -b feature/AmazingFeature`)
3. Değişikliklerinizi commit edin (`git commit -m 'Add some AmazingFeature'`)
4. Branch'inizi push edin (`git push origin feature/AmazingFeature`)
5. Pull Request oluşturun

## 📞 İletişim

Proje hakkında sorularınız için [email@example.com](mailto:email@example.com) adresinden bana ulaşabilirsiniz.

## 🙏 Teşekkürler

- Firebase ekibine harika backend servisleri için
- Android ekibine Jetpack Compose için
- Açık kaynak topluluğuna katkıları için

---

⭐ Bu projeyi beğendiyseniz yıldız vermeyi unutmayın!
