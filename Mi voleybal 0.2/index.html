<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Reserva tu hora - MI VALEIBOL</title>
  <script src="https://unpkg.com/html5-qrcode" type="text/javascript"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/html2canvas/1.4.1/html2canvas.min.js"></script>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #f7f9fc 0%, #e8f0fe 100%);
      padding: 20px;
      font-size: 18px;
      margin: 0;
      color: #1b1f3b;
    }

    .main-content {
      max-width: 600px;
      margin: 0 auto;
    }

    .header-logo {
      text-align: center;
      margin: 20px 0 30px;
    }

    .logo-text {
      font-family: 'Arial Black', 'Arial Bold', Gadget, sans-serif;
      font-size: 2.8rem;
      font-weight: 900;
      text-transform: uppercase;
      line-height: 1;
      text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.1);
      letter-spacing: -1px;
    }

    .logo-mi {
      color: #0056b3; /* Azul menos oscuro */
    }

    .logo-vale {
      color: #FF0000; /* Rojo */
    }

    .logo-ibol {
      color: #0056b3; /* Azul menos oscuro */
    }

    .login-button {
      background: linear-gradient(135deg, #0051ba, #002e6d);
      color: white;
      border: none;
      padding: 10px 20px;
      border-radius: 25px;
      cursor: pointer;
      font-size: 16px;
      position: absolute;
      top: 20px;
      right: 20px;
      box-shadow: 0 4px 12px rgba(0, 81, 186, 0.4);
      transition: background 0.3s ease;
      user-select: none;
    }

    .login-button:hover {
      background: linear-gradient(135deg, #002e6d, #001a44);
    }

    .container {
      max-width: 500px;
      margin: 0 auto 40px;
      background: white;
      padding: 30px 40px;
      border-radius: 15px;
      box-shadow: 0 8px 20px rgba(27, 31, 59, 0.12);
      position: relative;
    }

    label {
      font-weight: 600;
      display: block;
      margin-top: 15px;
      color: #3c4a72;
    }

    input, select {
      width: 100%;
      padding: 12px 15px;
      margin-top: 6px;
      border-radius: 8px;
      border: 1.8px solid #cbd3e0;
      font-size: 17px;
      color: #1b1f3b;
      transition: border-color 0.3s ease;
      box-sizing: border-box;
    }

    input:focus, select:focus {
      border-color: #0051ba;
      outline: none;
      box-shadow: 0 0 8px rgba(0, 81, 186, 0.3);
      background-color: #f0f4ff;
    }

    input[disabled], select[disabled] {
      border: none;
      background-color: transparent;
      color: #4a4f6a;
      padding: 0;
      font-weight: 600;
      cursor: default;
    }

    #codigoReserva {
      font-weight: 700;
      font-size: 20px;
      margin: 0;
      padding: 0;
      color: #0051ba;
      letter-spacing: 1.5px;
      font-family: 'Courier New', Courier, monospace;
      user-select: text;
    }

    .qr {
      margin-top: 30px;
      text-align: center;
    }

    #reader {
      width: 100%;
      margin: 10px auto;
      display: none;
      border: 2px solid #0051ba;
      border-radius: 10px;
      overflow: hidden;
    }

    #reader__dashboard_section_swaplink {
      display: none !important;
    }

    .botones {
      margin-top: 40px;
      display: flex;
      flex-direction: column;
      gap: 14px;
    }

    .botones-row {
      display: flex;
      gap: 15px;
    }

    .botones-row button {
      flex: 1;
      padding: 15px 0;
      font-size: 18px;
      border: none;
      border-radius: 25px;
      cursor: pointer;
      box-shadow: 0 6px 15px rgba(0, 81, 186, 0.25);
      font-weight: 700;
      transition: background 0.3s ease, box-shadow 0.3s ease;
      color: white;
      user-select: none;
    }

    .btn-scan {
      background: linear-gradient(135deg, #007aff, #004fcd);
    }

    .btn-scan:hover {
      background: linear-gradient(135deg, #004fcd, #002d94);
      box-shadow: 0 8px 20px rgba(0, 81, 186, 0.45);
    }

    .btn-compartir {
      background: linear-gradient(135deg, #6e48aa, #9d50bb);
      color: white;
      padding: 15px 0;
      font-size: 18px;
      border: none;
      border-radius: 25px;
      cursor: pointer;
      width: 100%;
      box-shadow: 0 6px 15px rgba(110, 72, 170, 0.3);
      font-weight: 700;
      transition: background 0.3s ease, box-shadow 0.3s ease;
      user-select: none;
    }

    .btn-compartir:hover {
      background: linear-gradient(135deg, #9d50bb, #6e48aa);
      box-shadow: 0 8px 20px rgba(110, 72, 170, 0.5);
    }

    .btn-editar {
      background: linear-gradient(135deg, #27ae60, #1e8449);
      color: white;
      padding: 15px 0;
      font-size: 18px;
      border: none;
      border-radius: 25px;
      cursor: pointer;
      width: 100%;
      display: none;
      box-shadow: 0 6px 15px rgba(39, 174, 96, 0.3);
      font-weight: 700;
      transition: background 0.3s ease, box-shadow 0.3s ease;
      user-select: none;
    }

    .btn-editar.show {
      display: block;
    }

    .btn-editar:hover {
      background: linear-gradient(135deg, #1e8449, #166635);
      box-shadow: 0 8px 20px rgba(39, 174, 96, 0.55);
    }

    .btn-guardar {
      background: linear-gradient(135deg, #f39c12, #e67e22);
      color: white;
      padding: 15px 0;
      font-size: 18px;
      border: none;
      border-radius: 25px;
      cursor: pointer;
      width: 100%;
      display: none;
      box-shadow: 0 6px 15px rgba(243, 156, 18, 0.3);
      font-weight: 700;
      transition: background 0.3s ease, box-shadow 0.3s ease;
      user-select: none;
      margin-top: 10px;
    }

    .btn-guardar.show {
      display: block;
    }

    .btn-guardar:hover {
      background: linear-gradient(135deg, #e67e22, #d35400);
      box-shadow: 0 8px 20px rgba(243, 156, 18, 0.5);
    }

    /* Modal login */
    .modal {
      display: none;
      position: fixed;
      z-index: 99;
      left: 0;
      top: 0;
      width: 100%;
      height: 100%;
      overflow: auto;
      background-color: rgba(11, 26, 82, 0.65);
    }

    .modal-content {
      background-color: white;
      margin: 10% auto;
      padding: 30px 25px;
      border-radius: 15px;
      width: 320px;
      box-shadow: 0 10px 25px rgba(27, 31, 59, 0.25);
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    .modal-content h2 {
      text-align: center;
      margin-bottom: 25px;
      color: #002d94;
      font-weight: 700;
      font-size: 26px;
      user-select: none;
    }

    .modal-content input {
      width: 100%;
      margin-bottom: 15px;
      padding: 12px 14px;
      font-size: 17px;
      border-radius: 8px;
      border: 1.8px solid #cbd3e0;
      transition: border-color 0.3s ease;
      box-sizing: border-box;
    }

    .modal-content input:focus {
      border-color: #0051ba;
      outline: none;
      box-shadow: 0 0 10px rgba(0, 81, 186, 0.4);
    }

    .close {
      color: #aaa;
      float: right;
      font-size: 28px;
      font-weight: bold;
      cursor: pointer;
      transition: color 0.3s ease;
      user-select: none;
    }

    .close:hover {
      color: #0051ba;
    }

    .modal-content button {
      background: linear-gradient(135deg, #0051ba, #002e6d);
      color: white;
      border: none;
      padding: 12px 20px;
      border-radius: 25px;
      cursor: pointer;
      font-size: 16px;
      width: 100%;
      box-shadow: 0 4px 12px rgba(0, 81, 186, 0.4);
      transition: background 0.3s ease;
      user-select: none;
    }

    .modal-content button:hover {
      background: linear-gradient(135deg, #002e6d, #001a44);
    }
  </style>
</head>
<body>

<div class="main-content">
  <div class="header-logo">
    <div class="logo-text">
      <span class="logo-mi">MI</span>
      <span class="logo-vale">VALE</span>
      <span class="logo-ibol">IBOL</span>
    </div>
  </div>

  <div class="container">
    <form id="reserva-form">
      <label>Cliente</label>
      <input type="text" id="cliente" value="Nombre" disabled>

      <label>Fecha</label>
      <input type="date" id="fecha" disabled>

      <label>Hora inicio</label>
      <input type="time" id="horaInicio" disabled>

      <label>Hora fin</label>
      <input type="time" id="horaFin" disabled>

      <label>Tipo de campo</label>
      <select id="campo" disabled>
        <option value="Losa vóleibol">Losa vóleibol</option>
        <option value="Gras fútbol">Gras fútbol</option>
      </select>

      <div id="codigo-container">
        <label>Código</label>
        <p id="codigoReserva"></p>
      </div>
    </form>

    <div class="qr">
      <canvas id="qr-code"></canvas>
    </div>

    <div class="botones">
      <div class="botones-row">
        <button type="button" class="btn-scan" onclick="abrirScanner()">📷 Escanear código QR</button>
      </div>
      <button type="button" class="btn-compartir" onclick="compartirPantalla()">COMPARTIR</button>
      <button type="button" class="btn-editar" onclick="activarEdicion()">Editar reserva</button>
      <button type="button" class="btn-guardar" onclick="guardarCambios()">Guardar cambios</button>
    </div>

    <div id="reader"></div>
  </div>
</div>

<button class="login-button" onclick="abrirLogin()">Iniciar sesión</button>

<!-- Modal login -->
<div id="loginModal" class="modal">
  <div class="modal-content">
    <span class="close" onclick="cerrarLogin()">&times;</span>
    <h2>Iniciar sesión</h2>
    <input type="text" id="usuario" placeholder="Usuario" />
    <input type="password" id="contraseña" placeholder="Contraseña" />
    <button onclick="verificarLogin()">Ingresar</button>
  </div>
</div>

<script src="https://cdn.jsdelivr.net/npm/qrious@4.0.2/dist/qrious.min.js"></script>
<script>
  const qr = new QRious({
    element: document.getElementById('qr-code'),
    size: 200,
    value: ""
  });

  const usuariosValidos = {
    "Arnold": "Arnold001",
    "Franklin": "Franklin002",
    "User3": "User003",
    "User4": "User004"
  };

  function abrirLogin() {
    document.getElementById('loginModal').style.display = 'block';
  }

  function cerrarLogin() {
    document.getElementById('loginModal').style.display = 'none';
  }

  function verificarLogin() {
    const usuario = document.getElementById('usuario').value;
    const clave = document.getElementById('contraseña').value;

    if (usuariosValidos[usuario] === clave) {
      alert("Bienvenido " + usuario + " 🎉");
      cerrarLogin();
      mostrarBotonEditar(true);
    } else {
      alert("Usuario o contraseña incorrectos");
      mostrarBotonEditar(false);
    }
  }

  function mostrarBotonEditar(mostrar) {
    const btnEditar = document.querySelector('.btn-editar');
    if (mostrar) {
      btnEditar.classList.add('show');
    } else {
      btnEditar.classList.remove('show');
      ['cliente', 'fecha', 'horaInicio', 'horaFin', 'campo'].forEach(id => {
        document.getElementById(id).disabled = true;
      });
      document.querySelector('.btn-guardar').classList.remove('show');
      actualizarCodigoYQR();
    }
  }

  function generarCodigo() {
    const fecha = document.getElementById('fecha').value;
    const horaInicio = document.getElementById('horaInicio').value;
    if (!fecha || !horaInicio) return "";
    const dia = fecha.slice(8, 10);
    const mes = fecha.slice(5, 7);
    const hora = horaInicio.replace(":", "");
    return dia + mes + hora;
  }

  function actualizarCodigoYQR() {
    const clienteInput = document.getElementById('cliente');
    const fechaInput = document.getElementById('fecha');
    const horaInicioInput = document.getElementById('horaInicio');
    const horaFinInput = document.getElementById('horaFin');
    const campoInput = document.getElementById('campo');

    const codigo = generarCodigo();
    document.getElementById('codigoReserva').textContent = codigo;

    const textoQR = 
      `Cliente: ${clienteInput.value}; Fecha: ${fechaInput.value}; ` +
      `Hora: ${horaInicioInput.value}-${horaFinInput.value}; Campo: ${campoInput.value}; ` +
      `Código: ${codigo}`;

    qr.value = textoQR;
  }

  function activarEdicion() {
    ['cliente', 'fecha', 'horaInicio', 'horaFin', 'campo'].forEach(id => {
      document.getElementById(id).disabled = false;
    });
    document.querySelector('.btn-guardar').classList.add('show');
  }

  function guardarCambios() {
    ['cliente', 'fecha', 'horaInicio', 'horaFin', 'campo'].forEach(id => {
      document.getElementById(id).disabled = true;
    });
    document.querySelector('.btn-guardar').classList.remove('show');
    actualizarCodigoYQR();
  }

  function abrirScanner() {
    const reader = document.getElementById('reader');
    
    if (window.html5QrCodeScanner) {
      window.html5QrCodeScanner.stop().then(() => {
        window.html5QrCodeScanner = null;
        iniciarNuevoEscaneo();
      }).catch(err => {
        console.error("Error al detener el escáner:", err);
        iniciarNuevoEscaneo();
      });
    } else {
      iniciarNuevoEscaneo();
    }

    function iniciarNuevoEscaneo() {
      reader.style.display = "block";
      
      window.html5QrCodeScanner = new Html5Qrcode("reader");
      
      window.html5QrCodeScanner.start(
        { facingMode: "environment" },
        { 
          fps: 10, 
          qrbox: { width: 250, height: 250 },
          aspectRatio: 1.0
        },
        qrCodeMessage => {
          alert("Código escaneado:\n" + qrCodeMessage);
          window.html5QrCodeScanner.stop().then(() => {
            reader.style.display = "none";
            window.html5QrCodeScanner = null;
          });
        },
        errorMessage => {
          if (!errorMessage.includes("QR code parse error")) {
            console.warn("Escaneo fallido: ", errorMessage);
          }
        }
      ).catch(err => {
        console.error("No se pudo iniciar el escáner:", err);
      });
    }
  }

  function compartirPantalla() {
    const loginBtn = document.querySelector('.login-button');
    loginBtn.style.visibility = 'hidden';

    html2canvas(document.querySelector('.main-content')).then(canvas => {
      loginBtn.style.visibility = 'visible';

      const imagen = canvas.toDataURL('image/png');
      
      const enlace = document.createElement('a');
      enlace.download = 'reserva-valeibol.png';
      enlace.href = imagen;
      
      if (navigator.share) {
        canvas.toBlob(blob => {
          const archivo = new File([blob], 'reserva-valeibol.png', { type: 'image/png' });
          navigator.share({
            title: 'Mi reserva en VALEIBOL',
            text: 'Te comparto mi reserva deportiva',
            files: [archivo]
          }).catch(err => {
            console.log('Error al compartir:', err);
            enlace.click();
          });
        });
      } else {
        enlace.click();
        alert('La imagen se ha guardado. Puedes compartirla desde tu galería.');
      }
    });
  }

  function formatearFecha(fecha) {
    const año = fecha.getFullYear();
    const mes = String(fecha.getMonth() + 1).padStart(2, '0');
    const dia = String(fecha.getDate()).padStart(2, '0');
    return `${año}-${mes}-${dia}`;
  }

  function formatearHora(fecha) {
    const horas = String(fecha.getHours()).padStart(2, '0');
    const minutos = String(fecha.getMinutes()).padStart(2, '0');
    return `${horas}:${minutos}`;
  }

  window.onload = () => {
    const ahora = new Date();
    document.getElementById('fecha').value = formatearFecha(ahora);
    
    const horaInicio = new Date(ahora.getTime() + 5 * 60000);
    document.getElementById('horaInicio').value = formatearHora(horaInicio);
    
    const horaFin = new Date(horaInicio.getTime() + 40 * 60000);
    document.getElementById('horaFin').value = formatearHora(horaFin);

    mostrarBotonEditar(false);
    actualizarCodigoYQR();
  }

  ['cliente', 'fecha', 'horaInicio', 'horaFin', 'campo'].forEach(id => {
    document.getElementById(id).addEventListener('input', actualizarCodigoYQR);
  });
</script>
</body>
</html>