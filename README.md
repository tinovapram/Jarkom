# Jarkom

Project akhir semester Jarkom,
cara kerja:\n
1. Arduino ambil data sensor suhu dan kelembapan
2. Data dikirm via serial
3. Arduino menunggu data dari thingspeak
3. Python baca data, dipastikan apakah data sensor atau feedback
4. Data diparsing antara suhu dan kelebaban
5. upload ke thingspeak
6. ambil data terbaru dari thingspeak
7. Ambil variable suhu
8. Kirim ke arduino
9. Arduino mengatur warna LED Berdasarkan data terakhir
10. Arduino kirim feedback ke Python
