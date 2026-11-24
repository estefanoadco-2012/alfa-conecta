# ALFA Conecta

Sistema de servicio al cliente de ALFA Meat Culture (prototipo del proyecto de Gestión de Servicios, UCSP).

- **Vistas:** WhatsApp (simulación de reservas), Mesero, Carta digital, Cocina, Caja, Botón de mesa, Evaluación y reclamos, Termómetro, Club ALFA y Protocolos.
- **Datos:** Firebase (Firestore), compartidos en vivo entre tablets. Sin la configuración de Firebase, abre en modo demostración y no guarda.
- **Acceso:** cuenta del personal en Firebase Authentication (correo y contraseña).
- **Publicación:** Vercel, sitio estático (`index.html`), sin compilación.

Configuración: pegar el bloque `firebaseConfig` en `const FIREBASE_CONFIG` dentro de `index.html`, y publicar las reglas de `firestore.rules` en Firestore.
