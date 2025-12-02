# fictional-tribble

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zero Anime - Your Anime Hub</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #000; color: #fff; }
        header { background: linear-gradient(to right, #ff6b6b, #4ecdc4); padding: 20px; text-align: center; }
        header h1 { margin: 0; font-size: 2.5em; }
        nav { margin: 10px 0; }
        nav a { color: #fff; margin: 0 15px; text-decoration: none; font-weight: bold; }.container { max-width: 1200px; margin: 20px auto; padding: 0 20px; }.anime-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; }.anime-card { background: #222; border-radius: 10px; overflow: hidden; transition: transform 0.3s; }.anime-card:hover { transform: scale(1.05); }.anime-card img { width: 100%; height: 250px; object-fit: cover; }.anime-card h3 { padding: 10px; margin: 0; }
        footer { background: #333; text-align: center; padding: 10px; margin-top: 40px; }.credit { background: #333; text-align: center; padding: 5px; margin-top: 10px; color: #4CAF50; font-size: 0.9em; }
    </style>
</head>
<body>
    <header>
        <h1>Zero Anime</h1>
        <p>Welcome to the ultimate anime streaming & community site!</p>
        <nav>
            <a href="#home">Home</a>
            <a href="#anime">Anime</a>
            <a href="#watch">Watch</a>
            <a href="#about">About</a>
        </nav>
    </header>

    <div class="container">
        <section id="anime">
            <h2>Featured Anime</h2>
            <div class="anime-grid">
                <div class="anime-card">
                    <img src="https://via.placeholder.com/200x250/ff6b6b/fff?text=Attack+on+Titan" alt="Attack on Titan">
                    <h3>Attack on Titan</h3>
                </div>
                <div class="anime-card">
                    <img src="https://via.placeholder.com/200x250/4ecdc4/000?text=One+Piece" alt="One Piece">
                    <h3>One Piece</h3>
                </div>
                <div class="anime-card">
                    <img src="https://via.placeholder.com/200x250/45b7d1/fff?text=Demon+Slayer" alt="Demon Slayer">
                    <h3>Demon Slayer</h3>
                </div>
                <div class="anime-card">
                    <img src="https://via.placeholder.com/200x250/96ceb4/000?text=Naruto" alt="Naruto">
                    <h3>Naruto</h3>
                </div>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2025 Zero Anime LK. All rights reserved. | Contact: info@zeroanime.lk</p>
        <div class="credit">Made by Agent 226</div>
    </footer>

    <script>
        // Simple JS for smooth scrolling
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({ behavior: 'smooth' });
            });
        });
    </script>
</body>
</html>
