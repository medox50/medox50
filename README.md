<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="robots" content="index, follow, max-image-preview:large, max-snippet:-1, max-video-preview:-1">
    <meta name="description" content="Explore and download the best wallpapers for free. Find full version wallpapers with direct and single download links available.">
    <meta property="og:locale" content="en_US">
    <title>Wallpapers Download Full Version for FREE</title>
    <link rel="preload" as="font" href="https://www.yourwebsite.com/path/to/font.woff2" type="font/woff2" crossorigin="anonymous">
    <link rel="canonical" href="https://www.yourwebsite.com/">
    <link rel="stylesheet" href="styles.css">
    <link href="/css/site_2023.css" rel="stylesheet" media="screen">
    <style>
        body {
            background-image: url('img/14.preview.php\ wallpaer.jpg.jpg');
            background-size: cover;
            background-position: center;
            color: black;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        .dark-theme {
            background-color: black;
            color: white;
        }
        
        header {
            background-image: url('img/4666c8bc02cc83ef52c11cdef1d85f5d.jpg');
            background-size: cover;
            background-position: center;
            padding: 20px;
            text-align: center;
            position: relative;
            margin-bottom: 20px;
        }

        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }

        nav ul li {
            display: inline;
        }

        nav ul li a {
            color: inherit;
            text-decoration: none;
            font-size: 18px;
        }

        .top-bar {
            position: absolute;
            top: 10px;
            right: 10px;
        }

        .top-bar button {
            margin-left: 10px;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            background-color: #4CAF50;
            color: white;
            font-size: 16px;
        }

        .settings-menu {
            position: absolute;
            top: 60px;
            right: 10px;
        }

        .settings-btn {
            background-color: rgb(28, 40, 199);
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
        }

        .settings-options {
            background-color: white;
            padding: 10px;
            border: 1px solid black;
            border-radius: 5px;
            display: none;
            margin-top: 10px;
            color: black;
        }

        .hero-section {
            text-align: center;
            padding: 50px 0;
            color: inherit;
        }

        .wallpapers-section {
            text-align: center;
            padding: 50px 0;
        }

        .wallpapers-list {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }

        .wallpaper {
            background-color: rgba(0, 0, 0, 0.5);
            border: 2px solid #fff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            cursor: pointer;
            overflow: hidden;
            width: 200px;
            text-align: center;
            transition: transform 0.2s;
        }

        .wallpaper:hover {
            transform: scale(1.05);
        }

        .wallpaper img {
            max-width: 100%;
            height: auto;
            border-bottom: 2px solid #fff;
        }

        .wallpaper p {
            padding: 10px;
        }

        footer {
            background-color: #222;
            color: white;
            text-align: center;
            padding: 20px 0;
            position: relative;
            margin-top: 20px;
        }

        footer a {
            color: #4CAF50;
            text-decoration: none;
        }

        .search-bar {
            position: fixed;
            top: 20px;
            left: 20px;
            z-index: 1000;
        }

        .search-bar input[type="text"] {
            padding: 10px;
            border-radius: 5px;
            border: 1px solid black;
        }

        .search-bar button {
            background-color: black;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            margin-left: 5px;
        }

        /* Modal Styles */
        .modal {
            display: none;
            position: fixed;
            z-index: 1000;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            overflow: auto;
            background-color: rgba(0, 0, 0, 0.8);
            padding-top: 60px;
            align-items: center;
            justify-content: center;
        }

        .modal-content {
            background-color: #fefefe;
            margin: auto;
            padding: 20px;
            border: 1px solid #888;
            width: 80%;
            max-width: 800px;
            border-radius: 10px;
            text-align: center;
        }

        .close {
            color: #aaa;
            float: right;
            font-size: 28px;
            font-weight: bold;
        }

        .close:hover,
        .close:focus {
            color: black;
            text-decoration: none;
            cursor: pointer;
        }

        .modal-body img {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>

<header>
    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="photos.html">Wallpapers</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="contact.html">Contact</a></li>
            <li><a href="series of the best photo.html">Series</a></li>
        </ul>
    </nav>
    <div class="top-bar">
        <button class="signin-btn" onclick="location.href='signin.html'">Sign In</button>
        <button class="signup-btn" onclick="location.href='signup.html'">Sign Up</button>
    </div>
    <div class="settings-menu">
        <button class="settings-btn" onclick="toggleSettings()">Settings</button>
        <div class="settings-options" id="settingsOptions">
            <label for="theme">Theme:</label>
            <select id="theme" onchange="changeTheme()">
                <option value="Light">Light</option>
                <option value="dark">Dark</option>
            </select>
        </div>
    </div>
</header>

<div class="search-bar">
    <input type="text" placeholder="Search wallpapers...">
    <button>Search</button>
</div>

<div class="hero-section">
    <h1>Welcome to Our Wallpaper Download Site!</h1>
    <p>Discover and download high-quality wallpapers for free.</p>
</div>

<div class="wallpapers-section">
    <div class="wallpapers-list">
        <!-- Example wallpaper entries -->
        <div class="wallpaper">
            <h4>the batman </h4>
            <img src="img/1130536.jpg " alt="the batman">
            <p></p>
        </div>
        <div class="wallpaper">
            <h4>Black Windows 7</h4>
            <img src="img/Black Windows 7 wallpaper PSDgraphics.jpeg" alt="Wallpaper 2">
            <p></p>
        </div>
        <div class="wallpaper">
            <h4>zoom</h4>
            <img src="img/zoom wallpaper.jpg.webp" alt="Wallpaper 2">
            <p></p>
        </div>
        <div class="wallpaper">
            <h4>scarlet witch</h4>
            <img src="img/13370.jpg" alt="Wallpaper 2">
            <p></p>
        </div>
        <div class="wallpaper">
            <h4>spiderman  wellpaper</h4>
            <img src="img/1064992.jpg" alt="Wallpaper 2">
            <p></p>
        </div>
        <div class="wallpaper">
            <h4>the infinity stones</h4>
            <img src="img/127.jpg" alt="Wallpaper 2">
            <p></p>
        </div>
        <div class="wallpaper">
            <h4>vigion</h4>
            <img src="img/1146408.jpg" alt="Wallpaper 2">
            <p></p>
        </div>
        <div class="wallpaper">
            <h4>windows </h4>
            <img src="img/16795.png" alt="Wallpaper 2">
            <p></p>
        </div>
        <div class="wallpaper">
            <h4>Ichigo Kurosaki, </h4>
            <img src="img/16756.jpg" alt="Wallpaper 2">
            <p></p>
        </div>
        <div class="wallpaper">
            <h4>dc universe </h4>
            <img src="img/14.preview.php wallpaer.jpg.jpg" alt="Wallpaper 2">
            <p></p>
        </div>
        <div class="wallpaper">
            <h4>wolverine </h4>
            <img src="img/211575_download-4k-gaming-wallpapers-desktop-backgrounds_3840x2160_h.jpg" alt="Wallpaper 2">
            <p></p>
        </div>
    </div>
</div>

<!-- Modal Structure -->
<div id="wallpaperModal" class="modal">
    <div class="modal-content">
        <span class="close" onclick="closeModal()">&times;</span>
        <div class="modal-body">
            <img id="modalImage" src="" alt="Wallpaper Image">
        </div>
    </div>
</div>

<footer>
    <p>&copy; 2023 Wallpapers Download. All rights reserved. | <a href="privacy.html">Privacy Policy</a> | <a href="terms.html">Terms of Service</a></p>
</footer>

<script>
    document.addEventListener('DOMContentLoaded', function() {
        const modal = document.getElementById('wallpaperModal');
        const modalImg = document.getElementById('modalImage');
        const overlay = document.querySelector('.overlay');

        // Function to open modal with enlarged image
        function openModal(imgSrc) {
            modalImg.src = imgSrc;
            modal.style.display = 'flex';
        }

        // Close modal when overlay or close button is clicked
        function closeModal() {
            modal.style.display = 'none';
        }

        // Settings menu functionality
        const settingsBtn = document.querySelector('.settings-btn');
        const settingsOptions = document.querySelector('.settings-options');

        settingsBtn.addEventListener('click', function() {
            settingsOptions.style.display = settingsOptions.style.display === 'block' ? 'none' : 'block';
        });

        // Change theme functionality
        const themeSelect = document.getElementById('theme');

        themeSelect.addEventListener('change', function() {
            const theme = themeSelect.value;
            if (theme === 'dark') {
                document.body.classList.add('dark-theme');
            } else {
                document.body.classList.remove('dark-theme');
            }
        });

        // Add event listeners to all wallpaper images
        const wallpapers = document.querySelectorAll('.wallpaper img');
        wallpapers.forEach(function(wallpaper) {
            wallpaper.addEventListener('click', function() {
                openModal(wallpaper.src);
            });
        });

        // Search functionality
        const searchInput = document.querySelector('.search-bar input[type="text"]');

        searchInput.addEventListener('input', function() {
            const searchText = searchInput.value.trim().toLowerCase();
            const wallpapers = document.querySelectorAll('.wallpaper');
            wallpapers.forEach(function(wallpaper) {
                const wallpaperTitle = wallpaper.querySelector('h4').textContent.trim().toLowerCase();
                const displayStyle = wallpaperTitle.includes(searchText) ? 'block' : 'none';
                wallpaper.style.display = displayStyle;
            });
        });
    });

    function closeModal() {
        const modal = document.getElementById('wallpaperModal');
        modal.style.display = 'none';
    }
</script>

</body>
</html>
