<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Reclamar Brainrot</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
    }
    .card {
      background: white;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.15);
      width: 100%;
      max-width: 400px;
      text-align: center;
    }
    input {
      width: 100%;
      padding: 10px;
      margin: 8px 0;
      border: 1px solid #ccc;
      border-radius: 6px;
    }
    button {
      background: #5865F2; /* color de Discord */
      color: white;
      border: none;
      padding: 12px;
      width: 100%;
      border-radius: 6px;
      cursor: pointer;
      font-size: 16px;
    }
    button:hover {
      background: #4752C4;
    }
  </style>
</head>
<body>
  <div class="card">
    <h2>Reclamar tu compra</h2>
    <form onsubmit="redirectDiscord(); return false;">
      <input type="text" id="roblox" placeholder="Usuario de Roblox" required>
      <input type="text" id="paypal" placeholder="ID de Transacción PayPal" required>
      <button type="submit">Enviar</button>
    </form>
  </div>

  <script>
    function redirectDiscord() {
      // 👉 Pega aquí tu link de invitación real de Discord
      window.location.href = "https://discord.gg/TU-LINK-AQUI";
    }
  </script>
</body>
</html>
