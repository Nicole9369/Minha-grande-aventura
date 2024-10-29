# Minha-grande-aventura
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Animação CSS</title>
    <style>
        .bola {
            width: 50px;
            height: 50px;
            background-color: #3498db;
            border-radius: 50%;
            animation: bounce 1s infinite;
        }
        
        @keyframes bounce {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-20px);
            }
        }
    </style>
</head>
<body>
    <div class="bola"></div>
</body>
</html>
