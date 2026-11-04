# lapakin-rilis

Rilis internal Lapakin: installer dan SHA256SUMS, tanpa kode sumber. Fitur Cek Update di Lapakin membaca rilis terbaru di repo ini.

Setiap rilis wajib berisi dua berkas dari folder dist/ hasil npm run build:installer, yaitu Lapakin-Setup-<versi>.exe dan SHA256SUMS.txt.

Tag rilis ditulis vX.Y.Z dan harus sama dengan version di package.json. Jangan menandai rilis sebagai pre-release.
