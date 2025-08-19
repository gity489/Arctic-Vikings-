<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Arctic Vikings</title>
<style>
  body {
    margin: 0;
    height: 100vh;
    background: linear-gradient(135deg, black, darkred, black);
    color: white;
    font-family: Arial, sans-serif;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }

  h1 {
    margin-bottom: 30px;
    color: crimson;
    text-shadow: 0 0 15px red;
  }

  .button-container {
    display: flex;
    gap: 20px;
    margin-bottom: 30px;
  }

  button {
    padding: 15px 30px;
    font-size: 1.2em;
    color: white;
    background-color: crimson;
    border: 2px solid red;
    border-radius: 10px;
    cursor: pointer;
    transition: 0.3s;
  }

  button:hover {
    background-color: red;
    transform: scale(1.1);
  }

  section {
    display: none;
    max-width: 70%;
    text-align: center;
  }

  section.active {
    display: block;
  }
</style>
</head>
<body>

<h1>Arctic Vikings</h1>

<div class="button-container">
  <button onclick="showPage('https://gity489.github.io/Arctic-Vikings-history/')">History</button>
  <button onclick="showPage('https://gity489.github.io/Arctic-Vikings-ranks/')">Ranking</button>
  <button onclick="showPage('https://gity489.github.io/Arctic-Vikings-events-/')">Events</button>
</div>

<section id="history" class="active">
  <h2>History</h2>
  <p>The Arctic Vikings history goes on.</p>
</section>

<section id="ranking">
  <h2>Ranking</h2>
  <p>The ice cold rankings (YIKES!).</p>
</section>

<section id="events">
  <h2>Events</h2>
  <p>Discover all events in Arctic Vikings history.</p>
</section>

<script>
function showPage(id) {
  document.querySelectorAll('section').forEach(s => s.classList.remove('active'));
  document.getElementById(id).classList.add('active');
}
</script>

</body>
</html>
 
