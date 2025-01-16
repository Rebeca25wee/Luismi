# Luismi
Playlist picker (not srs really)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Luismi Song Voodo</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        /* Custom CSS */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f8f9fa;
        }
        header {
            background: linear-gradient(135deg, #b97c19, #bc9520cf);
            color: white;
        }
        .mood-buttons button {
            font-size: 4rem;
            padding: 4rem 4rem;
        }
        #results {
            transition: all 0.3s ease-in-out;
        }
        footer {
            background-color: #b57e00cc;
            color: rgb(19, 9, 9);
            font-size: 20px;
        }
        .nav-item{
          margin-top: 15px;
          padding:5px;
        }
        .lead {
          margin-top: 25px;
          color:black;
        }
        .display-4 {
          font-weight: bold;
          color:black;
        }

    </style>
</head>
<body>
    <!-- Header Section -->
    <header class="d-flex flex-wrap justify-content-center py-3 mb-4 border-bottom">
      <a href="/" class="d-flex align-items-center mb-3 mb-md-0 me-md-auto text-dark text-decoration-none">
        <svg class="bi me-2" width="40" height="32"><use xlink:href="#bootstrap"></use></svg>
        <span class="fs-4"><h4>Looking for a Luismi Song? Got you covered.</h4></span>

      </a>

      <ul class="nav nav-pills">
        <li class="nav-item"><a href="https://youtu.be/xvFZjo5PgG0?si=kFzQdu0hmYo2TJyg" class="nav-link active" aria-current="page" style="background-color: black; font-weight: bold;">Origins</a></li>
        <li class="nav-item"><a href="https://www.celebritytalent.net/sampletalent/1040/luis-miguel/" class="nav-link" style="color: black; font-weight: bold;">Pricing</a></li>
        <li class="nav-item"><a href="https://youtu.be/y0sF5xhGreA?si=UXVtZoBt4X_SZDwc" class="nav-link" style="color: black; font-weight: bold;">About me</a></li>
      </ul>
    </header>
    <header class="text-center py-5">
        <h1 class="display-4">Luismi Mood Selector</h1>
        <p class="lead">We have a wide selection of songs made by experts who got heartbroken, happy, angered, excited, anxious, among other things. This website is the best option for people who analyze the lyrics and rythm.</p>
    </header>

    <!-- Main Content -->
    <main class="container my-5">
        <!-- Mood Selector -->
        <section id="selector" class="text-center">
            <h2 class="mb-4">Describe tu mood</h2>
            <div class="mood-buttons d-flex justify-content-center gap-3 flex-wrap">
                <button class="btn btn-primary" data-mood="karaoke"><a href="https://open.spotify.com/playlist/3qvtJbAXOqL3TCOap9repj?si=mWU_rb5oTtWsAUnPqn9ISg">🎤🌟</a></button>
                <button class="btn btn-secondary" data-mood="nostalgico"><a href="https://open.spotify.com/playlist/4gwj40gdWkoaWJ5Lmf3tkT?si=BPL5NiemR2mPWto5g2HXiA">😭🍷</a></button>
                <button class="btn btn-danger" data-mood="romantico"><a href="https://open.spotify.com/playlist/050lkYnGXU198u1kwVZW8A?si=fvuhQFkdRyWpUEje450xsQ">💖</a></button>
                <button class="btn btn-success" data-mood="fiesta"><a href="https://open.spotify.com/playlist/3wlbxzFaEaR88i9ZNxGUvX?si=SJe0gtxMS5O2IlOUZMWlvQ">💃🎺</a></button>
            </div>
        </section>

        <!-- Song Recommendation -->
        <section id="results" class="mt-5 text-center">
            <h2>Mi consejito</h2>
            <div id="song-container" class="mt-3 p-4 border rounded bg-white shadow-sm">
                <p class="text-muted">Busca una canción que sea un vibe. NO. PIENSES. EN. NADIE. Son joyitas. Además de eso nada... disfruten ;)</p>
            </div>
        </section>
    </main>

    <div class=
"container rounded h-75 w-5 m-20 p-30 text-light bg-success">
		<h1>FAQ</h1>
		<div class="accordion" id="accordionExample" style="margin-inline-start: 300px;">
			<div class="accordion-item">
				<h2 class="accordion-header">
					<button class="accordion-button"
						type="button" data-bs-toggle="collapse"
						data-bs-target="#collapseOne" aria-expanded="true"
						aria-controls="collapseOne">
						How are you so talented, Rebeca?
					</button>
				</h2>
				<div id="collapseOne" class="accordion-collapse collapse show"
					data-bs-parent="#accordionExample">
					<div class="accordion-body">
						<strong>WELL</strong> 
					... I wouldn´t say I´m talented but we all can tell hard work pays off. These days people can´t find websites that necesarilly resonate with them, so by creating a LUIMI SONG SELECTOR website I plan making a better world- people will feel understood. :)
					</div>
				</div>
			</div>
			<div class="accordion-item">
				<h2 class="accordion-header">
					<button class="accordion-button collapsed" type="button"
						data-bs-toggle="collapse" data-bs-target="#collapseTwo"
						aria-expanded="false" aria-controls="collapseTwo">
						Was this idea entirely yours?
					</button>
				</h2>
				<div id="collapseTwo" class="accordion-collapse collapse"
					data-bs-parent="#accordionExample">
					<div class="accordion-body">
						<strong>
							I would like to say so... I am no Mark Zuckerberg
						</strong> 
						This idea emerged from a conversation I had with a friend of mine. Hopefully this website will get the recognition it deserves and I get to develop this idea further.
					</div>
				</div>
			</div>
			<div class="accordion-item">
				<h2 class="accordion-header">
					<button class="accordion-button collapsed"
						type="button" data-bs-toggle="collapse"
						data-bs-target="#collapseThree" aria-expanded="false"
						aria-controls="collapseThree">
						Do you have any plans for the future (website)?
					</button>
				</h2>
				<div id="collapseThree" class="accordion-collapse collapse"
					data-bs-parent="#accordionExample">
					<div class="accordion-body">
						<strong>
							I´m glad you asked!! yes, I do.
						</strong> 
						Because the staff was short on time, most of the website was done with bootstrap and with spotify playlist. I get the charm of simpleness. However, I want to randomize the spotify playlist directly from the website and that will take some js work. Aditionally, I want to create a more visually pleasing design but for that I´ll have to revise my notes of fonts/color theory. 
					</div>
				</div>
			</div>
		</div>
	</div>

    <!-- Footer -->
    <footer class="text-center py-3" style="margin-top: 30px;">
      <small>&copy; website para gente dolida</small>
  </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
