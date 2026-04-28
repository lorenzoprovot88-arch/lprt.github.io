<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio | Lorenzo Provot</title>
    <style>
        /* Couleurs et Variables */
        :root {
            --primary: #2c3e50;
            --accent: #3498db;
            --bg: #f4f7f6;
            --text: #333;
        }

        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            line-height: 1.6;
            color: var(--text);
            background-color: var(--bg);
            margin: 0;
        }

        /* Navigation */
        nav {
            background: var(--primary);
            padding: 1rem;
            position: sticky;
            top: 0;
            z-index: 100;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        /* Header */
        header {
            background: linear-gradient(135deg, #2c3e50, #34495e);
            color: white;
            padding: 4rem 2rem;
            text-align: center;
        }

        .status-badge {
            background: var(--accent);
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
        }

        /* Sections */
        .container {
            max-width: 900px;
            margin: auto;
            padding: 2rem;
        }

        section {
            background: white;
            padding: 2rem;
            margin-bottom: 2rem;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        h2 {
            color: var(--primary);
            border-bottom: 3px solid var(--accent);
            padding-bottom: 10px;
            margin-top: 0;
        }

        /* Grille de compétences */
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .skill-tag {
            display: inline-block;
            background: #e1f5fe;
            color: #0288d1;
            padding: 5px 12px;
            border-radius: 4px;
            margin: 4px;
            font-size: 0.85rem;
            font-weight: bold;
        }

        /* Expériences */
        .exp-item {
            border-left: 3px solid #ddd;
            padding-left: 20px;
            margin-bottom: 25px;
        }

        .exp-date {
            color: var(--accent);
            font-weight: bold;
        }

        footer {
            text-align: center;
            padding: 2rem;
            color: #777;
        }

        /* Mobile responsive */
        @media (max-width: 600px) {
            header h1 { font-size: 1.8rem; }
        }
    </style>
</head>
<body>

<nav>
    <a href="#about">À propos</a>
    <a href="#formations">Parcours</a>
    <a href="#competences">Compétences</a>
    <a href="#contact">Contact</a>
</nav>

<header>
    <h1>Lorenzo PROVOT</h1>
    <p>Étudiant en BTS SIO - Option SISR</p>
    <span class="status-badge">Recherche de stage : 11 Mai - 19 Juin</span>
</header>

<div class="container">

    <section id="about">
        <h2>À Propos</h2>
        <p>Passionné par la création numérique et le développement de jeux vidéo, j'ai naturellement élargi mes compétences vers l'informatique technique et les réseaux. Je souhaite aujourd'hui approfondir mes connaissances théoriques et pratiques dans ce domaine pour enrichir mon expertise.</p>
    </section>

    <section id="formations">
        <h2>Formations</h2>
        <div class="exp-item">
            <span class="exp-date">En cours</span>
            <h3>BTS SIO SISR</h3>
            <p><strong>Lycée La Martinière Duchère</strong> | Lyon, France</p>
            <p>Spécialisation : Solutions d'infrastructure, systèmes et réseaux.</p>
        </div>
        <div class="exp-item">
            <h3>Bac Général Technologique</h3>
            <p>Mention Assez Bien</p>
        </div>
    </section>

    <section id="competences">
        <h2>Compétences Techniques</h2>
        <div class="skills-grid">
            <div>
                <h3>Logiciels & Outils</h3>
                <span class="skill-tag">Cisco Packet-Tracer</span>
                <span class="skill-tag">VMWare</span>
                <span class="skill-tag">WireShark</span>
                <span class="skill-tag">Proxmox</span>
                <span class="skill-tag">Autocad</span>
            </div>
            <div>
                <h3>Réseaux & Systèmes</h3>
                <span class="skill-tag">Routage & Admin</span>
                <span class="skill-tag">DNS / DHCP</span>
                <span class="skill-tag">VLAN</span>
                <span class="skill-tag">Architecture Réseau</span>
            </div>
        </div>
    </section>

    <section id="experiences">
        <h2>Expériences Professionnelles</h2>
        <div class="exp-item">
            <h3>Stage - France 3 Rhône Alpes</h3>
            <ul>
                <li>Réalisation d'un clip musical et documentaire.</li>
                <li>Montage vidéo et manipulation sonore en direct.</li>
            </ul>
        </div>
        <div class="exp-
