🐾 Penguu - Virtual Pet FSA

Penguu adalah aplikasi Virtual Pet berbasis web yang dibangun menggunakan prinsip Finite State Automata (FSA). 

    Sistem Status Real-time: Pantau Nutrisi, Energi, Kebahagiaan, dan Kesehatan melalui progress bar yang dinamis.

    Mekanisme FSA (Finite State Automata): Penguu berubah status (Lapar, Lelah, Senang, Hidup, sakit, atau Mati) secara otomatis berdasarkan ambang batas statistik.

    Interaksi Interaktif: Tersedia aksi Elus (👋), Makan (🍲), Tidur (💤), dan Main (🎡).

    Logika Otomatis (5 Detik): Permainan secara cerdas menurunkan status Penguu setiap 5 detik untuk mensimulasikan kebutuhan makhluk hidup.

🛠️ Teknologi yang Digunakan

    HTML & CSS: Struktur UI dan desain responsif menggunakan CSS Variables.

    JavaScript: Pengolah logika state, manipulasi DOM, dan manajemen waktu.

🎮 Mekanisme Permainan
1. Siklus Hidup (Looping)

Setiap 5000ms (5 detik), sistem akan menjalankan logika berikut:

    Penurunan: Nutrisi dan Energi berkurang secara otomatis.

    Efek Domino: Jika Nutrisi atau Energi terlalu rendah, maka tingkat Kebahagiaan dan Kesehatan juga akan ikut merosot drastis.

    Pembaruan Status: Gambar dan teks Penguu akan berubah sesuai kondisi terbaru.

2. Tabel State (FSM)
State	Kondisi Pemicu	Tampilan Visual
Mati	Kesehatan ≤ 0%	xx.png
Lapar	Nutrisi ≤ 30%	lapar.png
Lelah	Energi ≤ 30%	lelah.png
Senang	Kebahagiaan ≥ 70%	senang.png
Hidup	Kondisi Normal	hidup.png

Dibuat dengan ❤️ (dari Alya dan Aurel) untuk simulasi Finite State Automata

Link akses: https://aurelliazhr.github.io/Virtual-Pet-Penguu/
