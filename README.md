# index
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profil atus</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <nav class="navbar">
            <a href="#beranda">Beranda</a>
            <a href="#tentang">Tentang saya</a>
            <a href="#portofolio">Portofolio</a>
            <a href="#opini">Opini</a>

            <div class="dropdown">
                <button class="dropbtn">lainnya</button>
                <div class="dropdown-content">
                    <a href="https://www.instagram.com/mratustiianiiiiii6_/" target="_blank">Instagram</a>
                    <a href="https://www.facebook.com/share/1FSumWP1UZ/" target="_blank">Facebook</a>
                    <a href="https://www.tiktok.com/@maratusetiani?_t=ZS-8vmAEqFfg2y&_r=1" target="_blank">Tiktok</a>

                </div>
            </div>

        </nav>
    </header>

    <section class="intro" id="intro">
        <img src="aku.jpg" alt="Foto">
    <div class="intro-text">
    <h2>Halo, saya Maratus Setiani</h2>
    <p>Saya seorang mahasiswa di Universitas Nahdlatul Ulama Sunan Giri Bojonegoro</p>

    </section>

    <section class="tentang " id="tentang">
        <div>
            <h2>Tentang Saya</h2>
            <p>Saya adalah seorang mahasiswa di UNUGIRI , prodi Teknik Informatika. Sekarang saya menduduki semester 2.</p>
            <p>Saya adalah Gen-z dengan kelahiran pada tanggal 10 mei 2006. Saya anak kedua dari dua bersaudara.</p>
            <p> Saya adalah alumi dari pondok pesantren ATTANWIR bojonegoro.</p>
            <p>Dan kini saya melanjutkan pendidikan saya dengan kuliah di UNUGIRI di prodi Teknik Informatika.</p>
          </div>
          <img src="atus.jpg" alt="foto saya">
    </section>

    <section class="portofolio" id="portofolio">
        <h2>Portofolio</h2>
        <table>
          <thead>
            <tr>
              <th>No</th>
              <th>Nama Kegiatan</th>
              <th>Waktu Kegiatan</th>
              <th>Bukti Kegiatan</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>1</td>
              <td>PKKMB UNUGIRI</td>
              <td>2024</td>
              <td><a href="https://drive.google.com/open?id=1nmNSllOAfYFdZNahdbkEa1glHNhcc8RU&usp=drive_copy" target="_blank">Lihat Bukti</a></td>
            </tr>
            <tr>
              <td>2</td>
              <td>Pengurus Konsulat Attanwir</td>
              <td>2023/2024</td>
              <td><a href="https://drive.google.com/open?id=1K2CJV9_l4emTU-xR8nZ8ioP1QfyBVC_a&usp=drive_copy" target="_blank">Lihat Bukti</a></td>
            </tr>
            <tr>
              <td>3</td>
              <td>Workshop TIK</td>
              <td>2024</td>
              <td><a href="https://drive.google.com/open?id=11T8LoLpxYcgma3zS6OjBofeCl2274Ox0&usp=drive_copy" target="_blank">Lihat Bukti</a></td>
            </tr>
            <tr>
              <td>4</td>
              <td>KMD</td>
              <td>2024</td>
              <td><a href="https://drive.google.com/open?id=1X_fCcsWYEw14vIdMOV8JvZGx0Q6lpMmh&usp=drive_copy" target="_blank">Lihat Bukti</a></td>
            </tr>
          </tbody>
        </table>
      </section>

      <section>
        <h2 style="text-align: center;">Opini</h2>
      </section>
    
      <section class="opini" id="opini">
       
        <div><img src="kmd.jpg" alt="Opini 1"><h4>KMD Attanwir</h4></div>
        <div><img src="it camp.jpg" alt="Opini 2"><h4>IT camp</h4></div>
        <div><img src="sosialisasi.jpg" alt="Opini 3"><h4>Sosialisasi</h4></div>
        <div><img src="tugas1.jpg" alt="Opini 4"><h4>Tugas Pemograman</h4></div>
        <div><img src="tugas.jpg" alt="Opini 5"><h4>Tugas struktur data</h4></div>
        <div><img src="tugas2.jpg" alt="Opini 6"><h4>Tugas Bahasa inggris </h4></div>
      </section> 

      <section class="kontak">
        <h2>hubungi saya</h2>
        <div class="kontak1">
    
        <form>
          <input type="email" placeholder="Email">
          <input type="text" placeholder="Nama">
          <input type="text" placeholder="Subject">
          <textarea placeholder="Isi Pesan"></textarea>
          <button type="submit">Kirim</button>
        </form>
     
        <div class="maps">
          <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d31656.009256997408!2d112.04127026897488!3d-7.353764529913663!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e78256fc8b465f9%3A0x1ce5ed3ecfc34078!2sTondomulo%2C%20Kec.%20Kedungadem%2C%20Kabupaten%20Bojonegoro%2C%20Jawa%20Timur!5e0!3m2!1sid!2sid!4v1745497607406!5m2!1sid!2sid"
           width="350" 
           height="200" 
           style="border:0;" 
           allowfullscreen="" loading="lazy" 
           referrerpolicy="no-referrer-when-downgrade">
          </iframe>
        </div>
      </div>
       </section> 
    
       <footer>
        <p>Copyright by Maratus Setiani</p>
      </footer>
