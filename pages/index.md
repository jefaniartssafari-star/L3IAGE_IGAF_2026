---
title: Accueil
description: JM Safari Tech - Rendre la technologie accessible à tous.
---

<style>
/* Configuration de base */
:root {
    --primary: #fba731;
    --bg-dark: #0d0d0d;
    --bg-card: #1a1a1a;
    --text-light: #ffffff;
    --text-muted: #a0a0a0;
}

body {
    background-color: var(--bg-dark);
    color: var(--text-light);
    font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
}

/* Section Héro (Bannière) */
.hero {
    background: linear-gradient(135deg, var(--primary) 0%, #e08c1a 100%);
    color: #000;
    padding: 5rem 2rem;
    border-radius: 0 0 30px 30px;
    text-align: center;
}

.hero h1 {
    font-size: 3.5rem;
    font-weight: 800;
    line-height: 1.1;
    margin-bottom: 1.5rem;
}

.hero p {
    font-size: 1.2rem;
    max-width: 700px;
    margin: 0 auto 2.5rem auto;
    font-weight: 500;
}

.btn-primary {
    background-color: #000;
    color: #fff;
    padding: 15px 35px;
    border-radius: 50px;
    text-decoration: none;
    font-weight: bold;
    font-size: 1.1rem;
    transition: transform 0.3s ease;
    display: inline-block;
}

.btn-primary:hover {
    transform: scale(1.05);
    color: var(--primary);
}

/* Section Expertises */
.section-header {
    text-align: center;
    margin: 4rem 0 2rem 0;
}

.section-header h2 {
    color: var(--primary);
    text-transform: uppercase;
    letter-spacing: 3px;
    font-size: 1rem;
}

.section-header h3 {
    font-size: 2.5rem;
    margin-top: 0.5rem;
}

/* Grille des cartes */
.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 2rem;
}

.card {
    background-color: var(--bg-card);
    border-radius: 20px;
    overflow: hidden;
    border: 1px solid #333;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    display: flex;
    flex-direction: column;
}

.card:hover {
    transform: translateY(-10px);
    box-shadow: 0 10px 20px rgba(251, 167, 49, 0.2);
}

.card-image {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-bottom: 3px solid var(--primary);
}

.card-content {
    padding: 1.5rem;
    flex-grow: 1;
}

.card-icon {
    background-color: var(--primary);
    color: #000;
    width: 50px;
    height: 50px;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 24px;
    margin-top: -40px;
    margin-bottom: 1rem;
    position: relative;
    z-index: 10;
}

.card h4 {
    font-size: 1.5rem;
    margin: 0 0 0.5rem 0;
}

.card p {
    color: var(--text-muted);
    font-size: 1rem;
    margin: 0;
}

/* Section Contact */
.contact {
    text-align: center;
    background-color: var(--bg-card);
    max-width: 800px;
    margin: 5rem auto;
    padding: 3rem 2rem;
    border-radius: 20px;
    border: 1px solid #333;
}

.contact h2 {
    font-size: 2rem;
    margin-bottom: 1rem;
}

.btn-whatsapp {
    background-color: #25D366;
    color: white;
    padding: 15px 35px;
    border-radius: 50px;
    text-decoration: none;
    font-weight: bold;
    font-size: 1.2rem;
    display: inline-flex;
    align-items: center;
    gap: 10px;
    margin-top: 1.5rem;
    transition: background-color 0.3s;
}

.btn-whatsapp:hover {
    background-color: #128C7E;
    color: white;
}

/* Responsive */
@media (max-width: 768px) {
    .hero h1 { font-size: 2.5rem; }
    .section-header h3 { font-size: 2rem; }
}
</style>

<div class="hero">
    <h1>Rendre la technologie<br>accessible à tous.</h1>
    <p>Sites internet, outils d'IA, tutoriels et idées de projets : tout ce qu'il faut pour avancer dans le monde numérique.</p>
    <a href="#expertise" class="btn-primary">Découvrir nos services &rarr;</a>
</div>

<div id="expertise">
    <div class="section-header">
        <h2>Nos domaines d'expertise</h2>
        <h3>Quatre univers pour apprendre, créer et innover.</h3>
    </div>
    <div class="grid">
        <!-- Carte 1 -->
        <div class="card">
            <img src="images/web.jpg" class="card-image" alt="Développement Web">
            <div class="card-content">
                <div class="card-icon">💻</div>
                <h4>Développement web</h4>
                <p>Créer des sites internet modernes et sur mesure.</p>
            </div>
        </div>
        <!-- Carte 2 -->
        <div class="card">
            <img src="images/ia.jpg" class="card-image" alt="Intelligence Artificielle">
            <div class="card-content">
                <div class="card-icon">🧠</div>
                <h4>Intelligence Artificielle</h4>
                <p>Découvrir et maîtriser les outils IA de demain.</p>
            </div>
        </div>
        <!-- Carte 3 -->
        <div class="card">
            <img src="images/maintenance.jpg" class="card-image" alt="Informatique">
            <div class="card-content">
                <div class="card-icon">⚙️</div>
                <h4>Informatique</h4>
                <p>Tutoriels et conseils pour maîtriser votre matériel.</p>
            </div>
        </div>
        <!-- Carte 4 -->
        <div class="card">
            <img src="images/innovation.jpg" class="card-image" alt="Innovation">
            <div class="card-content">
                <div class="card-icon">💡</div>
                <h4>Innovation</h4>
                <p>Des idées et des projets numériques pour l'avenir.</p>
            </div>
        </div>
    </div>
</div>

<div class="contact">
    <h2>Prêt à démarrer votre projet ?</h2>
    <p>Discutons de vos idées et de la façon dont nous pouvons vous aider à les concrétiser.</p>
    <a href="https://wa.me/243981203927" target="_blank" class="btn-whatsapp">
        💬 Discuter sur WhatsApp
    </a>
</div>