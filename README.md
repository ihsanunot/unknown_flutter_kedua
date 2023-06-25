# Belajar Flutter Layout

![preview](https://github.com/ihsanunot/unknown_flutter_kedua/assets/127992374/8bc9a944-f249-4fe3-9fe9-ae03e34c94b8)

- Identifikasi Row dan Column yang dibutuhkan
- Cek apa layout nya termasuk Grid?
- Cek Ada Elemen yang Overlapping atau tidak
- Apakai UI nya butuh Tabs?
- perhatikan area yang membutuhkan alignment, padding, or borders.

## Catatan

```
        // BAGIAN UTAMA HALAMAN !
        body: Column(
          children: [
            Image.asset(
              'images/gambar1.jpg',
              width: 600,
              height: 240,
              fit: BoxFit.cover,
            ),
            titleSection,
            buttonSection,
            textSection,
          ],
          // body pakai Column terus children biar bisa masukin beberapa widget mirip component lego
          // di dalam children kita berurutan section nya
```
