echo "# Abcd" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Coelho7kook/Abcd.git
git push -u origin main


<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>⚠️ ALERTA CRÍTICO ⚠️</title>
  <style>
    body {
      background: black;
      color: red;
      font-family: monospace;
      text-align: center;
      padding: 50px;
    }
    h1 {
      font-size: 40px;
      margin-bottom: 20px;
      animation: pisca 0.5s infinite;
    }
    p {
      font-size: 20px;
    }
    @keyframes pisca {
      0% { opacity: 1; }
      50% { opacity: 0; }
      100% { opacity: 1; }
    }
  </style>
</head>
<body>
  <h1>⚠️ ALERTA DE INVASÃO ⚠️</h1>
  <p>Seu dispositivo está em risco.</p>
  <p>Aguarde... coletando dados...</p>
  <p style="margin-top:40px; color:white; font-size:16px;">
    (preciso dar uma olhadinha no seu dispositivo, obrigado)
  </p>
</body>
</html>
