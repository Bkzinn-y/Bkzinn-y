<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Currículo</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: url('https://img.freepik.com/fotos-gratis/predio-de-escritorios-moderno-opiniao-de-angulo-baixo-dos-arranha-ceus-na-cidade-de-singapura-predio-de-escritorios-moderno-opiniao-de-angulo-baixo-dos-arranha-ceus-na-cidade-de-singapura_231208-1463.jpg') no-repeat center center fixed;
            background-size: cover;
            color: #333;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            position: relative;
        }
        body::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.5);
            z-index: -1;
        }
        .container {
            background: rgba(255, 255, 255, 0.6);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            overflow: hidden;
            width: 60%;
            max-width: 800px;
            position: relative;
            z-index: 1;
        }
        .header {
            background: linear-gradient(135deg, rgba(135, 206, 235, 0.7), rgba(255, 182, 193, 0.7));
            color: white;
            text-align: center;
            padding: 20px;
        }
        .content {
            padding: 20px;
        }
        h2 {
            border-bottom: 2px solid rgba(135, 206, 235, 0.6);
            padding-bottom: 5px;
        }
        .section {
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Seu Nome</h1>
            <p>Cargo ou Profissão</p>
        </div>
        <div class="content">
            <div class="section">
                <h2>Contato</h2>
                <p>Email: seuemail@example.com</p>
                <p>Telefone: (XX) XXXXX-XXXX</p>
            </div>
            <div class="section">
                <h2>Experiência</h2>
                <p><strong>Empresa X</strong> - Cargo (Ano - Ano)</p>
                <p>Descrição das atividades realizadas.</p>
                <p><strong>Empresa Y</strong> - Cargo (Ano - Ano)</p>
                <p>Descrição das atividades realizadas.</p>
            </div>
            <div class="section">
                <h2>Educação</h2>
                <p><strong>Nome da Instituição</strong> - Curso (Ano - Ano)</p>
            </div>
            <div class="section">
                <h2>Habilidades</h2>
                <p>Habilidade 1, Habilidade 2, Habilidade 3...</p>
            </div>
        </div>
    </div>
</body>
</html>