</body>
</html>

#style css
body {
    font-family: Arial, sans-serif;
    margin: 20px;
    padding: 20px;
    background-color: #8ca6b3;
  }
  
  header {
    background-color: #2e379b;
    display: flex;
    justify-content: space-between;
    align-items:center;
    position: fixed;
    width: 100%;
    top: auto;
    top: 0;
    left: 0;
    z-index: 1000;
  }
  #intro, #tentang, #portofolio, #opini {
    scroll-margin-top: 80px;
  }
  
  nav a {
    margin: 0 20px;
    text-decoration: none;
    color:black ;

  }
  .navbar a, .dropbtn {
    color: white;
    padding: 12px 16px;
    text-decoration: none;
    text-align: center;
    background: none;
    border: none;
    cursor: pointer;
  }

  .navbar a:hover, .dropdown:hover .dropbtn {
    background-color: #575757;
  }
  .dropdown {
    position: relative;
    display: inline-block;
  }

  .dropdown-content {
    display: none;
    position: absolute;
    background-color: #f9f9f9;
    min-width: 160px;
    box-shadow: 0px 8px 16px rgba(0,0,0,0.2);
    z-index: 1;
  }
  .dropdown-content a {
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
  }

  .dropdown-content a:hover {
    background-color: #ddd;
  }

  .dropdown:hover .dropdown-content {
    display: block;
  }
  .intro{
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 20px;
    flex: 1;
  }
  .intro text{
    flex: 0 0 60%;
      text-align: left;
      padding-right: 20px;
  }
  .intro img{
    width: 150px;         /* bisa disesuaikan ukurannya */
height: 150px;        /* pastikan tinggi dan lebar sama */
object-fit: cover;    /* menjaga agar gambar tetap rapi */
border-radius: 50%;   /* ini yang bikin jadi lingkaran */
display: block;
box-shadow: 0 10px 20px rgba(0, 0, 0, 3);/*bayangan halus*/
border: 3px solid #ffffff; /*bingkai putih*/
  }
  .tentang, .portofolio, .opini, .kontak {
    padding: 10px;
    text-align: center;
  }

   .tentang img {
    width: 150px;
    height: 150px;
    object-fit: cover;
    border-radius: 50%;
    box-shadow: 0 10px 20px rgba(0, 0, 0, 3);/*bayangan halus*/
    border: 3px solid #ffffff; /*bingkai putih*/
  }
  .tentang {
    display: flex;
    justify-content: space-between;
  }

  h2 {
    text-align: center;
    font-size: 2.5em;
    color: #1a1550;
    font-family: 'Montserrat', sans-serif;
    position: relative;
    padding-bottom: 10px;
    text-shadow: 1px 1px 2px rgba(0,0,0,0.15);
    animation: bounceIn 0.7s ease;
  }
  
  h2::after {
    content: "";
    position: absolute;
    width: 80px;
    height: 4px;
    background: linear-gradient(to right, #43cea2, #185a9d);
    left: 50%;
    bottom: 0;
    transform: translateX(-50%);
    border-radius: 5px;
  }
  
  table {
    width: 100%;
    border-collapse: separate;
    border-spacing: 0;
    border-radius: 10px;
    overflow: hidden;
  }

  thead tr {
    background: linear-gradient(to right, #43cea2, #185a9d);
    color: white;
  }

  th, td {
    padding: 14px 18px;
    text-align: left;
  }

  tbody tr {
    background-color: #f9f9f9;
    transition: background 0.3s;
  }

  tbody tr:nth-child(even) {
    background-color: #f1f1f1;
  }

  tbody tr:hover {
    background-color: #d0f0e0;
  }

  a {
    color: #1e88e5;
    text-decoration: none;
    font-weight: bold;
  }

  a:hover {
    text-decoration: underline;
  }

  @keyframes fadeIn {
    from { opacity: 0; transform: translateY(20px); }
    to { opacity: 1; transform: translateY(0); }
  }

  @media (max-width: 768px) {
    table, thead, tbody, th, td, tr {
      display: block;
    }

    thead tr {
      display: none;
    }

    td {
      position: relative;
      padding-left: 50%;
      border-bottom: 1px solid #ddd;
    }

    td::before {
      position: absolute;
      left: 15px;
      width: 45%;
      white-space: nowrap;
      font-weight: bold;
      color: #555;
    }

    td:nth-of-type(1)::before { content: "No"; }
    td:nth-of-type(2)::before { content: "Nama Kegiatan"; }
    td:nth-of-type(3)::before { content: "Waktu Kegiatan"; }
    td:nth-of-type(4)::before { content: "Bukti Kegiatan"; }
  }
  .opini {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
    padding: 20px;
  }
  
  .opini div {
    width: calc(33.333% - 20px);
    background: #ffffff;
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    text-align: center;
  }
  
  .opini div:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 24px rgba(0, 0, 0, 0.2);
  }
  
  .opini img {
    width: 100%;
    height: 180px;
    object-fit: cover;
    transition: transform 0.3s ease;
  }
  
  .opini div:hover img {
    transform: scale(1.05);
  }
  
  .opini h4 {
    margin: 0;
    padding: 12px;
    font-size: 1.1em;
    background-color: #f5f5f5;
    color: #2c3e50;
  }
  
  /* Responsive untuk tablet dan HP */
  @media (max-width: 768px) {
    .opini div {
      width: calc(50% - 20px);
    }
  }
  
  @media (max-width: 480px) {
    .opini div {
      width: 100%;
    }
  }
  .kontak {
    padding: 40px 20px;
    background-color: #f9f9f9;
  }
  
  .kontak1 {
    display: flex;
    flex-wrap: wrap;
    gap: 30px;
    justify-content: center;
    margin-top: 30px;
  }
  
  /* FORM STYLE */
  form {
    background-color: #a4bee4;
    padding: 20px 25px;
    border-radius: 12px;
    box-shadow: 0 6px 20px rgba(0, 0, 0, 0.1);
    width: 350px;
  }
  
  form input, form textarea {
    display: block;
    margin-bottom: 15px;
    width: 100%;
    padding: 10px;
    font-size: 1em;
    border: 1px solid #ccc;
    border-radius: 8px;
    transition: border-color 0.3s, box-shadow 0.3s;
  }
  
  form input:focus,form textarea:focus {
    border-color: #4a90e2;
    box-shadow: 0 0 5px rgba(74, 144, 226, 0.4);
    outline: none;
  }
  
  form button {
    background-color: #4a90e2;
    color: #fff;
    border: none;
    padding: 10px 16px;
    font-size: 1em;
    border-radius: 8px;
    cursor: pointer;
    transition: background-color 0.3s;
  }
  
  form button:hover {
    background-color: #357ab7;
  }
  
  /* MAPS STYLE */
  .maps {
    width: 350px;
    height: 200px;
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 6px 20px rgba(0, 0, 0, 0.1);
  }
  footer {
    text-align: center;
    padding: 10px;
    background-color: #2e379b;
    color: white;
    margin-top: 50px; /* beri jarak dari bagian atas */
  }
  
