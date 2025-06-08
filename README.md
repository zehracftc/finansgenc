<!DOCTYPE html>
<html lang="tr">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kentsel Dönüşüm Ortakları</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
  
  <script src="https://cdn.jsdelivr.net/npm/chartjs-plugin-datalabels@2.2.0/dist/chartjs-plugin-datalabels.min.js"></script>
  
  <style>
    body {
      margin: 0;
      padding: 0;
    }

    .navbar-brand {
      font-weight: bold;
    }

    .hero {
      background-image: url('https://cdn.gamma.app/0ef3vil4frou02i/generated-images/nshqIzN7YHHjf_200XZe1.jpg');
      background-size: cover;
      background-position: center;
      color: white;
      padding: 6rem 0;
      text-align: center;
    }

    .hero h1,
    .hero p {
      text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
    }

    .card {
      margin-bottom: 1rem;
    }

    .footer {
      background-color: #343a40;
      color: white;
      padding: 1rem;
      text-align: center;
    }

    .modal-header {
      background-color: #198754;
      color: white;
    }
  </style>
</head>

<body>
  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">Kentsel Dönüşüm Ortakları</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#giris">Giriş Yap</a></li>
          <li class="nav-item"><a class="nav-link" href="#giris">Kayıt Ol</a></li>
          <li class="nav-item"><a class="nav-link" href="#projeler">Projeler</a></li>
          <li class="nav-item"><a class="nav-link" href="#yatirim">Yatırımlarım</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero -->
  <section class="hero">
    <div class="container">
      <h1 class="display-5">Güvenli ve Şeffaf Yatırımlarla Şehirleri Dönüştürüyoruz</h1>
      <p class="lead">Kentsel dönüşüm projelerine katılım finans modeliyle yatırım yapın, hem kazanın hem şehri dönüştürün.</p>
    </div>
  </section>

  <!-- Projeler -->
  <section class="container my-5" id="projeler">
    <h2 class="mb-4">Mevcut Projeler</h2>
    <div class="row">
      <!-- Proje Kartları -->
      <!-- Kadıköy -->
      <div class="col-md-4">
        <div class="card">
          <img src="https://www.habervesaire.com/wp-content/uploads/2018/10/kadikoy-kentsel-donusum-yagmur-tezbora.jpg" class="card-img-top" alt="Kadıköy Projesi">
          <div class="card-body">
            <h5 class="card-title">Kadıköy Dönüşüm Projesi</h5>
            <p class="card-text">Depreme dayanıklı yeni konutlar ve sosyal alanlar.</p>
            <a href="#" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#modalKadikoy">Detayları Gör</a>
             <a href="#" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#modalKadikoy2">Fon Al</a>
          </div>
        </div>
      </div>
      <!-- Bağcılar -->
      <div class="col-md-4">
        <div class="card">
          <img src="https://media-blog.zingat.com/uploads/2021/04/ibb.bagcilar.jpg" class="card-img-top" alt="Bağcılar Projesi">
          <div class="card-body">
            <h5 class="card-title">Bağcılar Kentsel Yenileme</h5>
            <p class="card-text">Kentsel estetik ve sosyal alanlar kazandırma hedefli proje.</p>
            <a href="#" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#modalBagcilar">Detayları Gör</a>
           <a href="#" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#modalBagcilar">Fon Al</a>
          </div>
        </div>
      </div>
      <!-- Gaziosmanpaşa -->
      <div class="col-md-4">
        <div class="card">
          <img src="https://cdnuploads.aa.com.tr/uploads/userFiles/a54ea27f-6036-4f79-88c6-6bc9ba19a35d/08_Nisan%2F06%20temmuz%2F09%2FAA-31913451.jpg" class="card-img-top" alt="Gaziosmanpaşa Projesi">
          <div class="card-body">
            <h5 class="card-title">Gaziosmanpaşa Karma Proje</h5>
            <p class="card-text">Ticari + konut alanları ile yatırım fırsatı.</p>
            <a href="#" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#modalGop">Detayları Gör</a>
          <a href="#" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#modalGop">Fon Al</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Kadıköy Modal -->
  <div class="modal fade" id="modalKadikoy" tabindex="-1" aria-labelledby="modalKadikoyLabel" aria-hidden="true">
    <div class="modal-dialog modal-lg">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title" id="modalKadikoyLabel">Kadıköy Dönüşüm Projesi Detayları</h5>
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Kapat"></button>
        </div>
        <div class="modal-body">
          <p><strong>Proje Özeti:</strong> Kadıköy'de depreme dayanıklı konutlar ve sosyal yaşam alanları.</p>
          <p><strong>Toplam Yatırım:</strong> 250 milyon TL</p>
          <p><strong>Beklenen Getiri Oranı:</strong> %15 (yıllık)</p>
          <p><strong>Proje Süresi:</strong> 24 Ay</p>
          <p><strong>Yatırımcı Sayısı:</strong> 432</p>
          <canvas id="kadikoyChart" height="150"></canvas>
          <section style="max-width: 400px; margin: auto; padding: 20px;">
            <canvas id="investmentChart"></canvas>
          </section>
          
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Kapat</button>
        </div>
      </div>
    </div>
  </div>
   <!-- Kadıköy Modal -->
  <div class="modal fade" id="modalKadikoy2" tabindex="-1" aria-labelledby="modalKadikoyLabel" aria-hidden="true">
    <div class="modal-dialog modal-lg">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title" id="modalKadikoyLabel">Kadıköy Dönüşüm Projesi Detayları</h5>
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Kapat"></button>
        </div>
        <div class="modal-body">
         
          
         <section class="container my-5" id="yatirim">
  <h2 class="mb-4">Yatırımlarım ve Gelir Analizi</h2>

  <div class="mb-3">
    <label for="yatirimTutar" class="form-label"><strong>Yatırmak İstediğiniz Tutar (TL):</strong></label>
    <input type="number" class="form-control" id="yatirimTutar" placeholder="Örneğin: 1500">
  </div>
  <button class="btn btn-success mb-3" id="hesaplaBtn">Yatırımı Kaydet ve Hisseyi Hesapla</button>

  <div id="hisseBilgisi" class="alert alert-info" style="display: none;">
    Toplam <strong><span id="hisseAdedi">0</span></strong> hisseye sahip olacaksınız.
  </div>

