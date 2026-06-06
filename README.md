Deskripsi Aplikasi
Weather Finder adalah aplikasi mobile berbasis React Native dan Expo yang digunakan untuk mencari informasi cuaca berdasarkan nama kota. Aplikasi menggunakan Open-Meteo API (tanpa API key) untuk mengambil data lokasi dan cuaca secara real-time.
Fitur Level 1
•	Controlled TextInput (value dan onChangeText)
•	Debounce 500ms menggunakan setTimeout dan clearTimeout
•	useEffect dengan dependency array
•	Fetch data Geocoding API dan Forecast API Open-Meteo
•	AbortController untuk membatalkan request lama
•	Empty State
•	Loading State
•	Error State
•	Success State
•	Mapping Weather Code (WMO)
Fitur Level 2 yang Dipilih
1. Arah dan Kecepatan Angin
•	Menampilkan kecepatan angin (windspeed)
•	Mengubah wind direction menjadi arah mata angin (U, TL, T, TG, S, BD, B, BL)
2. Indikator Siang/Malam
•	Menggunakan field is_day dari Open-Meteo
•	Menampilkan indikator ☀️ Siang atau 🌙 Malam
3. Riwayat Pencarian
•	Menyimpan 5 kota terakhir yang dicari
•	Kota dapat dipilih kembali dengan sekali klik

Cara Menjalankan Aplikasi
1.	Clone repository
2.	Install dependency
npm install
3.	Jalankan aplikasi
npx expo start --tunnel
4.	Scan QR Code menggunakan aplikasi Expo Go
Tech Stack
•	React Native
•	Expo SDK 54
•	JavaScript
•	Open-Meteo API


<img width="739" height="1600" alt="empty-state jpg" src="https://github.com/user-attachments/assets/707af071-829b-4d2a-b218-bbedbd40ff1f" />
<img width="739" height="1600" alt="loading-state jpg" src="https://github.com/user-attachments/assets/98cf8a82-d62c-4ead-adda-47ebd89f3406" />
<img width="739" height="1600" alt="success-state jpg" src="https://github.com/user-attachments/assets/02be50a8-fa31-4840-97ec-bafa0f7a01ea" />
<img width="739" height="1600" alt="error-state jpg" src="https://github.com/user-attachments/assets/7456c9fd-f283-4895-a917-eb70b5fcd2c7" />
