<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Homework Sharing Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
  
<body>
    <header>
        <h1>Homework Sharing Portal</h1>
        <p>Welcome to the homework sharing platform! Upload and share your homework photos here.</p>
    </header>

    <section class="upload-section">
        <h2>Upload Your Homework</h2>
        <form action="/upload" method="POST" enctype="multipart/form-data">
            <input type="file" name="homeworkPhoto" accept="image/*" required>
            <button type="submit">Upload</button>
        </form>
    </section>

    <section class="gallery-section">
        <h2>Homework Gallery</h2>
        <div class="gallery">
            <!-- Homework images will be displayed here -->
        </div>
    </section>

    <footer>
        <p>Created by Mrsg's friends</p>
    </footer>
</body>
</html>

