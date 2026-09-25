# nextself-audio-ru

NextSelf uygulamasının Rusça B1+ ders sesleri. Uygulama bu dosyaları tek tek indirir
(`ru/<ilk iki hex>/<anahtar>.mp3`, mono mp3); anahtar, seslendirilen metnin
sha1 özetinin ilk 16 hanesidir.

## Ses modeli ve lisans

- **Silero TTS** (v5_cis_base, ru_oksana) — MIT — https://github.com/snakers4/silero-models

Kayıtlar bu ses modeliyle üretilmiştir; metinler NextSelf müfredatına aittir.

## Doğrulama

`SHA256SUMS.txt` tüm dosyaların özetini taşır: `shasum -c SHA256SUMS.txt`