<button class="btn btn-success mb-3" id="satinAlBtn">SATIN AL</button>

       
          </section>
          
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Kapat</button>
        </div>
      </div>
    </div>
  </div>

  <!-- Bağcılar Modal (Boş içerik örnek) -->
  <div class="modal fade" id="modalBagcilar" tabindex="-1" aria-labelledby="modalBagcilarLabel" aria-hidden="true">
    <div class="modal-dialog modal-lg">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title" id="modalBagcilarLabel">Bağcılar Projesi Detayları</h5>
          <button type="button" class="btn-close" data-bs-dismiss="modal"></button>
        </div>
        <div class="modal-body">
          <p>Bu proje detayları yakında eklenecektir.</p>
        </div>
      </div>
    </div>
  </div>

  <!-- Gaziosmanpaşa Modal (Boş içerik örnek) -->
  <div class="modal fade" id="modalGop" tabindex="-1" aria-labelledby="modalGopLabel" aria-hidden="true">
    <div class="modal-dialog modal-lg">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title" id="modalGopLabel">Gaziosmanpaşa Projesi Detayları</h5>
          <button type="button" class="btn-close" data-bs-dismiss="modal"></button>
        </div>
        <div class="modal-body">
          <p>Bu proje detayları yakında eklenecektir.</p>
        </div>
      </div>
    </div>
  </div>

  <!-- Yatırım Analizi -->
  <section class="container my-5" id="yatirim">
    <h2 class="mb-4">Yatırımlarım ve Gelir Analizi</h2>
    <canvas id="myChart"></canvas>
  </section>

  <!-- Giriş Formu -->
  <section class="container my-5" id="giris">
    <h2 class="mb-4">Kullanıcı Girişi</h2>
    <form>
      <div class="mb-3">
        <label for="email" class="form-label">E-posta</label>
        <input type="email" class="form-control" id="email">
      </div>
      <div class="mb-3">
        <label for="password" class="form-label">Şifre</label>
        <input type="password" class="form-control" id="password">
      </div>
      <button type="submit" class="btn btn-primary">Giriş Yap</button>
    </form>
  </section>

  <!-- Footer -->
  <footer class="footer">
    <div class="container">
      <p>&copy; 2025 Kentsel Dönüşüm Ortakları - Tüm Hakları Saklıdır</p>
    </div>
  </footer>

  <!-- Scripts -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
  <script>
    // Ana yatırım çizelgesi
    const ctx = document.getElementById('myChart').getContext('2d');
    new Chart(ctx, {
      type: 'line',
      data: {
        labels: ['Ocak', 'Şubat', 'Mart', 'Nisan', 'Mayıs', 'Haziran'],
        datasets: [
          {
            label: 'Kadıköy Projesi',
            data: [120, 135, 150, 160, 175, 190],
            borderColor: '#198754',
            fill: false,
            tension: 0.3
          },
          {
            label: 'Bağcılar Projesi',
            data: [100, 105, 120, 130, 140, 150],
            borderColor: '#0d6efd',
            fill: false,
            tension: 0.3
          },
          {
            label: 'Gaziosmanpaşa Projesi',
            data: [130, 140, 160, 180, 195, 210],
            borderColor: '#ffc107',
            fill: false,
            tension: 0.3
          }
        ]
      },
      options: {
        responsive: true,
        plugins: {
          title: {
            display: true,
            text: 'Aylık Getiri Eğrisi'
          },
          tooltip: {
            mode: 'index',
            intersect: false
          },
          legend: {
            position: 'top'
          }
        },
        interaction: {
          mode: 'nearest',
          axis: 'x',
          intersect: false
        },
        scales: {
          y: {
            beginAtZero: false
          }
        }
      }
    });

    // Kadıköy yatırım donut grafiği
    
  
  


    const ctxInvestment = document.getElementById('investmentChart').getContext('2d');

