<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
        <header>
                <h1>Contador</h1>
        </header>
        <section>
        <div>
        <p>Inicio: <input type="number" name="Inicio" id="txti"</p>
        <p>Fim:<input type="number" name="fim"  id="txtf"   </p>
        <p>Passo: <input type="number" name="passo" id="txtp" </p>
        <p> <input type="button" value="contar" onclick="contar()" </p>
        </div>
        <div id="res">
            Preparando contagem... 
        </div>
        </section>
        <footer>
            <p>&copy; FelipeCapiTwitch</p>
        </footer>
        <script src="script.js"></script>
        
</body>
</html>
