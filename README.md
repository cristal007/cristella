<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>www.Cristella.com.br</title>
       <style>
       
        body, html {
            margin: 0;
            padding: 0;
            scroll-behavior: smooth; /* Faz a rolagem ser suave */
        }
        .section {
            width: 100vw;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 50px 20px;
        }
        .section {
            width: 100vw;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 50px 20px;
        }

        #main-section {
            background-color: #A3C1AD; /* Cor verde "lésbico" */
            color: white;
            font-size: 2em;
        }

        #second-section {
            background-color: #f0f0f0;
            color: #333;
        }

        #relationship-section {
            background-color: #ffffff; /* Fundo branco */
            color: #444;
            font-size: 1.2em;
            line-height: 1.6;
            padding-top: 20px;
            padding-bottom: 50px;
        }

        #relationship-section h2 {
            margin: 0;
            padding: 10px 20px;
            font-size: 2em;
            color: #333;
            background-color: #A3C1AD; /* Tom verde "lésbico" */
            width: 100%;
            text-align: center;
        }

        .button {
            margin-top: 20px;
            padding: 15px 30px;
            background-color: white;
            color: #4CAF50;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1em;
        }

        .button:hover {
            background-color: #333;
            color: white;
        }
        
    
       .perfil-img {
            width: 150px;
            border-radius: 50%;
            margin-top: 15px;
        }
        .perfil-img {
    border: 3px solid #333;
}

/* Seletores de id */
#sobre {
    background-color: #fff;
    margin: 20px auto;
    padding: 20px;
    max-width: 800px;
    border-radius: 10px;
}
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
}

.video-container {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 20px;
}

video {
    max-width: 100%;
    height: auto;
    border-radius: 10px; /* Opcional: adiciona bordas arredondadas */
}



       </style>
</head>
<body>

    <!-- Primeira seção ocupando toda a tela inicial -->
    <section id="main-section" class="section">
        <div>
            <h1>Bem-vindo ao site dedicado ao nosso namoro!</h1>
            <button class="button" onclick="scrollToSection('second-section')">Veja mais</button>
        </div>
    </section>

    <!-- Segunda seção com conteúdo adicional -->
    <section id="second-section" class="section">
        <h1>Sobre Nós</h1>
        <p>Nos resumimos a desejos realizados, encontros, premeditos, fés, marés...</p>
        <button class="button" onclick="scrollToSection('relationship-section')">Continuar</button>
    </section>

    <!-- Terceira seção com texto sobre o relacionamento -->
    <section id="relationship-section" class="section">
        <h2>Tu é Tu </h2>
        <h4>A você, meu bem, dedico essa música, pois, quantos encontros cabem em uma vida?<br>Quantas vidas temos para viver?</h4>
       
  
          
    <script>
        // Função para rolar suavemente para qualquer seção
        function scrollToSection(sectionId) {
            document.getElementById(sectionId).scrollIntoView({ behavior: "smooth" });
        }
    </script>

</body>
</html>
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Video Test</title>
    <style>
        .video-container {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f0f0;
        }

        video {
            width: 80vw;
            aspect-ratio: 4 / 9;
            max-height: 90vh;
        }
    </style>
</head>
<body>
   
     
    <video width="640" height="360" controls>
        <source src="selva.mov" type="video/mp4">
            
        </source>
    </video>
    
    <a href="https://youtube.com/shorts/W-PKKPKgYzY?si=TJAq7j3xOSfsW-V7" target="_blank">Abrir Video</a>
     <footer id="main-footer">
        <p>&copy; 2024 Cristella. Todos os direitos reservados.</p>
       
    </footer> 
</body>
</html>
