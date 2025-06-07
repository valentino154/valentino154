<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Carta para Papá</title>
  <style>
    body {
      font-family: 'silva', serif;
      background-color: #fef9f4;
      margin: 0;
      padding: 0;
    }

    .carta {
      max-width: 700px;
      background: white;
      margin: 50px auto;
      padding: 40px;
      border-radius: 15px;
      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
      animation: aparecer 1.5s ease;
    }

    @keyframes aparecer {
      from {
        opacity: 0;
        transform: translateY(30px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    h1 {
      text-align: center;
      color: #a0522d;
      margin-bottom: 20px;
    }

    img {
      display: block;
      max-width: 150px;
      margin: 0 auto 30px auto;
    }

    p {
      font-size: 18px;
      color: #333;
      line-height: 1.7;
      margin: 20px 0;
    }

    .firma {
      text-align: right;
      margin-top: 50px;
      font-style: italic;
      color: #555;
    }

    @media print {
      body {
        background: white;
      }

      .carta {
        box-shadow: none;
        border: none;
        margin: 0;
      }

      img {
        display: none; /* oculta imagen al imprimir si deseas */
      }
    }
</head>
<body>
  <div class="carta">
    <img src="https://i.ibb.co/CsJPSv6K/IMG-20250526-WA0005.jpg" alt="VALENTINO para Papá">
    <h1>Querido Papá</h1>
    <p>
      Hoy quiero escribirte estas palabras para recordarte lo especial que eres para mí.
      Gracias por cada consejo, por tu paciencia, y por estar siempre a mi lado.
    </p>
    <p>
      Eres mi ejemplo de fortaleza, de bondad y de amor incondicional. Me siento afortunado de tener un papá como tú.
    </p>
    <p>
      Aunque a veces no lo diga, te valoro con todo mi corazón. ¡Gracias por ser mi papá!
    </p>
    <p class="VALENTINO">
      Con mucho cariño,<br>
      AGUILA
    </p>
  </div>
</body>
</html>
