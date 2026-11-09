# Clínica Dental Sonrisa

Template de reservas de tratamientos odontológicos, con selección de servicio y especialista, horarios, perfil y pantallas de pago simulado.

## Tecnología y alcance

HTML, CSS y JavaScript nativo. Usa Tailwind CSS vía CDN. No requiere un proceso de compilación para previsualizar las páginas. Se necesita conexión a Internet para cargar los recursos externos referenciados por los HTML, como estilos, fuentes e imágenes.

La autenticación y las reservas son demostrativas y utilizan almacenamiento del navegador. No hay backend ni conexión a una agenda compartida. Los pagos y las confirmaciones son simulados; no se procesan transacciones reales.

## Ejecución local

Desde esta carpeta, con Node.js y npm instalados:

```powershell
npx --yes http-server . -p 8080 -c-1
```

Abre [la vista previa local](http://localhost:8080/) y comienza en `index.html`. Mantén el mismo origen y puerto al recorrer las páginas para conservar los datos del navegador.

## Acceso de demostración

| Correo | Contraseña |
|---|---|
| `juan@test.com` | `123456` |
| `maria@test.com` | `123456` |

Abre la pantalla de inicio de sesión e ingresa con una cuenta de la tabla. Los cambios de perfil y las reservas se guardan solamente en ese navegador y origen.

## Páginas incluidas (17)

| Archivo | Título de la página |
|---|---|
| `confirmacion.html` | Cita Confirmada · Clínica Dental Sonrisa |
| `contacto.html` | Contacto · Clínica Dental Sonrisa |
| `detalle-reserva.html` | Detalle de Reserva · Clínica Dental Sonrisa |
| `galeria.html` | Galería · Clínica Dental Sonrisa |
| `horarios.html` | Horarios · Clínica Dental Sonrisa |
| `index.html` | Clínica Dental Sonrisa · Odontología Integral en Santiago |
| `inicio-sesion.html` | Iniciar Sesión · Clínica Dental Sonrisa |
| `pago-confirmado.html` | Pago Confirmado · Clínica Dental Sonrisa |
| `pago.html` | Pago de Reserva · Clínica Dental Sonrisa |
| `perfil.html` | Mi Perfil · Clínica Dental Sonrisa |
| `precios.html` | Precios · Clínica Dental Sonrisa |
| `privacidad.html` | Política de Privacidad · Clínica Dental Sonrisa |
| `recuperar-password.html` | Recuperar Contraseña · Clínica Dental Sonrisa |
| `registro.html` | Crear Cuenta · Clínica Dental Sonrisa |
| `reserva.html` | Reservar Cita · Clínica Dental Sonrisa |
| `servicios.html` | Servicios · Clínica Dental Sonrisa |
| `terminos.html` | Términos y Condiciones · Clínica Dental Sonrisa |

## Personalización

- Textos, imágenes, enlaces y datos de contacto: revisa los HTML y `main.js`.
- Colores, espaciados y ajustes responsivos: `css/styles.css`.
- Catálogos, datos de ejemplo y lógica del template: `main.js`. Algunos textos y resúmenes también están definidos en scripts dentro de los HTML.

Los importes visibles usan pesos chilenos (CLP) y los contactos son ejemplos para Chile. Sustituye precios, dirección, teléfono, correo e información del negocio antes de usarlos como datos comerciales.

## Comprobación visual

Recorre las páginas en móvil, tablet y escritorio. Comprueba que el menú, los formularios, las tarjetas y los precios permanezcan legibles; las tablas extensas pueden utilizar desplazamiento horizontal dentro de su contenedor.
