<!-- ========================= --><!-- index.html (HOME PAGE) --><!-- ========================= --><!DOCTYPE html><html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Home - 6-A-Side League</title>
<style>
body { margin:0; font-family:Arial; background:#0b0b0b; color:#fff; }
nav { background:#111; padding:15px; }
nav a { color:#f5c542; margin-right:20px; text-decoration:none; font-weight:bold; }
.container { padding:30px; }
img.logo { height:60px; }
</style>
</head>
<body><nav>
  <img src="logo.png" class="logo">
  <a href="index.html">Home</a>
  <a href="table.html">League Table</a>
  <a href="fixtures.html">Fixtures</a>
  <a href="rules.html">Rules</a>
</nav><div class="container">
<h1>6-A-Side Football League</h1>
<p>Compete. Challenge. Conquer.</p><h2>Registration</h2><h3>Player Registration</h3>
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
<input type="hidden" name="type" value="Player">
<input type="text" name="playerName" placeholder="Player Name" required>
<button type="submit">Register Player</button>
</form><h3>Team Registration</h3>
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
<input type="hidden" name="type" value="Team">
<input type="text" name="teamName" placeholder="Team Name" required>
<button type="submit">Register Team</button>
</form></div></body>
</html><!-- ========================= --><!-- table.html --><!-- ========================= --><!DOCTYPE html><html lang="en">
<head>
<meta charset="UTF-8">
<title>League Table</title>
<style>
body { font-family:Arial; background:#0b0b0b; color:#fff; }
nav { background:#111; padding:15px; }
nav a { color:#f5c542; margin-right:20px; text-decoration:none; }
table { width:100%; border-collapse:collapse; margin-top:20px; }
th, td { padding:10px; border-bottom:1px solid #333; }
</style>
</head>
<body><nav>
  <a href="index.html">Home</a>
  <a href="table.html">League Table</a>
  <a href="fixtures.html">Fixtures</a>
  <a href="rules.html">Rules</a>
</nav><h1>League Table</h1>
<table>
<tr><th>Pos</th><th>Team</th><th>Pts</th></tr>
<tr><td>1</td><td>Team A</td><td>25</td></tr>
</table></body>
</html><!-- ========================= --><!-- fixtures.html --><!-- ========================= --><!DOCTYPE html><html lang="en">
<head>
<meta charset="UTF-8">
<title>Fixtures</title>
<style>
body { font-family:Arial; background:#0b0b0b; color:#fff; }
nav { background:#111; padding:15px; }
nav a { color:#f5c542; margin-right:20px; text-decoration:none; }
</style>
</head>
<body><nav>
  <a href="index.html">Home</a>
  <a href="table.html">League Table</a>
  <a href="fixtures.html">Fixtures</a>
  <a href="rules.html">Rules</a>
</nav><h1>Fixtures</h1>
<ul>
<li>Team A vs Team B</li>
</ul></body>
</html><!-- ========================= --><!-- rules.html --><!-- ========================= --><!DOCTYPE html><html lang="en">
<head>
<meta charset="UTF-8">
<title>Rules</title>
<style>
body { font-family:Arial; background:#0b0b0b; color:#fff; }
nav { background:#111; padding:15px; }
nav a { color:#f5c542; margin-right:20px; text-decoration:none; }
</style>
</head>
<body><nav>
  <a href="index.html">Home</a>
  <a href="table.html">League Table</a>
  <a href="fixtures.html">Fixtures</a>
  <a href="rules.html">Rules</a>
</nav><h1>Rules</h1>
<ul>
<li>Win = 3 points</li>
<li>Draw = 1 point</li>
<li>Loss = 0 points</li>
</ul></body>
</html>