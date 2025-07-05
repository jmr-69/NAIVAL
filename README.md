my-blog/
├── index.html
├── blog.html
├── style.css

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Blog - Home</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>My Blog</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="blog.html">Blog</a>
    </nav>
  </header>

  <main>
    <section>
      <h2>Welcome!</h2>
      <p>This is my personal blog where I share thoughts, tutorials, and ideas.</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 My Blog</p>
  </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Blog - Posts</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>My Blog</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="blog.html">Blog</a>
    </nav>
  </header>

  <main>
    <section>
      <h2>Latest Posts</h2>
      <article>
        <h3>First Blog Post</h3>
        <p><em>July 5, 2025</em></p>
        <p>This is a placeholder post. You can add your own text here!</p>
      </article>

      <article>
        <h3>Another Post</h3>
        <p><em>July 1, 2025</em></p>
        <p>More content goes here. You can write about anything you like.</p>
      </article>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 My Blog</p>
  </footer>
</body>
</html>

body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background: #f9f9f9;
  color: #333;
}

header {
  background: #333;
  color: #fff;
  padding: 1rem;
}

header h1 {
  margin: 0;
}

nav a {
  color: #fff;
  margin: 0 1rem;
  text-decoration: none;
}

main {
  padding: 2rem;
}

footer {
  background: #eee;
  text-align: center;
  padding: 1rem;
  position: fixed;
  bottom: 0;
  width: 100%;
}

article {
  margin-bottom: 2rem;
  padding: 1rem;
  background: #fff;
  border-left: 4px solid #007BFF;
}
