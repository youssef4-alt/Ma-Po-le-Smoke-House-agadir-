# Ma-Po-le-Smoke-House-agadir-
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ma Poêle Smoke House - Agadir</title>
    <style>
        :root {
            --bg-color: #1a1d20;
            --card-bg: #24282c;
            --accent-color: #ff9f43;
            --text-main: #ffffff;
            --text-muted: #a0a5a9;
            --border-color: #383d42;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-main);
            line-height: 1.6;
        }

        header {
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://images.unsplash.com/photo-1555396273-367ea4eb4db5?auto=format&fit=crop&w=1200&q=80') no-repeat center center/cover;
            padding: 100px 20px;
            text-align: center;
            border-bottom: 3px solid var(--accent-color);
        }

        .logo-area h1 {
            font-size: 3.5rem;
            color: var(--text-main);
            margin-bottom: 10px;
            font-weight: 800;
            letter-spacing: 1px;
        }

        .logo-area h1 span {
            color: var(--accent-color);
        }

        .tagline {
            font-size: 1.2rem;
            color: var(--text-muted);
            margin-bottom: 30px;
        }

        .cta-buttons {
            display: flex;
            justify-center: center;
            gap: 15px;
            flex-wrap: wrap;
            justify-content: center;
        }

        .btn {
            display: inline-block;
            padding: 12px 28px;
            text-decoration: none;
            border-radius: 30px;
            font-weight: 600;
            transition: all 0.3s ease;
        }

        .btn-primary {
            background-color: var(--accent-color);
            color: #000;
        }

        .btn-primary:hover {
            background-color: #ff8c1a;
            transform: translateY(-2px);
        }

        .btn-secondary {
            border: 2px solid var(--text-main);
            color: var(--text-main);
        }

        .btn-secondary:hover {
            background-color: var(--text-main);
            color: #000;
            transform: translateY(-2px);
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 40px 20px;
        }

        /* Info Section */
        .info-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-bottom: 60px;
        }

        .info-card {
            background-color: var(--card-bg);
            border: 1px solid var(--border-color);
            padding: 25px;
            border-radius: 12px;
            text-align: center;
        }

        .info-card h3 {
            color: var(--accent-color);
            margin-bottom: 10px;
            font-size: 1.3rem;
        }

        .info-card p {
            color: var(--text-muted);
            font-size: 0.95rem;
        }

        /* Menu Section */
        .section-title {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 40px;
            position: relative;
        }

        .section-title::after {
            content: '';
            display: block;
            width: 60px;
            height: 3px;
            background-color: var(--accent-color);
            margin: 10px auto 0;
        }

        .menu-category-title {
            color: var(--accent-color);
            font-size: 1.8rem;
            margin: 40px 0 20px;
            border-left: 4px solid var(--accent-color);
            padding-left: 15px;
        }

        .menu-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(340px, 1fr));
            gap: 25px;
        }

        .menu-item {
            background-color: var(--card-bg);
            border: 1px solid var(--border-color);
            padding: 20px;
            border-radius: 8px;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            transition: transform 0.2s;
        }

        .menu-item:hover {
            transform: scale(1.02);
        }

        .item-header {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            margin-bottom: 8px;
        }

        .item-title {
            font-size: 1.15rem;
            font-weight: 600;
            padding-right: 10px;
        }

        .item-price {
            color: var(--accent-color);
            font-weight: 700;
            white-space: nowrap;
            font-size: 1.15rem;
        }

        .item-desc {
            color: var(--text-muted);
            font-size: 0.9rem;
            font-style: italic;
        }

        footer {
            background-color: #111315;
            text-align: center;
            padding: 40px 20px;
            margin-top: 60px;
            border-top: 1px solid var(--border-color);
            color: var(--text-muted);
            font-size: 0.9rem;
        }

        footer a {
            color: var(--accent-color);
            text-decoration: none;
        }

        @media (max-width: 768px) {
            .logo-area h1 { font-size: 2.5rem; }
            .menu-grid { grid-template-columns: 1fr; }
        }
    </style>
