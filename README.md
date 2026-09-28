# -design-portfolio
A portfolio showcasing my graphic design work, including custom flyers, promotional designs, and branding projects created for clients.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Built Weblabb | Graphic Design Portfolio</title>

  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background: #0b0b0b;
      color: #ffffff;
    }

    header {
      text-align: center;
      padding: 70px 20px 50px;
      background: #111111;
    }

    header h1 {
      margin: 0;
      font-size: 42px;
      letter-spacing: 2px;
    }

    header p {
      color: #aaaaaa;
      font-size: 17px;
      margin-top: 12px;
    }

    .button {
      display: inline-block;
      margin-top: 20px;
      padding: 14px 25px;
      background: #25D366;
      color: white;
      text-decoration: none;
      border-radius: 30px;
      font-weight: bold;
    }

    .section-title {
      text-align: center;
      padding: 45px 20px 20px;
    }

    .section-title h2 {
      font-size: 30px;
      margin-bottom: 10px;
    }

    .section-title p {
      color: #999999;
    }

    .portfolio {
      max-width: 1100px;
      margin: auto;
      padding: 25px;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 25px;
    }

    .project {
      background: #171717;
      border-radius: 15px;
      overflow: hidden;
      border: 1px solid #292929;
    }

    .project img {
      width: 100%;
      display: block;
    }

    .project-info {
      padding: 15px;
      text-align: center;
    }

    .project-info h3 {
      margin: 0;
      font-size: 18px;
    }

    .project-info p {
      color: #999999;
      margin-bottom: 0;
    }

    .contact {
      text-align: center;
      padding: 70px 20px;
      background: #111111;
      margin-top: 40px;
    }

    .contact h2 {
      font-size: 30px;
    }

    .contact p {
      color: #aaaaaa;
    }

    footer {
      text-align: center;
      padding: 25px;
      color: #666666;
      font-size: 14px;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 32px;
      }

      .portfolio {
        padding: 15px;
      }
    }
  </style>
</head>

<body>

  <header>
    <h1>BUILT WEBLABB</h1>

    <p>
      Graphic Design • Branding • Creative Designs
    </p>

    <p>
      Turning ideas into visuals.
    </p>

    <a
      class="button"
      href="https://wa.me/233503833630"
      target="_blank">
      💬 Chat With Me on WhatsApp
    </a>
  </header>


  <section class="section-title">
    <h2>My Work</h2>
    <p>Some of my recent graphic design projects.</p>
  </section>


  <section class="portfolio">

    <div class="project">
      <img src="IMG_2920.jpeg" alt="Graphic Design Flyer">

      <div class="project-info">
        <h3>Custom Flyer Design</h3>
        <p>Graphic Design</p>
      </div>
    </div>

  </section>


  <section class="contact">

    <h2>Need a Design?</h2>

    <p>
      Looking for a flyer, advertisement, menu or promotional design?
    </p>

    <a
      class="button"
      href="https://wa.me/233503833630"
      target="_blank">
      Contact Me
    </a>

  </section>


  <footer>
    © 2026 Built Weblabb. All Rights Reserved.
  </footer>

</body>
</html>
