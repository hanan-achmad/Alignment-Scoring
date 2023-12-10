# Alignment Scoring

<h3>Sequence alignment</h3>
<p>Jika dua sequence memiliki bagian-bagian yang mirip lebih dari yang seharusnya, maka kemungkinan besar sequence tersebut memiliki hubungan (homolog). Saat melakukan sequence alignment, kita tidak hanya memperhatikan karakter yang sama persis atau match, tetapi juga gap atau celah pada sequence dan mismatch nya, yang dapat mewakili mutasi yang terjadi diantara kedua sequence. Dalam metode sequence alignment, tujuannya adalah untuk menemukan alignment terbaik dengan mencoba memaksimalkan jumlah match dan meminimalkan jumlah gap dan mismatch. Untuk mengukur seberapa baik penyelarasan itu, kita memberi skor dengan menambahkan nilai untuk setiap karakter yang cocok dan mengurangkan nilai untuk spasi dan ketidakcocokan. Semakin tinggi skornya, semakin baik alignment nya.</p>

<h4>Skoring Alignment</h4>
<p>Disini kita akan melakukan skoring alignment secara sederhana terhadap protein sequence dari mouse dan rat untuk melihat hubungan kekerabatan antar kedua spesies ini.</p>
<p>Dimana untuk kasus ini kita akan menghitung skor kemiripan dengan rumus: Skor Kemiripan = Jumlah Karakter Sama, match = 1 dan untuk saat ini kita akan menggunakan skor untuk gap dan mismatch adalah 0.</p>

<p>Contohnya:<p>

<li>S1 = ACATGGAAT</li>
<li>S2 = ACAGGAAAT</li>

<p>Skor kemiripan dari sequence tersebut adalah: 7</p>
