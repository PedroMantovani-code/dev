<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NeoDev Blog - Cyberpunk Hub</title>
    <style>
        /* Estilos Globais e Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Courier New', Courier, monospace;
            line-height: 1.6;
            color: #00ffcc; /* Verde Neon */
            background-color: #0d0e15; /* Roxo Escuro / Preto Espacial */
        }
        a {
            color: #ff007f; /* Rosa Neon */
            text-decoration: none;
            transition: all 0.3s ease;
        }
        a:hover {
            color: #00ffcc;
            text-shadow: 0 0 8px #00ffcc;
        }

        /* Cabeçalho */
        header {
            background: linear-gradient(180deg, #1a0826 0%, #0d0e15 100%);
            border-bottom: 3px solid #ff007f;
            color: #fff;
            padding: 3rem 1rem;
            text-align: center;
            box-shadow: 0 0 20px rgba(255, 0, 127, 0.2);
        }
        header h1 {
            font-size: 3rem;
            margin-bottom: 0.5rem;
            color: #fff;
            text-shadow: 0 0 10px #ff007f, 0 0 20px #ff007f;
            text-transform: uppercase;
            letter-spacing: 2px;
        }
        header p {
            font-size: 1.1rem;
            color: #00ffcc;
            text-shadow: 0 0 5px rgba(0, 255, 204, 0.5);
        }

        /* Layout Principal */
        .container {
            max-width: 1100px;
            margin: 2rem auto;
            padding: 0 1rem;
            display: grid;
            grid-template-columns: 3fr 1fr;
            gap: 2rem;
        }

        /* Lista de Postagens */
        .main-content {
            display: flex;
            flex-direction: column;
            gap: 2rem;
        }
        article {
            background: #161925;
            padding: 2rem;
            border-radius: 8px;
            border: 1px solid #3d1e6d;
            box-shadow: 0 4px 15px rgba(0,0,0,0.5);
            transition: transform 0.2s ease;
        }
        article:hover {
            transform: translateY(-3px);
            border-color: #ff007f;
            box-shadow: 0 0 15px rgba(255, 0, 127, 0.3);
        }
        article h2 {
            font-size: 1.8rem;
            color: #fff;
            margin-bottom: 0.5rem;
        }
        article h2 a {
            color: #fff;
        }
        article h2 a:hover {
            color: #ff007f;
            text-shadow: 0 0 5px #ff007f;
        }
        article .meta {
            font-size: 0.85rem;
            color: #7a889b;
            margin-bottom: 1rem;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        article p {
            margin-bottom: 1.5rem;
            color: #b3c5d7;
        }
        .read-more {
            font-weight: bold;
            border: 1px solid #ff007f;
            padding: 0.5rem 1rem