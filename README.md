# Praktikum Pemrograman Spasial Web - Acara 6

Peta interaktif WebGIS Kabupaten Flores Timur berbasis **Leaflet JS**.

## Deskripsi
Aplikasi WebGIS ini menampilkan peta interaktif wilayah Kabupaten Flores Timur dengan fitur visualisasi data geospasial:
- **Jumlah Penduduk per Kecamatan**: Visualisasi tematik (choropleth) berdasarkan kelas kepadatan/jumlah penduduk.
- **Jaringan Jalan**: Menampilkan layer garis jaringan jalan di Flores Timur.
- **Toponimi**: Titik-titik toponimi (seperti gunung dan tempat menarik) disertai informasi popup dan dokumentasi foto.
- **Layer Control & Legenda**: Kontrol pilihan basemap (OpenStreetMap, Esri World Imagery, CartoDB Positron) serta legenda klasifikasi jumlah penduduk.

## Struktur Direktori
```text
.
├── GeoJSON/          # Data geospasial format GeoJSON (jalan, jumlah penduduk, toponimi)
├── florestimur/      # Data shapefile sumber Kabupaten Flores Timur
├── images/           # Aset gambar penunjang dan ikon marker
├── index.html        # Halaman utama aplikasi WebGIS Leaflet
└── README.md
```

## Teknologi
- [Leaflet JS](https://leafletjs.com/) v1.9.4
- [Bootstrap](https://getbootstrap.com/) v5.3.8 & Bootstrap Icons
- HTML5 / CSS3 / JavaScript