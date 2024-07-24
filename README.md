# Deskripsi
APIs Email Gateway Yang Bisa Dipasang Pada Web Hosting untuk mempermudah development dan melakukan proses melalui rest APIs
# Cara Penggunaan
Asumsikan bahwa anda telah memasang script email gateway ini pada web hosting dengan url : https://emailgatewayanda.com <br>
Sebagai catatan script ini hanya berfungsi di web hosting dan anda sudah membuat sebuah akun web mail.<br>
Perhatikan parameter berikut:<br>
<ul>
  <li><b>URL :</b> https://emailgatewayanda.com</li>
  <li><b>Metode :</b> POST</li>
  <li>
    <b>Body :</b>
    <pre>
      <code>
        {
        	"subjek": "Test Kirim Email",
        	"email_asal": "admin@domain.com",
        	"password_email_asal": "Passwordanda123*#",
        	"url_provider": "smtp.hostinger.com",
        	"nama_pengirim": "Admin Website Kami",
        	"email_tujuan": "emailtujuan@gmail.com",
        	"nama_tujuan": "Bapak Syamsul Maarif",
        	"pesan": "Hallo, ini percobaan mengirim email",
        	"port": "465"
        }
      </code>
    </pre>
  </li>
</ul>
<p>
  <b>Keterangan :</b><br>
  Untuk parameter <code>url_provider</code> akan berbeda pada masing-masing provider hosting yang anda gunakan. Silahkan hubungi CS masing-masing provider untuk mengetahui parameter tersebut.
</p>