const investmentChart = new Chart(ctxInvestment, {
  type: 'doughnut',
  data: {
    labels: ['Toplam Gerekli Yatırım (250m TL)', 'Mevcut Yatırım (178m TL)'],
    datasets: [
      {
        data: [250, 178],
        backgroundColor: ['#0d6efd', '#198754'],
        borderColor: '#fff',
        borderWidth: 2,
        hoverOffset: 30
      }
    ]
  },
  options: {
    responsive: true,
    plugins: {
      title: {
        display: true,
        text: 'Yatırım Durumu Detayları',
        font: {
          size: 18,
          weight: 'bold'
        }
      },
      legend: {
        position: 'bottom',
        labels: {
          color: '#333',
          font: {
            size: 14,
            weight: 'bold'
          }
        }
      },
      tooltip: {
        callbacks: {
          label: context => `${context.label}: ${context.parsed} milyon TL`
        }
      }
    },
    cutout: '70%',
    animation: {
      animateRotate: true,
      animateScale: true
    }
  }
});
document.getElementById('hesaplaBtn').addEventListener('click', function () {
  const tutar = parseFloat(document.getElementById('yatirimTutar').value);
  const birimFiyat = 30; // 1 hisse = 3 TL

  if (!isNaN(tutar) && tutar > 0) {
    const hisseAdedi = (tutar / birimFiyat).toFixed(2);
    document.getElementById('hisseAdedi').textContent = hisseAdedi;
    document.getElementById('hisseBilgisi').style.display = 'block';
  } else {
    document.getElementById('hisseBilgisi').style.display = 'none';
    alert('Lütfen geçerli bir tutar girin.');
  }
});

  // Giriş formu submit işlemi
  document.getElementById('loginForm').addEventListener('submit', function(event) {
    event.preventDefault();
    const email = document.getElementById('email').value;
    const password = document.getElementById('password').value;

    if (email === 'test@mail.com' && password === '1234') {
      alert('Giriş başarılı. Hoş geldiniz!');
    } else {
      alert('Geçersiz e-posta veya şifre. Lütfen tekrar deneyin.');
    }
  });
   
  </script>
</body>

</html>