</head>
<body>

    <header>
        <div class="logo-area">
            <h1>Ma Poêle <span>Smoke House</span></h1>
            <p class="tagline">Toutes nos grillades au feu de bois & pizzas artisanales à Agadir</p>
            <div class="cta-buttons">
                <a href="https://glovoapp.com" target="_blank" class="btn btn-primary">Commander sur Glovo</a>
                <a href="tel:0679523257" class="btn btn-secondary">Appeler: 06 79 52 32 57</a>
            </div>
        </div>
    </header>

    <div class="container">
        <!-- Info Cards -->
        <div class="info-grid">
            <div class="info-card">
                <h3>📍 Adresse</h3>
                <p>Local 18 im f, Rue L'hôtel de ville<br>Agadir 80000</p>
            </div>
            <div class="info-card">
                <h3>🕒 Horaires</h3>
                <p>Ouvert tous les jours<br>Jusqu'à 01:00 du matin</p>
            </div>
            <div class="info-card">
                <h3>📱 Réseaux Sociaux</h3>
                <p>Instagram & TikTok<br>@mapoele.agadir</p>
            </div>
        </div>

        <h2 class="section-title">Notre Carte</h2>

        <!-- Les Grillades -->
        <h3 class="menu-category-title">Les Grillades (Au feu de bois)</h3>
        <p style="color: var(--text-muted); margin-bottom: 20px; font-style: italic;">Servis avec Riz basmati, frites, salade ou purée de pommes de terre</p>
        <div class="menu-grid">
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Surprême De Poulet Braisé</span><span class="item-price">60 Dhs</span></div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Broquettes Poulet</span><span class="item-price">70 Dhs</span></div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Brochettes Kefta</span><span class="item-price">80 Dhs</span></div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Brochettes Mixtes</span><span class="item-price">80 Dhs</span></div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Poulpe Braisé</span><span class="item-price">100 Dhs</span></div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Terre et Mer / Land And Sea</span><span class="item-price">120 Dhs</span></div>
                <div class="item-desc">Brochettes Poulet, Kefta, Poulpe</div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Émincé De Poulet Aux Champignons</span><span class="item-price">65 Dhs</span></div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Émincé De Poulet Aux Crevettes</span><span class="item-price">70 Dhs</span></div>
            </div>
        </div>

        <!-- Charcoal Burgers -->
        <h3 class="menu-category-title">Charcoal Burgers</h3>
        <p style="color: var(--text-muted); margin-bottom: 20px; font-style: italic;">Servis avec frites</p>
        <div class="menu-grid">
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Cheese Burger</span><span class="item-price">35 Dhs</span></div>
                <div class="item-desc">Steak haché, laitue, tomate, oignons, cornichons, fromage cheddar, sauce burger.</div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Chicken Burger</span><span class="item-price">35 Dhs</span></div>
                <div class="item-desc">Poulet croustillant, laitue, tomate, oignons, cornichons, fromage cheddar, sauce burger.</div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Américain Burger</span><span class="item-price">50 Dhs</span></div>
                <div class="item-desc">Steak haché, oignons rings, jambon, laitue, tomate, oignons, cornichons, fromage cheddar, sauce burger.</div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Ma Poêle Burger</span><span class="item-price">60 Dhs</span></div>
                <div class="item-desc">Steak haché, poulet croustillant, jambon fumé, oignons rings, laitue, tomate, oignons, cornichons, fromage cheddar, sauce burger.</div>
            </div>
        </div>

        <!-- Pizzas -->
        <h3 class="menu-category-title">Pizzas (Au feu de bois)</h3>
        <div class="menu-grid">
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Pizza Margherita</span><span class="item-price">40 Dhs</span></div>
                <div class="item-desc">Sauce tomate, mozzarella, olive noire.</div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Pizza Tonnara</span><span class="item-price">55 Dhs</span></div>
                <div class="item-desc">Sauce tomate, mozzarella, thon, olive noire.</div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Pizza 4 Saisons</span><span class="item-price">80 Dhs</span></div>
                <div class="item-desc">Sauce tomate, mozzarella, fruit de mer, thon, viande hachée, poulet.</div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Pizza 4 Fromages</span><span class="item-price">70 Dhs</span></div>
                <div class="item-desc">Sauce tomate, mozzarella, edam, parmesan, roquefort.</div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Pizza Charcuterie</span><span class="item-price">65 Dhs</span></div>
                <div class="item-desc">Sauce tomate, mozzarella, charcuterie.</div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Pizza Végétarienne</span><span class="item-price">50 Dhs</span></div>
                <div class="item-desc">Sauce tomate, mozzarella, légumes grillés.</div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Pizza Viande Hachée</span><span class="item-price">60 Dhs</span></div>
                <div class="item-desc">Sauce tomate, mozzarella, viande hachée, champignons, origan.</div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Pizza Poulet</span><span class="item-price">55 Dhs</span></div>
                <div class="item-desc">Sauce tomate, mozzarella, poulet, champignons, tomate fraîche.</div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Pizza Dinde Fumée</span><span class="item-price">55 Dhs</span></div>
                <div class="item-desc">Sauce tomate, mozzarella, champignons, jambon de dinde, olives.</div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Pizza Fruits de Mer</span><span class="item-price">70 Dhs</span></div>
                <div class="item-desc">Sauce tomate, mozzarella, persil, calamars, crevettes.</div>
            </div>
        </div>

        <!-- Calzones -->
        <h3 class="menu-category-title">Calzones (Au feu de bois)</h3>
        <div class="menu-grid">
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Calzone Jambon</span><span class="item-price">55 Dhs</span></div>
                <div class="item-desc">Sauce tomate, jambon de dinde, mozzarella, edam.</div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Calzone Fruits de Mer</span><span class="item-price">70 Dhs</span></div>
                <div class="item-desc">Sauce tomate, mozzarella, persil, calamars, crevettes.</div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Calzone Végétarien</span><span class="item-price">50 Dhs</span></div>
                <div class="item-desc">Sauce tomate, mozzarella, légumes grillés.</div>
            </div>
        </div>

        <!-- Pasta -->
        <h3 class="menu-category-title">Pasta (Spaghetti, Tagliatelle, Penne)</h3>
        <div class="menu-grid">
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Bolognaise</span><span class="item-price">45 Dhs</span></div>
                <div class="item-desc">Sauce tomate, viande hachée, fromage, basilic.</div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Forestier</span><span class="item-price">45 Dhs</span></div>
                <div class="item-desc">Sauce blanche, champignons, poulet, fromage.</div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Carbonara</span><span class="item-price">45 Dhs</span></div>
                <div class="item-desc">Sauce blanche, jambon fumé, champignons.</div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Pêcheur</span><span class="item-price">60 Dhs</span></div>
                <div class="item-desc">Sauce blanche, fruits de mer, champignons.</div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Végétarienne</span><span class="item-price">45 Dhs</span></div>
                <div class="item-desc">Sauce tomate, légumes grillés, fromage.</div>
            </div>
        </div>

        <!-- Les Salades -->
        <h3 class="menu-category-title">Les Salades</h3>
        <div class="menu-grid">
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Guacamole D'Avocat Aux Crevettes</span><span class="item-price">50 Dhs</span></div>
                <div class="item-desc">Avocat, crevettes.</div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Salade Smoked Chicken</span><span class="item-price">45 Dhs</span></div>
                <div class="item-desc">Laitue, tomate cerise, concombre, betterave, courgette grillée, champignons, riz, poulet grillé.</div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Salade Italienne</span><span class="item-price">40 Dhs</span></div>
                <div class="item-desc">Laitue, tomate cerise, concombre, betterave, courgette grillée, champignons, riz, thon.</div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Salade Sea Food</span><span class="item-price">65 Dhs</span></div>
                <div class="item-desc">Laitue, tomate cerise, concombre, betterave, courgette grillée, champignons, riz, crevettes, sépia, poulpe.</div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Salade Poulpe Fumé</span><span class="item-price">70 Dhs</span></div>
                <div class="item-desc">Laitue, tomate cerise, concombre, betterave, courgette grillée, champignons, riz, poulpe fumé.</div>
            </div>
        </div>

        <!-- Jus & Détox -->
        <h3 class="menu-category-title">Jus & Détox</h3>
        <div class="menu-grid">
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Green Détox</span><span class="item-price">25 Dhs</span></div>
                <div class="item-desc">Épinard, gingembre, orange, pomme.</div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Fraîche Détox</span><span class="item-price">25 Dhs</span></div>
                <div class="item-desc">Betterave, gingembre, orange, pomme.</div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Orange / Carottes</span><span class="item-price">20 Dhs</span></div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Jus De Citron / Thé Marocain / Café</span><span class="item-price">20 Dhs</span></div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Panaché</span><span class="item-price">30 Dhs</span></div>
            </div>
        </div>

        <!-- Suppléments -->
        <h3 class="menu-category-title">Suppléments</h3>
        <div class="menu-grid">
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Frites</span><span class="item-price">12 Dhs</span></div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Potatoes</span><span class="item-price">20 Dhs</span></div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Riz Basmati</span><span class="item-price">25 Dhs</span></div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Purée (de pommes de terre)</span><span class="item-price">20 Dhs</span></div>
            </div>
            <div class="menu-item">
                <div class="item-header"><span class="item-title">Pasta</span><span class="item-price">15 Dhs</span></div>
            </div>
        </div>

    </div>

    <footer>
        <p>&copy; 2026 Ma Poêle Smoke House. Tous droits réservés.</p>
        <p>Local 18 im f, Rue L'hôtel de ville, Agadir 80000 | Contact: <a href="tel:0679523257">06 79 52 32 57</a></p>
    </footer>

</body>
</html>
