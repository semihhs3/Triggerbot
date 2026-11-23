# HvH Triggerbot (Fabric 1.20.1)

- **R** tuşu: menüyü açar / kapatır (Ayarlar > Kontroller'den değiştirilebilir)
- Menüde: Triggerbot aç/kapa, **Delay (0–500 ms)**, Cooldown bekle, Sadece oyuncular
- Ayarlar `config/hvhtrigger.properties` dosyasına kaydedilir

## GitHub'da derleme
1. Bu klasörün içeriğini yeni bir repoya yükle (`.github` klasörü dahil).
2. **Actions** sekmesi > `build` workflow'u otomatik çalışır.
3. Bittiğinde **Artifacts > hvh-triggerbot** indir, içindeki `hvh-triggerbot-1.0.0.jar` dosyasını `mods` klasörüne at.
4. Fabric Loader 0.15+ ve Fabric API 0.92.2+1.20.1 gerekli.

## Yerelde derleme
Gradle 8.7 ve Java 17 ile: `gradle build` -> `build/libs/`
