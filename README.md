<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>StaticM223 Projects</title>

<style>
body{
    margin:0;
    background:#0f172a;
    color:white;
    font-family:Arial,Helvetica,sans-serif;
}

.container{
    max-width:900px;
    margin:60px auto;
    padding:20px;
}

h1{
    text-align:center;
    margin-bottom:40px;
}

.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.card{
    background:#1e293b;
    border-radius:12px;
    padding:25px;
    text-decoration:none;
    color:white;
    transition:.2s;
    border:1px solid #334155;
}

.card:hover{
    transform:translateY(-4px);
    background:#334155;
}

.card h2{
    margin-top:0;
}

.card p{
    color:#cbd5e1;
}
</style>
</head>

<body>

<div class="container">

<h1>StaticM223 GitHub Pages</h1>

<div class="grid">

<a class="card" href="https://staticm223.github.io/backup-dualshock-tools.github.io/">
<h2>🎮 DualShock Tools</h2>
<p>Backup of the DualShock/DualSense calibration utility.</p>
</a>

<a class="card" href="#">
<h2>📦 Future Project</h2>
<p>Coming soon...</p>
</a>

<a class="card" href="#">
<h2>🔧 Future Project</h2>
<p>Coming soon...</p>
</a>

</div>

</div>

</body>
</html>
