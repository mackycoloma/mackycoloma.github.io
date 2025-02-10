<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>{{ site.title }}</title>
    <meta name="description" content="{{ site.description }}">
    <link rel="stylesheet" href="{{ '/assets/css/style.css' | relative_url }}">
</head>
<body>
    <header>
        <h1>{{ site.title }}</h1>
        <p>{{ site.description }}</p>
    </header>

    <nav>
        <ul>
            <li><a href="{{ '/' | relative_url }}">Home</a></li>
            <li><a href="{{ '/projects/' | relative_url }}">Projects</a></li>
            <li><a href="{{ '/about/' | relative_url }}">About</a></li>
        </ul>
    </nav>

    <main>
        <h2>Welcome!</h2>
        <p>This is my portfolio site powered by Jekyll and GitHub Pages.</p>
    </main>

    <footer>
        <p>&copy; {{ site.time | date: '%Y' }} {{ site.author.name }}</p>
    </footer>
</body>
</html>
