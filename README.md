# the-effect-of-weather-on-travel-frequency

Kamu bekerja sebagai seorang analyst untuk Zuber, sebuah perusahaan berbagi tumpangan (ride-sharing) baru yang diluncurkan di Chicago. Tugasmu adalah untuk menemukan pola pada informasi yang tersedia. Kamu ingin memahami preferensi penumpang dan dampak faktor eksternal terhadap perjalanan.

Dengan menggunakan database, kamu akan menganalisis data dari kompetitor dan menguji hipotesis terkait pengaruh cuaca terhadap frekuensi perjalanan. 

# Deskripsi Data
Database yang memuat informasi perjalanan taksi di Chicago:

Tabel neighborhoods: data terkait wilayah di kota Chicago <br>

name: nama wilayah <br>
neighborhood_id: kode wilayah <br>
Tabel cabs: data terkait taksi <br>

cab_id: kode kendaraan<br>
vehicle_id: ID teknis kendaraan<br>
company_name: nama perusahaan yang memiliki kendaraan<br>
Tabel trips: data terkait perjalanan<br>

trip_id: kode perjalanan<br>
cab_id: kode kendaraan yang beroperasi<br>
start_ts: tanggal dan waktu perjalanan dimulai (waktu dibulatkan dalam satuan jam)<br>
end_ts: tanggal dan waktu perjalanan berakhir (waktu dibulatkan dalam satuan jam)<br>
duration_seconds: durasi perjalanan dalam satuan detik<br>
distance_miles: jarak perjalanan dalam satuan mil<br>
pickup_location_id: kode wilayah penjemputan<br>
dropoff_location_id: kode wilayah pengantaran<br>
Tabel weather_records: data terkait cuaca<br>

record_id: kode pencatatan cuaca<br>
ts: tanggal dan waktu saat pencatatan cuaca dilakukan (waktu dibulatkan dalam satuan jam)<br>
temperature: suhu saat pencatatan cuaca dilakukan<br>
description: deskripsi singkat tentang kondisi cuaca, seperti "light rain" (hujan ringan) atau "scattered clouds" (berawan).<br>

# Skema tabel
![image](https://github.com/sultanazhari/the-effect-of-weather-on-travel-frequency/assets/89324682/4f281645-7785-436a-895d-79f078b2c41a)
