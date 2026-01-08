# Muslim-overgarments
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- =========================
         META DATA
         ========================= -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Educational website about Muslim overgarments, their types, materials, and care.">
    <title>Muslim Overgarments</title>

    <!-- =========================
         INTERNAL CSS
         ========================= -->
    <style>
        /* ===== GLOBAL STYLES ===== */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            line-height: 1.6;
            background-color: #f5f5f5;
            color: #333;
        }

        h1, h2, h3 {
            color: #2f4f4f;
        }

        /* ===== HEADER & NAV (Flexbox) ===== */
        header {
            background-color: #2f4f4f;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            padding: 0;
            margin: 10px 0 0 0;
        }

        nav li {
            margin: 0 15px;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        /* ===== MAIN LAYOUT (CSS GRID) ===== */
        main {
            display: grid;
            grid-template-columns: 1fr;
            gap: 20px;
            padding: 20px;
        }

        section {
            background: white;
            padding: 20px;
            border-radius: 6px;
        }

        /* ===== IMAGES ===== */
        img {
            max-width: 100%;
            height: auto;
            border-radius: 6px;
        }

        /* ===== TABLE ===== */
        table {
            width: 100%;
            border-collapse: collapse;
        }

        th, td {
            border: 1px solid #999;
            padding: 10px;
            text-align: left;
        }

        th {
            background-color: #ddd;
        }

        /* ===== FOOTER ===== */
        footer {
            background-color: #2f4f4f;
            color: white;
            text-align: center;
            padding: 15px;
        }

        /* ===== RESPONSIVE DESIGN ===== */
        @media (min-width: 768px) {
            main {
                grid-template-columns: repeat(2, 1fr);
            }
        }
    </style>
</head>

<body>

<!-- =========================
     HEADER
     ========================= -->
<header>
    <h1>Muslim Overgarments</h1>
    <p>Modesty • Culture • Identity</p>

    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#types">Types</a></li>
            <li><a href="#materials">Materials</a></li>
            <li><a href="#care">Care</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>

<!-- =========================
     MAIN CONTENT
     ========================= -->
<main>

    <!-- ===== HOME ===== -->
    <section id="home">
        <h2>Welcome</h2>
        <p>
            Muslim overgarments are worn by men and women around the world as an expression
            of faith, modesty, culture, and personal identity. This website explores the
            different types of Muslim overgarments, the materials used, and how to properly
            care for them.
        </p>
        <img src="https://via.placeholder.com/600x300" alt="Examples of Muslim overgarments">
    </section>

    <!-- ===== ABOUT ===== -->
    <section id="about">
        <h2>About Muslim Overgarments</h2>
        <p>
            In Islam, modesty is an important value. Clothing choices are influenced by
            religious teachings, cultural traditions, climate, and personal style.
            Overgarments are designed to provide coverage while allowing comfort and dignity.
        </p>
        <p>
            Styles and names vary across regions, but the purpose remains the same:
            to promote modesty and respect.
        </p>
    </section>

    <!-- ===== TYPES (NESTED LISTS) ===== -->
    <section id="types">
        <h2>Types of Muslim Overgarments</h2>
        <ul>
            <li>Women's Overgarments
                <ul>
                    <li>Abaya – A loose outer robe</li>
                    <li>Hijab – A head covering</li>
                    <li>Jilbab – A long coat-like garment</li>
                    <li>Niqab – A face covering</li>
                </ul>
            </li>
            <li>Men's Overgarments
                <ul>
                    <li>Thobe – A long robe worn daily</li>
                    <li>Bisht – A formal outer cloak</li>
                </ul>
            </li>
        </ul>
    </section>

    <!-- ===== MATERIALS (TABLE) ===== -->
    <section id="materials">
        <h2>Materials & Fabrics</h2>
        <table>
            <tr>
                <th>Material</th>
                <th>Common Use</th>
                <th>Season</th>
            </tr>
            <tr>
                <td>Cotton</td>
                <td>Everyday wear</td>
                <td>All seasons</td>
            </tr>
            <tr>
                <td>Chiffon</td>
                <td>Formal occasions</td>
                <td>Spring / Summer</td>
            </tr>
            <tr>
                <td>Wool</td>
                <td>Outer garments</td>
                <td>Winter</td>
            </tr>
        </table>
    </section>

    <!-- ===== CARE ===== -->
    <section id="care">
        <h2>Care & Maintenance</h2>
        <ol>
            <li>Read garment care labels carefully</li>
            <li>Hand wash delicate fabrics</li>
            <li>Use mild detergents</li>
            <li>Avoid excessive heat when ironing</li>
            <li>Store garments in a clean, dry place</li>
        </ol>
    </section>

    <!-- ===== CONTACT ===== -->
    <section id="contact">
        <h2>Contact & Resources</h2>
        <p>
            This educational project was created to promote understanding of Muslim clothing
            traditions. For further learning, visit trusted cultural and educational resources
            related to Islamic fashion and modest wear.
        </p>
    </section>

</main>

<!-- =========================
     FOOTER
     ========================= -->
<footer>
    <p>&copy; 2026 Muslim Overgarments Website | Educational Project</p>
</footer>

</body>
</html>