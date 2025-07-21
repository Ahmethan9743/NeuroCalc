# Flexi Calc Flutter

## English

**Flexi Calc Flutter** is a multi-platform calculator application developed with Flutter. It supports basic and scientific calculations, theme switching (light/dark), language switching (Turkish/English), and voice input/output features. The app is designed for Windows, Web, Android, and iOS platforms.

### Features

- **Basic Calculator:** Addition, subtraction, multiplication, division, percent, reciprocal, square, square root, sign change, and more.
- **Scientific Calculator:** Trigonometric functions (sin, cos, tan, cot, sec, cosec, arcsin, arccos, arctan, arccot, arcsec, arccosec), π input, and advanced calculations.
- **Theme Support:** Switch between light and dark themes.
- **Language Support:** Switch between Turkish and English.
- **Voice Input/Output:** Calculate by speaking and listen to results (supported platforms).
- **Plugin System:** Add and manage custom plugins (for future development).
- **Cross-Platform:** Works on Windows, Web, Android, and iOS.

### Project Structure

- `lib/main.dart`: Main application code, UI, and logic for both basic and scientific calculators.
- `assets/`: Icons, sounds, and translation files.
- `test/`: Widget and unit tests.
- `android/`, `ios/`, `web/`, `windows/`, `linux/`, `macos/`: Platform-specific files.

### How to Run

1. **Install Flutter SDK** and set up your environment ([Flutter Install Guide](https://docs.flutter.dev/get-started/install)).
2. **Clone this repository** to your computer.
3. **Install dependencies:**
   ```sh
   flutter pub get
   ```
4. **Run on your desired platform:**
   - Windows: `flutter run -d windows`
   - Web: `flutter run -d chrome`
   - Android: `flutter run -d android`
   - iOS: `flutter run -d ios` (on macOS)
5. **Switch theme or language** from the app drawer.
6. **Use the scientific calculator** from the drawer menu.

### Notes

- For voice features, microphone permissions are required.
- On Windows, you may need to install [Visual Studio](https://visualstudio.microsoft.com/) with "Desktop development with C++" and ensure `nuget.exe` is in your PATH.
- For Android/iOS, set up emulators or connect a real device.

---

## Türkçe

**Flexi Calc Flutter**, Flutter ile geliştirilmiş çok platformlu bir hesap makinesi uygulamasıdır. Temel ve bilimsel hesaplama, tema değiştirme (açık/koyu), dil değiştirme (Türkçe/İngilizce) ve sesli giriş/çıkış özelliklerini destekler. Uygulama Windows, Web, Android ve iOS platformlarında çalışır.

### Özellikler

- **Temel Hesap Makinesi:** Toplama, çıkarma, çarpma, bölme, yüzde, ters alma, karesini alma, karekök, işaret değiştirme ve daha fazlası.
- **Bilimsel Hesap Makinesi:** Trigonometrik fonksiyonlar (sin, cos, tan, cot, sec, cosec, arcsin, arccos, arctan, arccot, arcsec, arccosec), π girişi ve gelişmiş hesaplamalar.
- **Tema Desteği:** Açık ve koyu tema arasında geçiş yapabilirsiniz.
- **Dil Desteği:** Türkçe ve İngilizce arasında geçiş yapabilirsiniz.
- **Sesli Giriş/Çıkış:** Konuşarak hesap yapabilir ve sonucu dinleyebilirsiniz (desteklenen platformlarda).
- **Eklenti Sistemi:** Kendi eklentilerinizi ekleyip yönetebilirsiniz (geliştirilecek).
- **Çoklu Platform:** Windows, Web, Android ve iOS üzerinde çalışır.

### Proje Yapısı

- `lib/main.dart`: Ana uygulama kodu, arayüz ve temel/bilimsel hesap makinesi mantığı.
- `assets/`: İkonlar, sesler ve çeviri dosyaları.
- `test/`: Widget ve birim testleri.
- `android/`, `ios/`, `web/`, `windows/`, `linux/`, `macos/`: Platforma özel dosyalar.

### Nasıl Çalıştırılır?

1. **Flutter SDK'yı kurun** ve ortamınızı hazırlayın ([Flutter Kurulum Rehberi](https://docs.flutter.dev/get-started/install)).
2. **Bu depoyu bilgisayarınıza klonlayın.**
3. **Bağımlılıkları yükleyin:**
   ```sh
   flutter pub get
   ```
4. **İstediğiniz platformda çalıştırın:**
   - Windows: `flutter run -d windows`
   - Web: `flutter run -d chrome`
   - Android: `flutter run -d android`
   - iOS: `flutter run -d ios` (sadece macOS'ta)
5. **Tema veya dili** uygulama menüsünden değiştirebilirsiniz.
6. **Bilimsel hesap makinesine** menüden ulaşabilirsiniz.

### Notlar

- Sesli özellikler için mikrofon izni gereklidir.
- Windows'ta, [Visual Studio](https://visualstudio.microsoft.com/) "Desktop development with C++" yüklü olmalı ve `nuget.exe` PATH'e eklenmelidir.
- Android/iOS için emülatör kurabilir veya gerçek cihaz bağlayabilirsiniz.

---

**Contact / İletişim:**  
Her türlü soru ve katkı için lütfen GitHub üzerinden iletişime geçin.