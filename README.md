# Kelime Kartları: doğal ses dosyaları

Kelime Kartları uygulamasının (web ve Android) kelime ve örnek cümle seslendirmeleri. Dosyalar uygulama tarafından
doğrudan okunur; elle bakılacak bir içerik yoktur.

- `en-us/` İngilizce, Amerikan aksanı · `en-gb/` İngilizce, İngiliz aksanı · `de/` Almanca
- Dosya adı: `sha1("<ses>|<metin>")` değerinin ilk 20 onaltılık hanesi, `.mp3`

## Kullanılan modeller ve lisanslar

- İngilizce: [Kokoro-82M](https://huggingface.co/hexgrad/Kokoro-82M) (Apache-2.0), sesler `af_heart` ve `bf_emma`
- Almanca: [Piper](https://github.com/rhasspy/piper) Thorsten (medium) sesi; veri kümesi [Thorsten-Voice](https://github.com/thorstenMueller/Thorsten-Voice) (CC0)