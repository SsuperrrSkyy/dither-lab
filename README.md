# dither-lab

Demo web: latar luar angkasa + planet dithered + warp lorong (WebGL2, satu file, tanpa dependensi).

- Interaksi: klik untuk masuk (audio aktif), tahan di mana saja untuk warp bertahap sampai x60,
  klik/tahan kontrol kanan-bawah untuk basis kecepatan x1..x20, LEARN MORE untuk panel info.
- Semua knob ada di blok `CONFIG` di dalam `index.html` (brand, palet, kepadatan bintang, warp).

Teknik (shape-dither Bayer 8x8, warp starfield, bloom, chromatic aberration) dipelajari dari
analisis publik situs astrodither.robertborghesi.is; semua visual prosedural, tanpa aset pihak lain.
