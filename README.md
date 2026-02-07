    <!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>VIP Predictions</title>
<style>
  body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #000;
    color: #fff;
  }

  .match-table {
    width: 100%;
    border-collapse: collapse;
  }

  .match-table th, .match-table td {
    padding: 10px 8px;
    text-align: center;
    font-size: 14px;
  }

  .match-table th {
    color: #00bfff;
    font-size: 15px;
    border-bottom: 2px solid #333;
  }

  .row-black { background-color: #000; }
  .row-holo { background-color: #111; }

  .pick { color: #ffcc00; font-weight: bold; }
  .scores { color: #00ff00; font-weight: bold; }

  /* Results colors */
  .win { color: #00ff00; font-weight: bold; }
  .loss { color: #ff0000; font-weight: bold; }
  .pending { color: #ffd700; font-weight: bold; } /* Gold */
</style>
</head>
<body>

<table class="match-table">
  <tr>
    <th>Date</th>
    <th>Match</th>
    <th>Pick</th>
    <th>Score</th>
    <th>Results</th>
  </tr>

  <tr class="row-black">
    <td>26/10/2026</td>
    <td>Barcelona vs Real Madrid</td>
    <td class="pick">Over 3.5</td>
    <td class="scores">3-2</td>
    <td class="win">Win</td>
  </tr>

  <tr class="row-holo">
    <td>27/10/2026</td>
    <td>Manchester City vs Liverpool</td>
    <td class="pick">Over 3.5</td>
    <td class="scores">4-1</td>
    <td class="loss">Loss</td>
  </tr>

  <tr class="row-black">
    <td>28/10/2026</td>
    <td>Juventus vs Inter Milan</td>
    <td class="pick">Over 3.5</td>
    <td class="scores">2-2</td>
    <td class="pending">Pending</td>
  </tr>

  <tr class="row-holo">
    <td>29/10/2026</td>
    <td>PSG vs Lyon</td>
    <td class="pick">Over 3.5</td>
    <td class="scores">3-1</td>
    <td class="win">Win</td>
  </tr>

  <tr class="row-black">
    <td>30/10/2026</td>
    <td>Chelsea vs Arsenal</td>
    <td class="pick">Over 3.5</td>
    <td class="scores">3-2</td>
    <td class="pending">Pending</td>
  </tr>
</table>

</body>
