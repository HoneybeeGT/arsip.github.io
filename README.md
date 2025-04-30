<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Arsip Soal</title>
  <style>
    /* Set the background image for the entire page */
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: url('https://files.catbox.moe/k149m3.jpg') no-repeat center center fixed;
      background-size: cover;
      color: #c7c7c7;
    }  
    header {
      background-color: rgba(23, 26, 33, 0.8);
      padding: 20px;
      text-align: center;
      color: #66c0f4;
    }
    /* Removing hero-specific background so it becomes part of global background */
    .hero {
      display: flex;
      align-items: center;
      justify-content: center;
      height: 300px;
      color: #fff;
      font-size: 2em;
      font-weight: bold;
      text-shadow: 2px 2px 4px #000;
    }
    /* Adding a semi-transparent background for the container improves readability */
    .container {
      padding: 30px 20px;
      max-width: 1000px;
      margin: 0 auto;
      background: rgba(26, 26, 26, 0.8);
      border-radius: 10px;
    }
    .points-menu {
      display: flex;
      flex-direction: column;
      gap: 15px;
      margin-bottom: 40px;
    }
    /* Each point item contains the clickable link and its description */
    .point-item {
      background: rgba(42, 42, 42, 0.8);
      border-radius: 5px;
      padding: 15px 20px;
    }
    /* Clickable link styling */
    .point-link {
      text-decoration: none;
      color: #c7c7c7;
      display: block;
      cursor: pointer;
      border-left: 5px solid #66c0f4;
      padding-left: 10px;
      transition: background-color 0.3s;
    }
    .point-link:hover {
      background-color: rgba(51, 51, 51, 0.8);
    }
    /* Point content is no longer hidden with display:none.
       Instead, we hide it via max-height and opacity and toggle an "open" class. */
    .point-content {
      overflow: hidden;
      max-height: 0;
      opacity: 0;
      transition: max-height 0.5s ease-out, opacity 0.5s ease-out;
      margin-top: 15px;
      padding-top: 15px;
      border-top: 1px solid #444;
    }
    /* When "open", allow the content to expand and fade in */
    .point-content.open {
      max-height: 1000px;  /* Use a value high enough to show the content fully */
      opacity: 1;
    }
    .point-content h2 {
      color: #66c0f4;
    }
    footer {
      background-color: rgba(23, 26, 33, 0.8);
      text-align: center;
      padding: 20px;
      color: #7f8c8d;
      font-size: 0.9em;
    }
    @media (max-width: 600px) {
      .hero {
        font-size: 1.5em;
        height: 200px;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Kesultanan Arsip</h1>
  </header>

  <div class="hero">
    Kesultanan Arsip Soal adalah kerajaan yang didirikan di Jawa pada abad ke-21.
  </div>

  <div class="container">
    <!-- Clickable List with Inline Descriptions -->
    <div class="points-menu">
      <div class="point-item">
        <a class="point-link" href="#">1. Awal Berdirinya</a>
        <div class="point-content">
          <h2>Awal Berdirinya</h2>
          <p>
            Kesultanan Arsip pertama di dirikan pada abad ke-21 oleh sekelompok orang.
            Pada awalnya dinamakan "Biologi nyehhh" sebelum diubah menjadi Arsip Soal setahun kemudian.
          </p>
        </div>
      </div>
      <div class="point-item">
        <a class="point-link" href="#">2. Letak</a>
        <div class="point-content">
          <h2>Letak</h2>
          <p>
            Kesultanan Arsip terletak di Kalasan, dengan ibu kota berada di depan F1.
            Pada awalnya ibukota kerajaan arsip berada di Rumah Ana sebelum dipindahkan ke depan F1.
          </p>
        </div>
      </div>
      <div class="point-item">
        <a class="point-link" href="#">3. Tokoh</a>
        <div class="point-content">
          <h2>Tokoh </h2>
          <h3>Septiana</h3>
          <p>
            Dia adalah salah satu tokoh penting yang mengide untuk membuat Kesultanan Arsip, dengan rumahnya
            menjadi ibu kota awal kesultanan Arsip.
          </p>
          <h3>Astrid</h3>
          <p>
            Dia adalah tokoh yang berperan penting dalam projek pertama kerajaan, yaitu projek "Kimchi Radiasi".
          </p>
          <h3>Atha</h3>
          <p>
            Dia merupakan tokoh yang berperan penting terhadap kebudayaan Arsip dikarenakan jiwa seninya yang begitu hebatnya.
          </p>
          <h3>Hardana</h3>
          <p>
            Juga dikenal sebagai Lidya, dia adalah tokoh penting yang berperan dalam proses penyusunan Kesultanan Arsip bersama Septiana.
          </p>
          <h3>Affan</h3>
          <p>
            Tidak banyak yang diketahui tentang tokoh ini karena jarang kehadirannya, namun dia adalah satu-satunya tokoh yang normal, membuat Kerajaan Arsip kokoh.
          </p>
          <h3>Raju</h3>
          <p>
            Juga dikenal sebagai Rafi', dia adalah supplier utama dan pemilik markas rahasia bernama "Muara Salju" yang digunakan untuk eksperimen Arsip seperti Projek Kimchi Radiasi.
          </p>
          <h3>Akmal</h3>
          <p>
            Awalnya dia bukanlah warga Kesultanan, namun dia diterima atas request istimewa dari pendiri- pendiri arsip. Bersama dengan Atha, dia telah membawa budaya India kepada Kesultanan Arsip.
          </p>
        </div>
      </div>
      <div class="point-item">
        <a class="point-link" href="#">4. Getting Around</a>
        <div class="point-content">
          <h2>Getting Around</h2>
          <p>
            Transportation options and how to navigate the area.
          </p>
        </div>
      </div>
      <div class="point-item">
        <a class="point-link" href="#">5. Best Time to Visit</a>
        <div class="point-content">
          <h2>Best Time to Visit</h2>
          <p>
            Seasonal information and weather tips.
          </p>
        </div>
      </div>
      <div class="point-item">
        <a class="point-link" href="#">6. Insider Tips</a>
        <div class="point-content">
          <h2>Insider Tips</h2>
          <p>
            Lesser-known facts or recommendations from locals.
          </p>
        </div>
      </div>
      <div class="point-item">
        <a class="point-link" href="#">7. Bukti Sejarah </a>
        <div class="point-content">
          <h2>Bukti Sejarah</h2>
          <p>
          </p>
          <img src="https://files.catbox.moe/yifsiu.jpg" alt="Example Accommodation" style="width: 100%; border-radius: 5px;">
        </div>
      </div>
    </div>
  </div>

  <footer>
    &copy; 2025 Explore Arsip coy | IJIIIJIJIJ 
  </footer>

  <script>
    document.addEventListener("DOMContentLoaded", function() {
      const links = document.querySelectorAll(".point-link");
      
      links.forEach(link => {
        link.addEventListener("click", function(e) {
          e.preventDefault();
          const content = this.nextElementSibling;
          
          // Toggle the 'open' class to smoothly transition the panel
          content.classList.toggle("open");
        });
      });
    });
  </script>
</body>
</html>
