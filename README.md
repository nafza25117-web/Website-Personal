[index.html](https://github.com/user-attachments/files/23126860/index.html)[halaman2.html](https://github.com/user-attachments/files/23127000/halaman2.html)#Website-Personal
WEB
[Uploa<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cover Page Sederhana - Selamat Datang</title>
    <style>      
        body {
            background-image: url('alatmedis.jpg');     
            background-repeat: no-repeat;
            background-size: cover; 
            background-position: center center;
            background-attachment: fixed; 
            text-align: center;  
            min-height: 100vh;            
            display: flex;                 
            align-items: center;                
            justify-content: center;                 
            height: 100vh;     
            margin: 0;
        }

        .cover-content {
            background-color: rgba(255, 255, 255, 0.95); 
            padding: 50px 60px;
            border-radius: 12px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
            max-width: 600px;
            animation: fadeIn 1.5s ease-in-out;     
        }

        h1 {
            font-size: 3em;
            color: #1d3557; 
            margin-bottom: 0.2em;
            text-align: center;
        }
        h2{
            font-size: 2em;
            color: #1d3557; 
            margin-bottom: 0.2em;
            margin-top: 0;
            text-align: center;
        }
        p.tagline {
            font-size: 1.2em;
            color: #457b9d; 
            margin-top: 0;
            margin-bottom: 30px;
            text-align: center;
        }

        .cta-button {
            display: inline-block;
            padding: 15px 30px;
            background-color: #5d9ce4; 
            color: white;
            text-decoration: none;
            border-radius: 8px;
            font-weight: bold;
            font-size: 1.1em;
            transition: background-color 0.3s ease, transform 0.3s ease;
            
        }

        .cta-button:hover {
            background-color: #24a74b;
            transform: translateY(-3px); 
            text-align: center; 
   
        }
        
        /* Animasi */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
            
        }
    </style>
</head>
<body>

    <div class="cover-content">
        <h1>Welcome To Our Website</h1>
        <h2>Klinik Rawat Inap Sidayu Medical Center</h2>
        
        <p class="tagline">Kami menyediakan layanan medis terbaik dengan sentuhan personal. Dipercayakan oleh ribuan keluarga,
             kami berkomitmen menjaga Anda tetap sehat dan prima.</p>
        
        <a href="halaman2.html" class="cta-button">
            Mulai Sekarang Juga
        </a>
    </div>

</body>
</html>ding index.html…]()
[Upl<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Klinik Rawat Inap Sidayu Medical Center</title>
    <style>
        body {
            background-image: url('bg1.jpeg');    
            background-repeat: no-repeat;
            background-size: cover; 
            background-position: center center;
            background-attachment: fixed; 
        }  

        .header {
            background-color: #080730;
            color: white;
            padding: 20px 0;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            display: flex; 
            flex-direction: column; 
            align-items: center; 
        }

        .header .logo {
            width: 120px; 
            height: auto;
            margin-bottom: 10px; 
        }

        .header h1 {
            margin: 0;
            font-size: 2.5em;
            letter-spacing: 1px;
            margin-bottom: 10px;
        }

        .header p {
            margin: 5px 0 0;
            font-size: 1.2em;
        }
        .nama-class-list li {
    text-align: center;
}
        .container {
            width: 90%;
            max-width: 1100px;
            margin: 30px auto;
            padding: 20px;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.05);
        }
        
        .layanan-list ul { 
        list-style: none; 
        padding-left: 0;
        }
        .bacground-color{
        margin: 0;
        padding: 0;
        box-sizing:border-box;
        }
        
        .layanan-list li {
        margin-bottom: 5px;
        }
        
        li {
        display: flex;
        align-items: center;
        }
        .ikon-centang {
        margin-right: 5px;
        }
        .room-card {
            display: flex;
            justify-content: space-around;
            gap: 20px;
            flex-wrap: wrap; 
            margin: 0 auto; 
            margin-bottom: 10px;
            width: 90%; 
            max-width: 600px; 
        }
        .list-2-kolom {
            display: grid; 
            grid-template-columns: 1fr 1fr; 
            gap: 10px 20px; 
            list-style: none;
            padding: 0;
        }
        .ugd-info {
            background-color: #f10e47; 
            padding: 15px;
            margin-bottom: 25px;
            border-radius: 8px;
            text-align: center;
            font-size: 1em;
            font-weight: bold;
        }
        
        h2 {
            color: #080730;
            border-bottom: 3px solid #080730;
            padding-bottom: 10px;
            margin-top: 30px;
            font-size: 2em;
        }

        .room-grid {
            display: flex;
            justify-content: space-around;
            gap: 20px;
            flex-wrap: wrap; 
        }

        .room-card {
            background-color: #e9f2fa; 
            border: 1px solid #ced4da;
            border-radius: 10px;
            padding: 25px;
            width: 45px;
            min-width: 300px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s ease-in-out;
        }

        .room-card:hover {
            transform: translateY(-5px); 
        }

        .room-card h3 {
            color: #080730;
            font-size: 1.8em;
            margin-top: 0,5px;
        }

        .room-card .price {
    
            font-size: 1.6em;
            font-weight: bold;
            color: #28a745; 
            margin: px 0;
            padding: 5px;
            background-color: white;
            border-radius: 5px;
            display: inline-block;
            
        }

        .room-card ul {
            list-style: none;
            padding-left: 0;
            text-align: left;
        }

        .room-card ul li {
            padding: 5px 0;
            border-bottom: 1px dashed #ced4da;
        }

        .room-card ul li:last-child {
            border-bottom: none;
        }
         body {
            font-family: 'Arial', sans-serif;
            background-color: #f8f9fa; 
            padding: 30px;
        }
        
        .service-card {
            max-width: 350px; 
            margin: 0 auto; 
            background-color: white;
            border-radius: 12px;
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.1); 
            padding: 30px;
            text-align: center;
            transition: transform 0.3s ease-in-out;
            border-top: 8px solid #080730;
        }

        .service-card:hover {
            transform: translateY(-5px); 
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.15);
        }

        .icon-large {
            font-size: 3.5em; 
            color: #080730;
            margin-bottom: 10px;
            display: block;
        }

        .service-card h3 {
            font-size: 1.8em;
            color: #343a40;
            margin-top: 5px;
            margin-bottom: 15px;
        }

        .service-description {
            font-size: 1.05em;
            color: #555;
            line-height: 1.6;
            margin-bottom: 25px;
            text-align: left;
        }

        .facility-list {
            list-style: none;
            padding-left: 0;
            text-align: left;
            margin-top: 10px;
            text-align: left;
        }

        .facility-list li {
            padding: 8px 0;
            border-bottom: 1px dashed #eee;
            color: #333;
            font-size: 1em;
            display: flex;
            align-items: center;
        }

        .check-icon {
            color: #28a745; 
            margin-right: 8px;
            font-weight: bold;
        }
        
        .room-card {
            display: flex;
            justify-content: space-around;
            gap: 20px;
            flex-wrap: wrap; 
            margin: 0 auto; 
            margin-bottom: 10px;
            width: 90%; 
            max-width: 600px; 
        }
        .list-2-kolom {
            display: grid; 
            grid-template-columns: 1fr 1fr; 
            gap: 10px 20px; 
            list-style: none;
            padding: 0;
        }
        .footer {
            text-align: center;
            padding: 20px;
            margin-top: 40px;
            background-color: #080730;
            color: white;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <div class="header">
        <img class="logo" src="LOGO SMC.png" alt="Logo Sidayu Medical Center">
        <h1>KLINIK RAWAT INAP</h1>
        <p>Sidayu Medical Center</p>
    </div>
            <header style="text-align: center; margin-bottom: 30px;">
                <h2>Tentang Kami</h2>
                <p>Klinik Sidayu Medical Center adalah fasilitas pelayanan kesehatan yang menyelenggarakan pelayanan kesehatan perorangan yang tidak hanya menyediakan pelayanan medis dasar atau spesialistik rawat jalan, tetapi juga memiliki
                   fasilitas dan izin untuk memberikan pelayanan rawat inap dalam batasan tertentu. 
                   Klinik ini merupakan suatu fasilitas pelayanan kesehatan yang sangatlah dicari serta bermanfaat bagi masyarakat yang sedang membutuhkan perawatan, 
                   klinik merupakan tempat bagi pasien yang ingin mendapatkan obat – obatan yang sesuai dengan sakit yang dialaminya, 
                   dan dapat konsultasi serta memperoleh nasihat medis. </p>
       </div>
    <div class="container">
        <div class="foto-container"> 
            <img src="smc2.png" width="500px"alt="Foto Ketiga">
        </div>
    </div>
    <hr style="border: 0; border-top: 1px solid #ccc; margin: 30px 0;">
    <div class="room-card">
    <div class="lab-options-card">
    <h2>Jenis Pelayanan Yang Tersedia:</h2>
    <ul class="list-2-kolom">
        <li>✅Layanan medis dasar/rawat jalan</li>
        <li>✅Layanan rawat inap</li>
        <li>✅Tindakan IGD</li>
        <li>✅Cek laboratorium</li>
        <li>✅Pembuatan SKD</li>
        <li>✅Pengurusan Jenazah</li>
        <li>✅Ambulance</li>
        <li>✅Pelayanan kefarmasian</li>
        <li>✅Pelayanan lain-lain</li>
    </ul>
    </div>
    </div>
             <h1 class="jarak-bawah"> 
               <hr style="border: 0; border-top: 1px solid #080730; margin: 30px 0;">
              
        <div class="ugd-info">
            PELAYANAN GAWAT DARURAT (UGD) 24 JAM 🚑
        </div>
       
        <p style="text-align: center; font-size: 0.8 em; color: #080730;">
            Kami berkomitmen untuk memberikan pelayanan rawat inap terbaik dengan fasilitas yang nyaman dan tenaga medis profesional.
        </p>

        <hr style="border: 0; border-top: 1px solid #ccc; margin: 30px 0;">

        <h2>Pilihan Kelas Rawat Inap</h2>

        <div class="room-grid">
            
            <div class="room-card">
                <h3>Kelas 1 (Eksklusif)</h3>
                <p class="price">Rp 150.000 / Hari</p>
                <ul>
                    <h4>FASILITAS :</h4>
                    <li>✅ *Kapasitas: 1 Pasien per Kamar*</li>
                    <li>✅ Kamar mandi dalam</li>
                    <li>✅ Kipas Angin</li>
                    <li>✅ Televisi</li>
                    <li>✅ Loker/Lemari pribadi</li>
                </ul>
                <p style="margin-top: 20px; color: #080730;">*Kenyamanan pribadi maksimal untuk pemulihan optimal.</p>
            </div>

            <div class="room-card">
                <h3>Kelas 2 (Semi-Privat)</h3>
                <p class="price">Rp 100.000 / Hari</p>
                <ul>
                    <h4>FASILITAS :</h4>
                    <li>✅ *Kapasitas: 2 Pasien per Kamar*</li>
                    <li>✅ Tirai pembatas antar pasien</li>
                    <li>✅ Kamar mandi dalam</li>
                    <li>✅ Kipas angin</li>
                    <li>✅ Loker/Lemari pribadi</li>
                </ul>
                <p style="margin-top: 20px; color: #080730;">*Fasilitas lengkap dengan harga yang lebih terjangkau.</p>
            </div>
        </div>
        <hr style="border: 0; border-top: 1px solid #ccc; margin: 30px 0;">
        <div class="service-container"> 
    
    <div class="service-card-lab">
        <div class="lab-header">
            <h2>🧪Laboratorium </h2>
                <div class="room-card">
                    <div class="lab-options-card">
                    <h4>Pilihan Cek Lab :</h4>
                    <ul class="list-2-kolom">
                       <li>✅ Pemeriksaan darah rutin</li>
                       <li>✅ Pemeriksaan gula darah</li>
                       <li>✅ Pemeriksaan kolesterol</li>
                       <li>✅ Pemeriksaan asam urat</li>
                       <li>✅ Pemeriksaan kehamilan</li>
                       <li>✅ Pemeriksaan widal</li>
                       <li>✅ Pemeriksaan urine Lengkap</li>
                       <li>✅ Pemeriksaan narkoba</li>
                       <li>✅ Pemeriksaan antigen</li>
                       <li>✅ Pemeriksaan penunjang lainnya.</li>
                    </ul>
                    </div>
                </div>
        </div>
    </div>
      <hr style="border: 0; border-top: 1px solid #ccc; margin: 30px 0;">
        <h2>Informasi Tambahan</h2>
        <p>Untuk informasi ketersediaan kamar dan reservasi, silakan hubungi kontak kami di bawah ini.</p>
    
            <p>
                <span style="margin-right: 8px;">📞</span>
                Contact Person : +62 823-2267-2226
            </p>

            <p>
                <span style="margin-right: 8px;">📧</span>
                Gmail : kliniksidayumedicalcenter.gmail.com
            </p>
            <a href="https://www.instagram.com/kliniksidayumedicalcenter/#">Instagram klinik sidayu medical center</a>
            <hr style="border: 0; border-top: 1px solid #ccc; margin: 30px 0;">
    <h2>Lokasi Klinik Sidayu Medical Center</h2>
    <img src="lokasi.png" alt="Foto keempat">
        <div class="kolom-motivasi">
            <h2>
        </div>

        <div class="wadah-teks">       
            
            <h1 style="font-size: 36px; color: #080730;">"Kesembuhan dan keselamatan anda adalah prioritas kami"</h1>
        </div>
        <div class="wadah-foto">
        <header style="text-align: center; margin-bottom: 30px;">   
    <img src="e.jpeg" alt="Foto Pertama" width="250px">
    <img src="i.jpeg" alt="Foto Kedua" width="250px">
    <img src="s.jpeg" alt="Foto Ketiga" width="250px">
</div>
    <div class="footer">
        &copy; 2025 Sidayu Medical Center. Semua Hak Dilindungi.
    </div>
</body>
</html>
oading halaman2.html…]()
<img width="444" height="303" alt="lokasi" src="https://github.com/user-attachments/assets/e8ed21a2-5854-4ac6-b118-1788225a7651" />
<img width="473" height="528" alt="LOGO SMC" src="https://github.com/user-attachments/assets/a60f2857-1188-4540-b04c-88b7fbbd4265" />
<img width="900" height="691" alt="smc2" src="https://github.com/user-attachments/assets/a95877d1-e467-4f54-bda1-5d4f65ca6f6b" />
![s](https://github.com/user-attachments/assets/3413c44a-1ca8-4e15-9f9f-594c9d4acf34)
![alatmedis](https://github.com/user-attachments/assets/b77863e0-33b2-4bc1-a8f2-9f8c06468e00)
![e](https://github.com/user-attachments/assets/c2569747-a9f0-4e42-9cfa-c47af8ce367c)
![bg1](https://github.com/user-attachments/assets/ce5ec6cb-7674-4372-a0d3-57ae13934ccf)
![i](https://github.com/user-attachments/assets/057f66c2-e651-41c0-ba45-0b950ed09490)





