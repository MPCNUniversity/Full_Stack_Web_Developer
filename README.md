# Full_Stack_Web_Developer

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>University Curriculum</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            color: #333;
        }
        header {
            background-color: #2c3e50;
            color: white;
            padding: 20px;
            text-align: center;
            border-radius: 5px 5px 0 0;
        }
        nav {
            background-color: #34495e;
            padding: 10px;
            border-radius: 0 0 5px 5px;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
        }
        nav li {
            margin: 0 15px;
        }
        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        .course-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        .course-card {
            border: 1px solid #ddd;
            padding: 20px;
            border-radius: 5px;
            transition: transform 0.3s ease;
        }
        .course-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        footer {
            text-align: center;
            margin-top: 40px;
            padding: 20px;
            background-color: #2c3e50;
            color: white;
            border-radius: 0 0 5px 5px;
        }
    </style>
</head>
<body>
    <header>
        <h1>University of [Your University] Curriculum</h1>
        <p>A comprehensive overview of our academic programs</p>
    </header>

    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#arts">Arts & Humanities</a></li>
            <li><a href="#sciences">Sciences</a></li>
            <li><a href="#engineering">Engineering</a></li>
            <li><a href="#business">Business</a></li>
        </ul>
    </nav>

    <main>
        <section id="home">
            <h2>Welcome to Our Curriculum</h2>
            <p>This is the central hub for all academic programs offered at our university. Browse through departments and individual courses below.</p>
        </section>

        <h2>Our Departments</h2>
        <div class="course-grid">
            <!-- Department Cards - You can duplicate this structure for each department -->
            <article class="course-card" id="arts">
                <h3>Arts & Humanities</h3>
                <p>The study of human culture and creativity through literature, philosophy, fine arts, and more.</p>
                <a href="arts.html">View Arts Courses →</a>
            </article>

            <article class="course-card" id="sciences">
                <h3>Natural Sciences</h3>
                <p>Exploring the fundamental principles of biology, chemistry, physics, and mathematics.</p>
                <a href="sciences.html">View Sciences Courses →</a>
            </article>

            <article class="course-card" id="engineering">
                <h3>Engineering & Technology</h3>
                <p>Applying scientific principles to design solutions for real-world problems.</p>
                <a href="engineering.html">View Engineering Courses →</a>
            </article>

            <article class="course-card" id="business">
                <h3>Business Administration</h3>
                <p>Developing the skills needed to manage and lead organizations effectively.</p>
                <a href="business.html">View Business Courses →</a>
            </article>
        </div>
    </main>

    <footer>
        <p>&copy; 2023 University Curriculum. All rights reserved.</p>
        <p>Note: Course content will be filled in at a later date.</p>
    </footer>
</body>
</html>
