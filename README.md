<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Komputer Jaringan | Portofolio IT</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #f8f9fa;
        }
        .hero-section {
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), 
                        url('https://images.unsplash.com/photo-1544197150-b99a580bb7a8?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            color: white;
            padding: 100px 0;
        }
        .navbar-brand {
            font-weight: bold;
            letter-spacing: 1px;
        }
        footer {
            background-color: #212529;
            color:white ;
            padding: 30px 0;
        }
    </style>
</head>
<body>

    <nav class="navbar navbar-expand-lg navbar-dark bg-dark sticky-top">
        <div class="container">
            <a class="navbar-brand" href="#">TKJ NETWORK</a>
            <button class="navbar-toggler" ltype="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link active" href="#home">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#about">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <header id="home" class="hero-section text-center">
        <div class="container">
            <h1 class="display-4 fw-bold">Dunia Komputer & Jaringan</h1>
            <p class="lead">Membangun konektivitas, mengelola infrastruktur, dan mengamankan data.</p>
            <a href="#about" class="btn btn-primary btn-lg mt-3">Pelajari Selengkapnya</a>
        </div>
    </header>

    <section id="about" class="container py-5">
        <div class="row align-items-center">
            <div class="col-md-6">
                <h2>Tentang Kami</h2>
                <p>Kami berfokus pada pengembangan infrastruktur jaringan komputer, mulai dari instalasi LAN, konfigurasi Router (Mikrotik/Cisco), hingga keamanan jaringan (Cyber Security).</p>
                <p>Keahlian kami mencakup:</p>
                <ul>
                    <li>Administrasi Server</li>
                    <li>Routing & Switching</li>
                    <li>Pemasangan Fiber Optic</li>
                    <li>Troubleshooting Perangkat Keras</li>
                </ul>
            </div>
            <div class="col-md-6 text-center">
                

[Image of computer network diagram]

            </div>
        </div>
    </section>

    <section id="contact" class="bg-light py-5">
        <div class="container">
            <h2 class="text-center mb-4">Hubungi Kami</h2>
            <div class="row justify-content-center">
                <div class="col-md-6">
                    <form>
                        <div class="mb-3">
                            <label class="form-label">Nama Lengkap</label>
                            <input type="text" class="form-control" placeholder="Masukkan nama Anda">
                        </div>
                        <div class="mb-3">
                            <label class="form-label">Email</label>
                            <input type="email" class="form-control" placeholder="nama@email.com">
                        </div>
                        <div class="mb-3">
                            <label class="form-label">Pesan</label>
                            <textarea class="form-control" rows="4" placeholder="Apa yang bisa kami bantu?"></textarea>
                        </div>
                        <button type="submit" class="btn btn-dark w-100">Kirim Pesan</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <footer class="text-center">
        <div class="container">
            <p class="mb-0">&copy; 2026 Teknik Komputer Jaringan. All Rights Reserved.</p>
            <small class="text-muted">Dibuat dengan Bootstrap 5</small>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>