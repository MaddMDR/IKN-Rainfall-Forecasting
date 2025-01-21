# IKN Rainfall Forecasting

Meramalkan curah hujan di Ibu Kota Nusantara (IKN) adalah salah satu permasalahan dari Lomba **Data Quest Airnology 2.0**. 

Data memiliki dimensi **20** dengan variabel bebas sebanyak **19**, dan 1 variabel target. Berikut adalah deskripsi masing-masing variabel:

---

## **Variabel Bebas (Independent Variables)**

1. **datetime**  
   Waktu ketika data dihitung (dalam format timestamp UNIX).
2. **datetime_iso**  
   Waktu dalam format ISO 8601, termasuk zona waktu.
3. **time_zone**  
   Zona waktu dalam detik terhadap UTC.
4. **temp**  
   Suhu saat ini dalam Celcius.
5. **visibility**  
   Visibilitas rata-rata dalam meter.
6. **d_point**  
   Titik embun saat ini dalam Celcius.
7. **feels**  
   Suhu yang dirasakan saat ini dalam Celcius.
8. **min_temp**  
   Suhu minimum dalam rentang waktu tertentu dalam Celcius.
9. **max_temp**  
   Suhu maksimum dalam rentang waktu tertentu dalam Celcius.
10. **pressure**  
    Tekanan atmosfer dalam hPa.
11. **sea_level**  
    Tekanan atmosfer pada permukaan laut dalam hPa.
12. **grnd_level**  
    Tekanan atmosfer pada permukaan tanah dalam hPa.
13. **hum**  
    Persentase kelembaban udara saat ini.
14. **wind_spd**  
    Kecepatan angin saat ini dalam m/s.
15. **wind_deg**  
    Arah angin dalam derajat.
16. **rain_3h**  
    Curah hujan dalam 3 jam terakhir dalam mm.
17. **snow_1h**  
    Curah salju dalam 1 jam terakhir dalam mm.
18. **snow_3h**  
    Curah salju dalam 3 jam terakhir dalam mm.
19. **clouds**  
    Persentase penutupan awan saat ini.

---

## **Variabel Target (Dependent Variable)**

- **rain_1h**  
  Curah hujan dalam 1 jam terakhir dalam mm. (variabel target yang akan diramalkan)

---

## **Deskripsi Tambahan**

- **Tujuan:** Meramalkan nilai *rain_1h* berdasarkan data yang diberikan.  
- **Tautan Kaggle:** [IKN Rainfall Forecasting - Data Quest Airnology 2.0](https://www.kaggle.com/competitions/tahap-penyisihan-oq-dataquestua/overview)

---

**Catatan:** Data ini merupakan bagian dari kompetisi tahap penyisihan **Data Quest Airnology 2.0**. Pastikan untuk memahami setiap variabel sebelum membangun model prediksi.
