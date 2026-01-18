# Design_foot_13
Site affiche de foot 
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Affiches de Foot – Créations</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    body { margin:0; font-family:Arial,sans-serif; background:#0b1320; color:white; }
    header { padding:70px 20px; text-align:center; background:linear-gradient(135deg,#001f3f,#003366); }
    header h1 { font-size:2.5rem; margin-bottom:10px; }
    header p { opacity:0.9; }
    section { padding:60px 20px; max-width:1200px; margin:auto; }
    h2 { text-align:center; margin-bottom:40px; font-size:2rem; }
    .gallery { display:grid; grid-template-columns:repeat(auto-fit,minmax(220px,1fr)); gap:20px; }
    .poster { background:#111827; border-radius:15px; overflow:hidden; box-shadow:0 10px 25px rgba(0,0,0,0.4); transition:transform 0.3s; }
    .poster:hover { transform:scale(1.05); }
    .poster img { width:100%; display:block; }
    .poster p { padding:15px; text-align:center; font-weight:bold; }
    form { max-width:500px; margin:auto; background:#111827; padding:30px; border-radius:15px; }
    input,textarea { width:100%; padding:12px; margin-bottom:15px; border:none; border-radius:10px; font-size:1rem; }
    textarea { resize:none; height:120px; }
    button { width:100%; padding:15px; border:none; border-radius:30px; font-size:1rem; font-weight:bold; cursor:pointer; background:white; color:#003366; transition:background 0.2s, transform 0.2s; }
    button:hover { background:#eaeaea; transform:scale(1.03); }
    footer { text-align:center; padding:30px; opacity:0.7; font-size:0.9rem; }
  </style>
</head>
<body>

<header>
  <h1>Mes affiches de foot ⚽</h1>
  <p>Créations graphiques – Matchs, joueurs, clubs</p>
</header>

<section>
  <h2>Mes créations</h2>
  <div class="gallery">
    <div class="poster">
      <img src="https://via.placeholder.com/400x550?text=Affiche+1" alt="Affiche foot">
      <p>OM vs Liverpool</p>
    </div>
    <div class="poster">
      <img src="https://via.placeholder.com/400x550?text=Affiche+2" alt="Affiche foot">
      <p>Arsenal vs Man United</p>
    </div>
    <div class="poster">
      <img src="https://via.placeholder.com/400x550?text=Affiche+3" alt="Affiche foot">
      <p>Joueur – Poster spécial</p>
    </div>
  </div>
</section>

<section>
  <h2>Demander une affiche personnalisée</h2>
  <form action="mailto:ilanmathe61@gmail.com" method="post" enctype="text/plain">
    <input type="text" name="Nom" placeholder="Ton nom" required>
    <input type="email" name="Email" placeholder="Ton email" required>
    <textarea name="Demande" placeholder="Match, joueur, style souhaité..." required></textarea>
    <button type="submit">Envoyer la demande</button>
  </form>
</section>

<footer>
  © 2026 – Créations d’affiches de foot
</footer>

</body>
</html>
