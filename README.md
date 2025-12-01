<!DOCTYPE html>
<html>

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Halaman Web Pantauan Perubahan Suhu Harian</title>

  <!-- CSS LANGSUNG DALAM HALAMAN -->
  <style>
    body {
      font-family: Arial, Helvetica, sans-serif;
      margin: 0;
      padding: 0;
      background: #eef3f7;
    }

    h2 {
      text-align: center;
      margin-top: 20px;
      color: #004e89;
    }

    hr {
      width: 90%;
      margin: auto;
    }

    p {
      text-align: center;
      color: #444;
      margin-top: 5px;
    }

    iframe {
      display: block;
      margin: 15px auto;
      width: 90%;
      max-width: 900px;
      height: 400px;
      border-radius: 10px;
      border: 2px solid #004e89;
    }

    table {
      width: 90%;
      margin: 20px auto;
      border-collapse: collapse;
      background: white;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }

    th, td {
      padding: 12px;
      text-align: center;
      border: 1px solid #ccc;
    }

    th {
      background: #004e89;
      color: white;
    }

    tr:nth-child(even) {
      background: #e8f2ff;
    }

    tr:hover {
      background: #d5e9ff;
      transition: 0.2s;
    }

    footer {
      text-align: center;
      margin: 20px 0;
      font-size: 14px;
      color: #333;
    }
  </style>

</head>

<body>

  <h2>Kondisi Cuaca Daerah Denpasar</h2>
  <hr>
  <p><b>Lokasi:</b> Desa Serangan, Kecamatan Denpasar Selatan, Denpasar, Bali, Indonesia</p>

  <iframe 
    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3948.020042691497!2d115.21402531529926!3d-8.650985694720094!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2dd240b5a6e395f5%3A0x301f9a0f7a4d6be0!2sDenpasar%2C%20Bali!5e0!3m2!1sid!2sid!4v1701420000000"
    allowfullscreen=""
    loading="lazy">
  </iframe>

  <table>
    <tr>
      <th>No</th>
      <th>Hari</th>
      <th>Tanggal</th>
      <th>Suhu (°C)</th>
      <th>Kelembapan</th>
    </tr>

    <tr>
      <td>1</td>
      <td>Senin</td>
      <td>01/12/2025</td>
      <td>30°C</td>
      <td>67%</td>
    </tr>

    <tr>
      <td>2</td>
      <td>Selasa</td>
      <td>02/12/2025</td>
      <td>26°C</td>
      <td>89%</td>
    </tr>

    <tr>
      <td>3</td>
      <td>Rabu</td>
      <td>03/12/2025</td>
      <td>26°C</td>
      <td>86%</td>
    </tr>

    <tr>
      <td>4</td>
      <td>Kamis</td>
      <td>04/12/2025</td>
      <td>26°C</td>
      <td>90%</td>
    </tr>

    <tr>
      <td>5</td>
      <td>Jum'at</td>
      <td>05/12/2025</td>
      <td>29°C</td>
      <td>90%</td>
    </tr>

    <tr>
      <td>6</td>
      <td>Sabtu</td>
      <td>06/12/2025</td>
      <td>25°C</td>
      <td>90%</td>
    </tr>

    <tr>
      <td>7</td>
      <td>Minggu</td>
      <td>07/12/2025</td>
      <td>25°C</td>
      <td>90%</td>
    </tr>
  </table>

  <footer>
    dibuat oleh &copy; Erdian Marga
  </footer>

</body>

</html>
