<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Flex layout</title>
  <link rel="stylesheet" href="index.css" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Lexend+Deca&display=swap" rel="stylesheet">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Big+Shoulders+Display:wght@700&display=swap" rel="stylesheet">
</head>

<body>
  <header class="navbar">
    <a href="index.html">FLEX</a>
    <a href="#" class="active">&</a>
    <a href="grid.html">GRID</a>
  </header>

  <main>
    <div class="container">
      <div class="column1">
        <img src="icon-sedans.svg" alt="SEDANS" />
        <h2>SEDANS</h2>
        <p>
          Choose a Sedan for its affordability and excellent fuel economy.
          Ideal for cruising in the city or on your next road trip.
        </p>
        <button id="s1" type="button">Learn More</button>
      </div>
      <div class="column2">
        <img src="icon-suvs.svg" alt="SUV" />
        <h2>SUVS</h2>
        <p>
          Take an SUV for its spacious interior, power, and versatility.
          Perfect for your next family vacation and off-road adventures.
        </p>
        <button id="s2" type="button">Learn More</button>
      </div>
      <div class="column3">
        <img src="icon-luxury.svg" alt="LUXURY" />
        <h2>LUXURY</h2>
        <p>
          Cruise in the best car brands without the bloated prices. Enjoy the
          enhanced comfort of a luxury rental and arrive in style.
        </p>
        <button id="s3" type="button">Learn More</button>
      </div>
    </div>
  </main>
</body>

</html>
