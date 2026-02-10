# undangan-aqiqah
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Undangan Aqiqah Anak - [Nama Anak]</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(to bottom, #e8f5e8, #ffffff);
            color: #333;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        .header {
            background: #4caf50;
            color: white;
            padding: 40px 20px;
            border-radius: 10px;
            margin-bottom: 20px;
        }
        .header h1 {
            font-size: 2.5em;
            margin: 0;
        }
        .header p {
            font-size: 1.2em;
        }
        .details {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            margin-bottom: 20px;
        }
        .details h2 {
            color: #4caf50;
        }
        .rsvp {
            background: #f9f9f9;
            padding: 20px;
            border-radius: 10px;
            margin-bottom: 20px;
        }
        .rsvp form {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }
        .rsvp input, .rsvp button {
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .rsvp button {
            background: #4caf50;
            color: white;
            cursor: pointer;
        }
        .footer {
            margin-top: 20px;
            font-size: 0.9em;
            color: #666;
        }
        .share {
            margin-top: 20px;
        }
        .share a {
            margin: 0 10px;
            text-decoration: none;
            color: #4caf50;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Undangan Aqiqah</h1>
            <p>Anak Kami: [Nama Anak] - [Tanggal Lahir]</p>
            <!-- Ganti [Nama Anak] dan [Tanggal Lahir] dengan data asli -->
        </div>
        
        <div class="details">
            <h2>Detail Acara</h2>
            <p><strong>Tanggal:</strong> [Tanggal Acara, e.g., Sabtu, 15 Oktober 2023]</p>
            <p><strong>Waktu:</strong> [Waktu, e.g., 10:00 - 12:00 WIB]</p>
            <p><strong>Tempat:</strong> [Alamat Lengkap, e.g., Masjid Al-Ikhlas, Jakarta]</p>
            <p><strong>Doa dan Acara:</strong> Dengan penuh syukur, kami mengundang Anda untuk menghadiri acara aqiqah anak kami. Mari bersama mendoakan kebaikan dan keselamatan untuk [Nama Anak].</p>
            <!-- Edit detail sesuai kebutuhan -->
        </div>
        
        <div class="rsvp">
            <h2>Konfirmasi Kehadiran (RSVP)</h2>
            <form action="#" method="post"> <!-- Ganti # dengan URL form handler jika perlu -->
                <input type="text" name="nama" placeholder="Nama Anda" required>
                <input type="email" name="email" placeholder="Email Anda" required>
                <select name="kehadiran">
                    <option value="hadir">Akan Hadir</option>
                    <option value="tidak">Tidak Bisa Hadir</option>
                </select>
                <button type="submit">Kirim</button>
            </form>
            <!-- Catatan: Form ini sederhana dan tidak menyimpan data. Untuk penyimpanan nyata, gunakan layanan seperti Google Forms atau Netlify Forms. -->
        </div>
        
        <div class="share">
            <p>Bagikan Undangan:</p>
            <a href="https://wa.me/?text=Undangan Aqiqah: [URL Website Anda]" target="_blank">WhatsApp</a>
            <a href="https://www.facebook.com/sharer/sharer.php?u=[URL Website Anda]" target="_blank">Facebook</a>
            <a href="https://twitter.com/intent/tweet?text=Undangan Aqiqah: [URL Website Anda]" target="_blank">Twitter</a>
            <!-- Ganti [URL Website Anda] dengan link hosting nanti -->
        </div>
        
        <div class="footer">
            <p>Dengan hormat,<br>[Nama Orang Tua]<br>[Kontak, e.g., 08123456789]</p>
        </div>
    </div>
    
    <script>
        // Script sederhana untuk alert setelah submit form
        document.querySelector('form').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Terima kasih atas konfirmasinya!');
            // Tambahkan logika lebih lanjut jika perlu, seperti kirim ke email.
        });
    </script>
</body>
</html>
