Title: Parcours scolaire


<section class="parcours-futuriste">
  <h2 class="title-futuriste">🚀 Mon Parcours Scolaire</h2>
  <div class="timeline-futuriste">

    <div class="event">
      <div class="event-marker"></div>
      <div class="event-content">
        <h3>Baccalauréat Scientifique</h3>
        <span class="event-date">2019 - 2022</span>
        <p><strong>Lycée Mare Caree, Moissy Cramayel</strong></p>
        <p>Mention Bien. Spécialité STI2D EE. Bases solides en logique et analyse.</p>
      </div>
    </div>

    <div class="event">
      <div class="event-marker"></div>
      <div class="event-content">
        <h3>BTS Services Informatiques aux Organisations (SIO)</h3>
        <span class="event-date">2022 - 2023 </span>
        <p><strong>IUT de SENART</strong></p>
        <p>Spécialisation en développement, cybersécurité et gestion de projets. Plusieurs projets professionnels réalisés.</p>
      </div>
    </div>

    <div class="event">
      <div class="event-marker"></div>
      <div class="event-content">
        <h3>Stage en entreprise</h3>
        <span class="event-date">Été 2024</span>
        <p><strong>Tech Innovante, Paris</strong></p>
        <p>Sécurisation d’application web, rédaction de documentation technique, travail collaboratif avec l’équipe dev.</p>
      </div>
    </div>

    <div class="event">
      <div class="event-marker"></div>
      <div class="event-content">
        <h3>Projet de fin d’année</h3>
        <span class="event-date">2025</span>
        <p><strong>Développement d’une plateforme sécurisée</strong></p>
        <p>Utilisation de Python, Django, DevOps, livraison complète avec présentation finale.</p>
      </div>
    </div>

  </div>
</section>

<style>
  /* Conteneur général */
  .parcours-futuriste {
    max-width: 800px;
    margin: 4rem auto;
    padding: 2rem;
    background: rgba(10, 20, 30, 0.5); /* Fond semi-transparent sombre */
    border-radius: 15px;
    box-shadow: 0 0 25px rgba(0, 255, 255, 0.4);
    color: #e0f7fa;
    font-family: 'Orbitron', sans-serif; /* Police futuriste, tu peux importer Orbitron Google Font */
  }

  /* Titre */
  .title-futuriste {
    font-size: 3rem;
    text-align: center;
    color: #00ffff;
    text-shadow:
      0 0 10px #00ffff,
      0 0 20px #00ffff,
      0 0 40px #00ffff;
    margin-bottom: 3rem;
  }

  /* Timeline verticale */
  .timeline-futuriste {
    position: relative;
    padding-left: 40px;
    border-left: 3px solid #00ffff;
  }

  /* Barre verticale animée */
  .timeline-futuriste::before {
    content: '';
    position: absolute;
    left: 12px;
    top: 0;
    width: 4px;
    height: 100%;
    background: linear-gradient(180deg, #00ffff 0%, #004d4d 100%);
    filter: drop-shadow(0 0 6px #00ffff);
    animation: pulseLine 3s infinite alternate;
    border-radius: 2px;
  }

  @keyframes pulseLine {
    0% { opacity: 1; }
    100% { opacity: 0.6; }
  }

  /* Un événement sur la timeline */
  .event {
    position: relative;
    margin-bottom: 3.5rem;
  }

  /* Les marqueurs ronds */
  .event-marker {
    position: absolute;
    left: -19px;
    top: 0;
    width: 30px;
    height: 30px;
    background: #00ffff;
    border-radius: 50%;
    box-shadow:
      0 0 10px #00ffff,
      0 0 20px #00ffff,
      0 0 30px #00ffff;
    animation: glowPulse 3s infinite alternate;
  }

  @keyframes glowPulse {
    0% {
      box-shadow:
        0 0 10px #00ffff,
        0 0 20px #00ffff,
        0 0 30px #00ffff;
    }
    100% {
      box-shadow:
        0 0 20px #00ffff,
        0 0 40px #00ffff,
        0 0 60px #00ffff;
    }
  }

  /* Contenu de chaque événement */
  .event-content h3 {
    margin: 0 0 0.3rem;
    font-size: 1.8rem;
    color: #00e5ff;
    text-shadow:
      0 0 5px #00e5ff,
      0 0 10px #00e5ff;
  }

  .event-date {
    font-style: italic;
    color: #4dd0e1;
    font-size: 1rem;
    margin-bottom: 0.8rem;
    display: inline-block;
    text-shadow: 0 0 4px #4dd0e1;
  }

  .event-content p {
    font-size: 1rem;
    line-height: 1.5;
    color: #b2ebf2;
    text-shadow: 0 0 3px #007c91;
  }

  /* Responsive */
  @media (max-width: 600px) {
    .parcours-futuriste {
      padding: 1rem;
      margin: 2rem 1rem;
    }
    .title-futuriste {
      font-size: 2rem;
      margin-bottom: 2rem;
    }
    .event-content h3 {
      font-size: 1.4rem;
    }
  }
</style>

<!-- N'oublie pas d'ajouter cette font dans ton <head> -->
<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&display=swap" rel="stylesheet" />
