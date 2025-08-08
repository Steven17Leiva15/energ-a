# energ-a
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Información sobre Energía</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        .energy-icon {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            color: #0d6efd;
        }
        .card-hover:hover {
            transform: translateY(-5px);
            transition: all 0.3s ease;
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        }
        .hero-section {
            background: linear-gradient(135deg, #6e8efb, #a777e3);
            color: white;
            padding: 5rem 0;
            margin-bottom: 3rem;
        }
        .stat-card {
            border-left: 5px solid #0d6efd;
        }
    </style>
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
        <div class="container">
            <a class="navbar-brand" href="#">
                <i class="fas fa-bolt me-2"></i>Energía Global
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#tipos">Tipos</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#importancia">Importancia</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#estadisticas">Estadísticas</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#futuro">Futuro</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero-section text-center">
        <div class="container">
            <h1 class="display-4 fw-bold mb-4">El Poder de la Energía</h1>
            <p class="lead mb-5">Explora el mundo de la energía: sus formas, importancia y el futuro sostenible</p>
            <a href="#tipos" class="btn btn-light btn-lg px-4 me-2">Explorar</a>
            <a href="#futuro" class="btn btn-outline-light btn-lg px-4">Futuro Energético</a>
        </div>
    </section>

    <!-- Tipos de Energía -->
    <section id="tipos" class="py-5">
        <div class="container">
            <h2 class="text-center mb-5">Tipos de Energía</h2>
            <div class="row g-4">
                <!-- Card 1 -->
                <div class="col-md-4">
                    <div class="card h-100 card-hover">
                        <div class="card-body text-center">
                            <i class="fas fa-sun energy-icon"></i>
                            <h4 class="card-title">Energía Solar</h4>
                            <p class="card-text">Obtenida del sol mediante paneles fotovoltaicos o sistemas térmicos. Es renovable y abundante, con aplicaciones desde pequeñas calculadoras hasta grandes plantas de energía.</p>
                            <ul class="text-start">
                                <li>Renovable y limpia</li>
                                <li>Bajo mantenimiento</li>
                                <li>Disponibilidad variable</li>
                            </ul>
                        </div>
                    </div>
                </div>
                
                <!-- Card 2 -->
                <div class="col-md-4">
                    <div class="card h-100 card-hover">
                        <div class="card-body text-center">
                            <i class="fas fa-wind energy-icon"></i>
                            <h4 class="card-title">Energía Eólica</h4>
                            <p class="card-text">Generada por el movimiento del aire mediante turbinas eólicas. Una de las fuentes de energía renovable de más rápido crecimiento en el mundo.</p>
                            <ul class="text-start">
                                <li>Bajo impacto ambiental</li>
                                <li>Alto costo inicial</li>
                                <li>Depende de condiciones climáticas</li>
                            </ul>
                        </div>
                    </div>
                </div>
                
                <!-- Card 3 -->
                <div class="col-md-4">
                    <div class="card h-100 card-hover">
                        <div class="card-body text-center">
                            <i class="fas fa-fire energy-icon"></i>
                            <h4 class="card-title">Energía Fósil</h4>
                            <p class="card-text">Proviene de combustibles como carbón, petróleo y gas natural. Aunque es la fuente más utilizada, genera emisiones de gases de efecto invernadero.</p>
                            <ul class="text-start">
                                <li>Alta densidad energética</li>
                                <li>Finita y contaminante</li>
                                <li>Infraestructura desarrollada</li>
                            </ul>
                        </div>
                    </div>
                </div>
                
                <!-- Card 4 -->
                <div class="col-md-4">
                    <div class="card h-100 card-hover">
                        <div class="card-body text-center">
                            <i class="fas fa-water energy-icon"></i>
                            <h4 class="card-title">Hidroeléctrica</h4>
                            <p class="card-text">Generada por el movimiento del agua en represas o corrientes fluviales. Es una de las fuentes renovables más antiguas y eficientes.</p>
                            <ul class="text-start">
                                <li>Alta eficiencia</li>
                                <li>Impacto en ecosistemas</li>
                                <li>Dependencia de lluvias</li>
                            </ul>
                        </div>
                    </div>
                </div>
                
                <!-- Card 5 -->
                <div class="col-md-4">
                    <div class="card h-100 card-hover">
                        <div class="card-body text-center">
                            <i class="fas fa-atom energy-icon"></i>
                            <h4 class="card-title">Nuclear</h4>
                            <p class="card-text">Producida mediante reacciones de fisión nuclear en centrales especializadas. Genera grandes cantidades de energía con baja emisión directa de CO₂.</p>
                            <ul class="text-start">
                                <li>Alta producción energética</li>
                                <li>Residuos radiactivos</li>
                                <li>Alto costo y seguridad crítica</li>
                            </ul>
                        </div>
                    </div>
                </div>
                
                <!-- Card 6 -->
                <div class="col-md-4">
                    <div class="card h-100 card-hover">
                        <div class="card-body text-center">
                            <i class="fas fa-leaf energy-icon"></i>
                            <h4 class="card-title">Biomasa</h4>
                            <p class="card-text">Obtenida de materia orgánica como cultivos, residuos agrícolas o forestales. Puede ser renovable si se gestiona sosteniblemente.</p>
                            <ul class="text-start">
                                <li>Versátil (sólida, líquida, gaseosa)</li>
                                <li>Neutralidad en carbono discutible</li>
                                <li>Competencia con cultivos alimenticios</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Importancia de la Energía -->
    <section id="importancia" class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center mb-5">Importancia de la Energía</h2>
            <div class="row align-items-center">
                <div class="col-lg-6">
                    <img src="https://sf6colombia.com/storage/2023/05/La-importancia-de-la-energia-renovable-en-la-lucha-contra-el-cambio-climatico.jpg" alt="Importancia energía" class="img-fluid rounded mb-4 mb-lg-0">
                </div>
                <div class="col-lg-6">
                    <div class="accordion" id="accordionImportancia">
                        <div class="accordion-item">
                            <h2 class="accordion-header">
                                <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne">
                                    <i class="fas fa-industry me-2"></i> Desarrollo Económico
                                </button>
                            </h2>
                            <div id="collapseOne" class="accordion-collapse collapse show" data-bs-parent="#accordionImportancia">
                                <div class="accordion-body">
                                    La energía es fundamental para el funcionamiento de industrias, transporte y comercio. Países con mayor acceso a energía tienden a tener economías más desarrolladas. La disponibilidad energética afecta directamente la productividad y competitividad de las naciones.
                                </div>
                            </div>
                        </div>
                        <div class="accordion-item">
                            <h2 class="accordion-header">
                                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo">
                                    <i class="fas fa-home me-2"></i> Calidad de Vida
                                </button>
                            </h2>
                            <div id="collapseTwo" class="accordion-collapse collapse" data-bs-parent="#accordionImportancia">
                                <div class="accordion-body">
                                    El acceso a energía eléctrica mejora la calidad de vida permitiendo iluminación, climatización, conservación de alimentos, comunicación y entretenimiento. También es crucial para servicios médicos y educativos.
                                </div>
                            </div>
                        </div>
                        <div class="accordion-item">
                            <h2 class="accordion-header">
                                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree">
                                    <i class="fas fa-globe-americas me-2"></i> Impacto Ambiental
                                </button>
                            </h2>
                            <div id="collapseThree" class="accordion-collapse collapse" data-bs-parent="#accordionImportancia">
                                <div class="accordion-body">
                                    La producción y consumo de energía representan aproximadamente el 60% de las emisiones globales de gases de efecto invernadero. La transición a energías limpias es esencial para combatir el cambio climático y preservar los ecosistemas.
                                </div>
                            </div>
                        </div>
                        <div class="accordion-item">
                            <h2 class="accordion-header">
                                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseFour">
                                    <i class="fas fa-shield-alt me-2"></i> Seguridad Nacional
                                </button>
                            </h2>
                            <div id="collapseFour" class="accordion-collapse collapse" data-bs-parent="#accordionImportancia">
                                <div class="accordion-body">
                                    La independencia energética es crucial para la seguridad nacional. Países dependientes de importaciones energéticas son vulnerables a fluctuaciones de precios y tensiones geopolíticas. La diversificación de fuentes es una estrategia clave.
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Estadísticas -->
    <section id="estadisticas" class="py-5">
        <div class="container">
            <h2 class="text-center mb-5">Estadísticas Globales de Energía</h2>
            <div class="row g-4">
                <div class="col-md-3">
                    <div class="card stat-card h-100">
                        <div class="card-body">
                            <h3 class="card-title">81%</h3>
                            <p class="card-text">Porcentaje de energía global aún proveniente de combustibles fósiles (2023)</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card stat-card h-100">
                        <div class="card-body">
                            <h3 class="card-title">29%</h3>
                            <p class="card-text">Crecimiento de energía renovable en la última década</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card stat-card h-100">
                        <div class="card-body">
                            <h3 class="card-title">1.2B</h3>
                            <p class="card-text">Personas sin acceso a electricidad en el mundo</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card stat-card h-100">
                        <div class="card-body">
                            <h3 class="card-title">$1.7T</h3>
                            <p class="card-text">Inversión global anual en energía limpia (2023)</p>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="row mt-5">
                <div class="col-lg-6">
                    <h4 class="mb-3">Distribución Global de Fuentes Energéticas (2023)</h4>
                    <div class="table-responsive">
                        <table class="table table-striped">
                            <thead class="table-primary">
                                <tr>
                                    <th>Fuente</th>
                                    <th>Porcentaje</th>
                                    <th>Tendencia</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr>
                                    <td>Petróleo</td>
                                    <td>31%</td>
                                    <td><i class="fas fa-arrow-down text-danger"></i> Decreciente</td>
                                </tr>
                                <tr>
                                    <td>Carbón</td>
                                    <td>27%</td>
                                    <td><i class="fas fa-arrow-down text-danger"></i> Decreciente</td>
                                </tr>
                                <tr>
                                    <td>Gas Natural</td>
                                    <td>23%</td>
                                    <td><i class="fas fa-arrow-up text-success"></i> Creciente</td>
                                </tr>
                                <tr>
                                    <td>Renovables</td>
                                    <td>12%</td>
                                    <td><i class="fas fa-arrow-up text-success"></i> Creciente</td>
                                </tr>
                                <tr>
                                    <td>Nuclear</td>
                                    <td>5%</td>
                                    <td><i class="fas fa-equals text-warning"></i> Estable</td>
                                </tr>
                                <tr>
                                    <td>Hidroeléctrica</td>
                                    <td>2%</td>
                                    <td><i class="fas fa-equals text-warning"></i> Estable</td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                </div>
                <div class="col-lg-6">
                    <h4 class="mb-3">Proyección de Capacidad Renovable (2030)</h4>
                    <div class="progress mb-3" style="height: 30px;">
                        <div class="progress-bar bg-success" role="progressbar" style="width: 45%;" aria-valuenow="45" aria-valuemin="0" aria-valuemax="100">
                            Solar 45%
                        </div>
                    </div>
                    <div class="progress mb-3" style="height: 30px;">
                        <div class="progress-bar bg-info" role="progressbar" style="width: 35%;" aria-valuenow="35" aria-valuemin="0" aria-valuemax="100">
                            Eólica 35%
                        </div>
                    </div>
                    <div class="progress mb-3" style="height: 30px;">
                        <div class="progress-bar bg-warning" role="progressbar" style="width: 10%;" aria-valuenow="10" aria-valuemin="0" aria-valuemax="100">
                            Hidroeléctrica 10%
                        </div>
                    </div>
                    <div class="progress mb-3" style="height: 30px;">
                        <div class="progress-bar bg-secondary" role="progressbar" style="width: 7%;" aria-valuenow="7" aria-valuemin="0" aria-valuemax="100">
                            Biomasa 7%
                        </div>
                    </div>
                    <div class="progress mb-3" style="height: 30px;">
                        <div class="progress-bar bg-danger" role="progressbar" style="width: 3%;" aria-valuenow="3" aria-valuemin="0" aria-valuemax="100">
                            Geotérmica 3%
                        </div>
                    </div>
                    <div class="alert alert-info mt-4">
                        <i class="fas fa-info-circle me-2"></i> Se espera que las energías renovables representen el 40% de la generación global para 2030, según la Agencia Internacional de Energía.
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Futuro de la Energía -->
    <section id="futuro" class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center mb-5">El Futuro de la Energía</h2>
            <div class="row">
                <div class="col-lg-4 mb-4">
                    <div class="card h-100">
                        <img src="https://images.unsplash.com/photo-1508514177221-188b1cf16e9d?ixlib=rb-1.2.1&auto=format&fit=crop&w=600&q=80" class="card-img-top" alt="Tendencias energéticas">
                        <div class="card-body">
                            <h4 class="card-title">Tendencias Emergentes</h4>
                            <ul class="list-group list-group-flush">
                                <li class="list-group-item"><i class="fas fa-check-circle text-success me-2"></i> Almacenamiento en baterías a gran escala</li>
                                <li class="list-group-item"><i class="fas fa-check-circle text-success me-2"></i> Hidrógeno verde como vector energético</li>
                                <li class="list-group-item"><i class="fas fa-check-circle text-success me-2"></i> Redes inteligentes (smart grids)</li>
                                <li class="list-group-item"><i class="fas fa-check-circle text-success me-2"></i> Energía undimotriz (olas)</li>
                                <li class="list-group-item"><i class="fas fa-check-circle text-success me-2"></i> Fusión nuclear experimental</li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 mb-4">
                    <div class="card h-100">
                        <div class="card-body">
                            <h4 class="card-title">Desafíos Globales</h4>
                            <div class="mb-3">
                                <h6>Transición Energética</h6>
                                <div class="progress">
                                    <div class="progress-bar bg-warning" role="progressbar" style="width: 65%;" aria-valuenow="65" aria-valuemin="0" aria-valuemax="100">65% Países con planes</div>
                                </div>
                            </div>
                            <div class="mb-3">
                                <h6>Acceso Universal</h6>
                                <div class="progress">
                                    <div class="progress-bar bg-info" role="progressbar" style="width: 85%;" aria-valuenow="85" aria-valuemin="0" aria-valuemax="100">85% Cobertura actual</div>
                                </div>
                            </div>
                            <div class="mb-3">
                                <h6>Reducción Emisiones</h6>
                                <div class="progress">
                                    <div class="progress-bar bg-danger" role="progressbar" style="width: 40%;" aria-valuenow="40" aria-valuemin="0" aria-valuemax="100">40% Objetivo 2030</div>
                                </div>
                            </div>
                            <div class="alert alert-warning mt-4">
                                <i class="fas fa-exclamation-triangle me-2"></i> Se necesitan inversiones de $4-5 billones anuales para alcanzar los objetivos climáticos para 2030.
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 mb-4">
                    <div class="card h-100">
                        <div class="card-body">
                            <h4 class="card-title">Tecnologías Prometedoras</h4>
                            <div class="list-group">
                                <a href="#" class="list-group-item list-group-item-action">
                                    <div class="d-flex w-100 justify-content-between">
                                        <h6 class="mb-1">Perovskitas para paneles solares</h6>
                                        <small class="text-muted">+35% eficiencia</small>
                                    </div>
                                    <p class="mb-1 small">Nuevos materiales que podrían revolucionar la energía solar.</p>
                                </a>
                                <a href="#" class="list-group-item list-group-item-action">
                                    <div class="d-flex w-100 justify-content-between">
                                        <h6 class="mb-1">Reactores nucleares modulares</h6>
                                        <small class="text-muted">En desarrollo</small>
                                    </div>
                                    <p class="mb-1 small">Centrales nucleares más pequeñas y seguras.</p>
                                </a>
                                <a href="#" class="list-group-item list-group-item-action">
                                    <div class="d-flex w-100 justify-content-between">
                                        <h6 class="mb-1">Baterías de estado sólido</h6>
                                        <small class="text-muted">2025-2030</small>
                                    </div>
                                    <p class="mb-1 small">Mayor capacidad y seguridad en almacenamiento.</p>
                                </a>
                                <a href="#" class="list-group-item list-group-item-action">
                                    <div class="d-flex w-100 justify-content-between">
                                        <h6 class="mb-1">Captura de carbono</h6>
                                        <small class="text-muted">Piloto</small>
                                    </div>
                                    <p class="mb-1 small">Tecnologías para reducir emisiones de plantas existentes.</p>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Call to Action -->
    <section class="py-5 text-white" style="background: linear-gradient(135deg, #2c3e50, #4ca1af);">
        <div class="container text-center">
            <h2 class="mb-4">¿Quieres aprender más sobre energía sostenible?</h2>
            <p class="lead mb-5">Suscríbete a nuestro boletín para recibir información actualizada sobre tecnologías energéticas, políticas y oportunidades de inversión.</p>
            <form class="row g-3 justify-content-center">
                <div class="col-md-6">
                    <div class="input-group mb-3">
                        <input type="email" class="form-control form-control-lg" placeholder="Tu correo electrónico">
                        <button class="btn btn-primary btn-lg" type="submit">Suscribirse</button>
                    </div>
                    <div class="form-check">
                        <input class="form-check-input" type="checkbox" id="privacidad">
                        <label class="form-check-label" for="privacidad">
                            Acepto la política de privacidad
                        </label>
                    </div>
                </div>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white py-4">
        <div class="container">
            <div class="row">
                <div class="col-md-4 mb-4 mb-md-0">
                    <h5><i class="fas fa-bolt me-2"></i>Energía Global</h5>
                    <p class="small">Información detallada y actualizada sobre el mundo de la energía y su futuro sostenible.</p>
                    <div class="social-icons">
                        <a href="#" class="text-white me-2"><i class="fab fa-facebook-f"></i></a>
                        <a href="#" class="text-white me-2"><i class="fab fa-twitter"></i></a>
                        <a href="#" class="text-white me-2"><i class="fab fa-linkedin-in"></i></a>
                        <a href="#" class="text-white"><i class="fab fa-youtube"></i></a>
                    </div>
                </div>
                <div class="col-md-2 mb-4 mb-md-0">
                    <h5>Enlaces</h5>
                    <ul class="list-unstyled">
                        <li><a href="#tipos" class="text-white">Tipos</a></li>
                        <li><a href="#importancia" class="text-white">Importancia</a></li>
                        <li><a href="#estadisticas" class="text-white">Estadísticas</a></li>
                        <li><a href="#futuro" class="text-white">Futuro</a></li>
                    </ul>
                </div>
                <div class="col-md-3 mb-4 mb-md-0">
                    <h5>Recursos</h5>
                    <ul class="list-unstyled">
                        <li><a href="#" class="text-white">Informes anuales</a></li>
                        <li><a href="#" class="text-white">Calculadora energética</a></li>
                        <li><a href="#" class="text-white">Glosario técnico</a></li>
                        <li><a href="#" class="text-white">Mapa energético mundial</a></li>
                    </ul>
                </div>
                <div class="col-md-3">
                    <h5>Contacto</h5>
                    <ul class="list-unstyled small">
                        <li><i class="fas fa-map-marker-alt me-2"></i> Av. Energía 123, Madrid</li>
                        <li><i class="fas fa-phone me-2"></i> +34 910 123 456</li>
                        <li><i class="fas fa-envelope me-2"></i> info@energiaglobal.com</li>
                    </ul>
                </div>
            </div>
            <hr class="my-4">
            <div class="row">
                <div class="col-md-6 text-center text-md-start">
                    <p class="small mb-0">&copy; 2023 Energía Global. Todos los derechos reservados.</p>
                </div>
                <div class="col-md-6 text-center text-md-end">
                    <p class="small mb-0">
                        <a href="#" class="text-white">Términos de uso</a> | 
                        <a href="#" class="text-white">Política de privacidad</a>
                    </p>
                </div>
            </div>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
