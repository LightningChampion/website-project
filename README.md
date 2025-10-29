# website-project


<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>My Personal Homepage</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <main class="container">
    <aside class="profile">
      <img src="images/profile.jpg" alt="A photo of me" />
    </aside>
    <section class="content">
      <h1>Network security</h1>
      <h2>About Us</h2>
      <p>Hello welcome to our Network security blog. In this blog we will give important informations about network security  <a target="_blank" rel="noopener"></a>.</p>
      <p>Network security is essential for your network. Read our articles and learn everything about network security.</p>

      <h2>Articles</h2>
      <table class="classes">
        <thead>
          <tr><th>Article name</th><th>Article link page</th></tr>
        </thead>
        <tbody>
          <tr><td><a href="#">Why network security is important?</a></td><td>Article link</td></tr>
          <tr><td><a href="#">Strong Password</a></td><td>Article link</td></tr>
          <tr><td><a href="#">Email security</a></td><td>Article link</td></tr>
        </tbody>
      </table>

      <h2>Tools</h2>
      <div id="video-container"></div>
      <ul class="extras">
        <li>Strong password generator</li>
        <li>Network security Quiz</li>
        <li>Cyber security guide</li>
      </ul>
    </section>
  </main>

  <script>
    // Video elementini oluştur
    const videoContainer = document.getElementById('video-container');

    const video = document.createElement('video');
    video.src = 'videos/tools.mp4'; // Video dosya yolu
    video.width = 320;
    video.height = 180;
    video.controls = true;

    videoContainer.appendChild(video);
  </script>
</body>
</html>


