/* General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
    color: #333;
}

header {
    background: #4CAF50;
    color: white;
    padding: 10px 20px;
    text-align: center;
}

header nav ul {
    list-style: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 10px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
}

/* Section Styles */
section {
    padding: 20px;
    margin: 20px auto;
    max-width: 1200px;
}

.wallpapers-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 10px;
}

.wallpaper {
    position: relative;
    overflow: hidden;
    border-radius: 8px;
}

.wallpaper img {
    width: 100%;
    height: auto;
    display: block;
}

.wallpaper a {
    position: absolute;
    bottom: 10px;
    right: 10px;
    background: rgba(0, 0, 0, 0.6);
    color: white;
    padding: 5px 10px;
    text-decoration: none;
    border-radius: 5px;
}

.categories button {
    margin: 5px;
    padding: 10px 20px;
    border: none;
    background-color: #4CAF50;
    color: white;
    border-radius: 5px;
    cursor: pointer;
}

.categories button:hover {
    background-color: #45a049;
}

/* Footer Styles */
footer {
    text-align: center;
    background: #4CAF50;
    color: white;
    padding: 10px 20px;
