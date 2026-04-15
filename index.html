html_content = """
<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Escape Room: Il Ponte Digitale</title>
    <style>
        :root {
            --primary: #4f46e5;
            --secondary: #ec4899;
            --bg: #0f172a;
            --card-bg: #1e293b;
            --text: #f8fafc;
            --success: #22c55e;
            --error: #ef4444;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--bg);
            color: var(--text);
            margin: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            min-height: 100vh;
        }

        #timer {
            font-size: 2rem;
            font-weight: bold;
            background: var(--secondary);
            padding: 10px 20px;
            border-radius: 0 0 20px 20px;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 4px 15px rgba(0,0,0,0.3);
        }

        .container {
            max-width: 800px;
            width: 90%;
            margin: 40px auto;
            background: var(--card-bg);
            padding: 30px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.5);
            text-align: center;
        }

        .level-box { display: none; }
        .level-box.active { display: block; animation: fadeIn 0.5s; }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }

        h1 { color: var(--secondary); }
        h2 { color: var(--primary); margin-bottom: 20px; }

        input[type="text"] {
            padding: 12px;
            width: 80%;
            border-radius: 8px;
            border: none;
            margin: 15px 0;
            font-size: 1rem;
        }

        button {
            padding: 12px 30px;
            background: var(--primary);
            color: white;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            font-size: 1rem;
            transition: 0.3s;
        }

        button:hover { background: #6366f1; transform: scale(1.05); }

        .feedback { margin-top: 20px; font-weight: bold; }
        .code-display {
            background: #334155;
            padding: 15px;
            border-radius: 10px;
            border: 2px dashed var(--secondary);
            margin-top: 20px;
        }

        .motivational {
            font-style: italic;
            color: #94a3b8;
            margin-bottom: 20px;
        }
        
        .hidden { display: none; }
        
        .final-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 10px;
            margin: 20px 0;
        }
    </style>
</head>
<body>

<div id="timer">30:00</div>

<div class="container" id="game-container">
    <div id="intro" class="level-box active">
        <h1>Benvenuti nell'Escape Room TIC</h1>
        <p>Avete 30 minuti per superare 8 livelli basati sul progetto "Il Ponte Digitale". Ogni livello vi darà una cifra. Annotatele tutte per sbloccare il diario finale!</p>
        <button onclick="startGame()">INIZIA IL VIAGGIO</button>
    </div>

    <div id="level1" class="level-box">
        <p class="motivational">"L'inclusione non è un posto, ma un modo di pensare."</p>
        <h2>Livello 1: La Piattaforma Core</h2>
        <p>Qual è lo strumento principale utilizzato per creare il "Diario Digitale" interattivo?</p>
        <button onclick="checkL1('Book Creator')">Book Creator</button>
        <button onclick="checkL1('PowerPoint')">PowerPoint</button>
        <button onclick="checkL1('Word')">Word</button>
        <div id="f1" class="feedback"></div>
    </div>

    <div id="level2" class="level-box">
        <p class="motivational">"Ogni piccolo passo è un grande traguardo."</p>
        <h2>Livello 2: Intelligenza Artificiale</h2>
        <p>Quale strumento IA è stato usato per generare i file audio esplicativi e il video sui processi mentali?</p>
        <input type="text" id="ans2" placeholder="Nome dell'applicazione...">
        <button onclick="checkL2()">Verifica</button>
        <div id="f2" class="feedback"></div>
    </div>

    <div id="level3" class="level-box">
        <p class="motivational">"La tecnologia è un ponte, non un muro."</p>
        <h2>Livello 3: Il Protocollo</h2>
        <p>Nel protocollo di rinforzo, su quale lato deve trovarsi la cerniera della busta per garantire il corretto movimento motorio?</p>
        <button onclick="checkL3('Destra')">Destra</button>
        <button onclick="checkL3('Sinistra')">Sinistra</button>
        <div id="f3" class="feedback"></div>
    </div>

    <div id="level4" class="level-box">
        <p class="motivational">"Non fermarti, la classe ti sta aspettando!"</p>
        <h2>Livello 4: Analisi del Contesto</h2>
        <p>Secondo il DSM-5, qual è il livello di gravità del disturbo dello spettro autistico dello studente?</p>
        <input type="text" id="ans4" placeholder="Inserisci il numero...">
        <button onclick="checkL4()">Verifica</button>
        <div id="f4" class="feedback"></div>
    </div>

    <div id="level5" class="level-box">
        <p class="motivational">"L'unione fa la forza: la classe raggiunge lo studente."</p>
        <h2>Livello 5: Immagini Interattive</h2>
        <p>Quale web-app è stata scelta per creare l'immagine interattiva con i pop-up?</p>
        <button onclick="checkL5('Canva')">Canva</button>
        <button onclick="checkL5('Genially')">Genially</button>
        <button onclick="checkL5('Prezi')">Prezi</button>
        <div id="f5" class="feedback"></div>
    </div>

    <div id="level6" class="level-box">
        <p class="motivational">"La comunicazione va oltre le parole."</p>
        <h2>Livello 6: Metodologia</h2>
        <p>Cosa deve fare lo studente nei corridoi come attività sociale minima?</p>
        <input type="text" id="ans6" placeholder="Azione principale (un verbo)...">
        <button onclick="checkL6()">Verifica</button>
        <div id="f6" class="feedback"></div>
    </div>

    <div id="level7" class="level-box">
        <p class="motivational">"Quasi alla fine! La tua dedizione è ammirevole."</p>
        <h2>Livello 7: Monitoraggio</h2>
        <p>Dove vengono condivisi i pensieri finali e le proposte dei compagni alla fine del diario?</p>
        <button onclick="checkL7('WhatsApp')">WhatsApp</button>
        <button onclick="checkL7('Padlet')">Padlet</button>
        <button onclick="checkL7('Instagram')">Instagram</button>
        <div id="f7" class="feedback"></div>
    </div>

    <div id="level8" class="level-box">
        <p class="motivational">"L'ultimo sforzo per sbloccare l'inclusione!"</p>
        <h2>Livello 8: Raccolta Dati</h2>
        <p>In quale formato sono stati inizialmente raccolti i dati prima di passarli su Book Creator?</p>
        <input type="text" id="ans8" placeholder="Nome del software...">
        <button onclick="checkL8()">Verifica</button>
        <div id="f8" class="feedback"></div>
    </div>

    <div id="final" class="level-box">
        <h1>MISSIONE COMPIUTA!</h1>
        <p>Inserisci la sequenza di 8 cifre che hai ottenuto per terminare il progetto.</p>
        <div class="final-grid">
            <input type="text" id="c1" maxlength="1">
            <input type="text" id="c2" maxlength="1">
            <input type="text" id="c3" maxlength="1">
            <input type="text" id="c4" maxlength="1">
            <input type="text" id="c5" maxlength="1">
            <input type="text" id="c6" maxlength="1">
            <input type="text" id="c7" maxlength="1">
            <input type="text" id="c8" maxlength="1">
        </div>
        <button onclick="checkFinal()">SBLOCCA IL DIARIO</button>
        <div id="ff" class="feedback"></div>
    </div>

    <div id="code-modal" class="code-display hidden">
        <p>Codice sbloccato per questo livello: <strong id="current-code">?</strong></p>
        <button onclick="nextLevel()">PROSEGUI</button>
    </div>
</div>

<script>
    let timeLeft = 30 * 60;
    let timerId;
    let currentLvl = 0;
    const codes = [5, 9, 2, 3, 7, 1, 4, 8]; // Cifre da rilasciare

    function startGame() {
        document.getElementById('intro').classList.remove('active');
        document.getElementById('level1').classList.add('active');
        startTimer();
    }

    function startTimer() {
        timerId = setInterval(() => {
            timeLeft--;
            let mins = Math.floor(timeLeft / 60);
            let secs = timeLeft % 60;
            document.getElementById('timer').innerText = 
                `${mins}:${secs < 10 ? '0' : ''}${secs}`;
            if (timeLeft <= 0) {
                clearInterval(timerId);
                alert("Tempo scaduto! Riprova.");
                location.reload();
            }
        }, 1000);
    }

    function showCode(num) {
        document.getElementById('current-code').innerText = codes[num-1];
        document.getElementById('code-modal').classList.remove('hidden');
    }

    function nextLevel() {
        document.getElementById('code-modal').classList.add('hidden');
        document.querySelector('.level-box.active').classList.remove('active');
        currentLvl++;
        const next = (currentLvl === 8) ? 'final' : 'level' + (currentLvl + 1);
        document.getElementById(next).classList.add('active');
    }

    // Logica validazione livelli
    function checkL1(val) {
        if(val === 'Book Creator') showCode(1);
        else document.getElementById('f1').innerText = "Riprova!";
    }

    function checkL2() {
        let val = document.getElementById('ans2').value.toLowerCase();
        if(val.includes('notebook')) showCode(2);
        else document.getElementById('f2').innerText = "È uno strumento di Google...";
    }

    function checkL3(val) {
        if(val === 'Sinistra') showCode(3);
        else document.getElementById('f3').innerText = "Controlla il protocollo!";
    }

    function checkL4() {
        if(document.getElementById('ans4').value == '3') showCode(4);
        else document.getElementById('f4').innerText = "È il livello di massima gravità...";
    }

    function checkL5(val) {
        if(val === 'Genially') showCode(5);
        else document.getElementById('f5').innerText = "Riprova!";
    }

    function checkL6() {
        let val = document.getElementById('ans6').value.toLowerCase();
        if(val.includes('salut') || val.includes('cammin')) showCode(6);
        else document.getElementById('f6').innerText = "Cosa facciamo quando incontriamo qualcuno?";
    }

    function checkL7(val) {
        if(val === 'Padlet') showCode(7);
        else document.getElementById('f7').innerText = "È una bacheca virtuale...";
    }

    function checkL8() {
        let val = document.getElementById('ans8').value.toLowerCase();
        if(val.includes('excel')) showCode(8);
        else document.getElementById('f8').innerText = "Un foglio di calcolo...";
    }

    function checkFinal() {
        let userCode = "";
        for(let i=1; i<=8; i++) userCode += document.getElementById('c'+i).value;
        
        if(userCode === codes.join('')) {
            clearInterval(timerId);
            document.getElementById('game-container').innerHTML = `
                <h1 style="color:var(--success)">CONGRATULAZIONI!</h1>
                <p>Hai sbloccato il Diario Digitale e completato l'analisi TIC.</p>
                <p>Tempo residuo: ${document.getElementById('timer').innerText}</p>
                <button onclick="location.reload()">Gioca ancora</button>
            `;
        } else {
            document.getElementById('ff').innerText = "Combinazione errata!";
            document.getElementById('ff').style.color = "var(--error)";
        }
    }
</script>

</body>
</html>
"""

# Salvo il file
with open("escape_room_tic.html", "w", encoding="utf-8") as f:
    f.write(html_content)
