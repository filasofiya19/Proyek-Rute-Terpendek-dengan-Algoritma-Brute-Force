# Proyek-Rute-Terpendek-dengan-Algoritma-Brute-Force

Disusun oleh:
1. Fila Sofiyati
2. Merlinda Lavenia
3. Silvi Nuraida

**Merupakan Rute Terpendek Tempat Wisata Bersejarah di Semarang (Kota dan Kabupaten Semarang)**<br>
Dengan list tempat sebagai berikut:

0.   Tugu Muda
1.	Lawang Sewu
2.	Museum Kota Lama Semarang
3.	Museum Rekor Dunia Indonesia
4.	Sam Poo Kong
5.	Candi Gedong Songo
6.	Museum Perjuangan Mandala Bakti
7.	Benteng Pendem Ambarawa
8.	Museum Kereta Api Ambarawa
9.	Pagoda Avalokitesvara

Untuk titik awalnya kami mencoba satu per satu sedemikian hingga ditemukan rute terpendeknya.

Untuk detail jaraknya yaitu:


    [0, 0.23, 3.3, 11.7, 2.8, 38.8, 0.064, 37.9, 38.6, 13.3],
    [0.15, 0, 3.2, 11.5, 2.5, 38.6, 0.17, 37.6, 38.4, 13.1],
    [3.3, 3, 0, 13, 5.7, 40, 3.3, 39.1, 39.8, 14.6],
    [11.1, 11.3, 12.4, 0, 11.2, 27.6, 11.1, 26.6, 27.3, 2.1],
    [2.3, 2.6, 5.6, 11.4, 0, 38.5, 2.3, 37.5, 38.3, 13],
    [38.9, 39.1, 40.1, 27.9, 38.9, 0, 38.8, 13.6, 12.8, 26.1],
    [0.027, 0.25, 3.3, 11.8, 2.5, 38.9, 0, 37.9, 38.6, 13.3],
    [36.8, 37, 38.1, 25.8, 36.8, 13.5, 36.8, 0, 1, 24],
    [36.8, 37, 38, 25.8, 36.8, 12.8, 36.8, 1.5, 0, 24],
    [13.5, 13.7, 14.8, 2.5, 13.5, 25.5, 13.5, 24.5, 24.4, 0],


**Kesimpulanya**<br>
Detail jarak (Km) titik satu ke titik lainnya:<br>
Dari 2 Ke 1, Jarak: 3 Km<br>
Dari 1 Ke 0, Jarak: 0.15 Km<br>
Dari 0 Ke 6, Jarak: 0.064 Km<br>
Dari 6 Ke 4, Jarak: 2.5 Km<br>
Dari 4 Ke 3, Jarak: 11.4 Km<br>
Dari 3 Ke 9, Jarak: 2.1 Km<br>
Dari 9 Ke 7, Jarak: 24.5 Km<br>
Dari 7 Ke 8, Jarak: 1 Km
Dari 8 Ke 5, Jarak: 12.8 Km<br>

Rute Terpendek:
2 -> 1 -> 0 -> 6 -> 4 -> 3 -> 9 -> 7 -> 8 -> 5
Total Jarak: 57.513999999999996 Km

**Nilai optimal perolehan jarak , terpendeknya dan detail rutenya yaitu 57,51 Km, dengan detail rute destinasi wisata yaitu Museum Kota Lama Semarang - Lawang Sewu - Tugu Muda - Museum Perjuangan Mandala Bhakti - Sam Poo Kong - Museum Rekor Dunia Indonesia - Pagoda Avalokitesvara - Benteng Pendem Ambarawa - Museum Kereta Api Ambarawa - Candi Gedong Songo.**
