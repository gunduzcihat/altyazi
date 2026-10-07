# Altyazı

YouTube videolarını eş zamanlı Türkçe altyazıyla izlemek için tek sayfalık, kişisel bir web uygulaması.

- Bağlantıyı yapıştır, video açılır; konuşulan satır videonun hemen altında Türkçe görünür.
- Çeviriyi Google Gemini yapar: videoyu dinler, bölüm bölüm (ilk 1 dk, sonra 5'er dk) altyazı üretir. İzlediğin yerin yaklaşık 5 dakika ilerisi hazır tutulur.
- Çevrilen video cihazda saklanır; ikinci izleyişte yeniden çevrilmez.
- Sunucu yok. Gemini anahtarı yalnızca cihazın tarayıcı deposunda durur, bu depoda yer almaz.

## Kurulum
1. Sayfayı telefonda aç, "Ana ekrana ekle".
2. Ana ekrandaki uygulamayı aç, Gemini anahtarını gir (aistudio.google.com/apikey).

## Dosyalar
- `index.html`: uygulamanın tamamı
- `manifest.webmanifest`, `icons/`: ana ekran kısayolu
- `fonts/`: Atkinson Hyperlegible Next (SIL OFL 1.1)
