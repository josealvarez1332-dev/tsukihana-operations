# 🌸 Tsukihana (月花) · Guía Rápida de Publicación (Opción A)

Esta carpeta **`Tsukihana_Web_Produccion`** contiene todo el ecosistema digital listo para subir a internet en menos de 2 minutos.

---

## 🚀 Método 1: Publicar en 1 Minuto con Netlify Drop (Recomendado, 100% Gratis)

No necesitas instalar programas ni escribir comandos en el terminal:

1. Abre tu navegador web y entra en: **[https://app.netlify.com/drop](https://app.netlify.com/drop)**
2. Inicia sesión (o crea una cuenta gratuita con Google / GitHub / Email si aún no tienes una).
3. **Arrastra la carpeta completa `Tsukihana_Web_Produccion`** dentro del recuadro de Netlify en tu pantalla.
4. En **10 segundos**, Netlify desplegará la web y te dará una dirección pública protegida con certificado de seguridad SSL HTTPS (por ejemplo: `tsukihana-vigo.netlify.app`).
5. *(Opcional)* En el panel de Netlify puedes cambiar el nombre del subdominio o añadir tu dominio propio (por ejemplo `tsukihanasushi.es` o `tsukihana.es`).

---

## ⚡ Método 2: Publicar con Vercel

Si prefieres usar Vercel:

1. Entra en **[https://vercel.com](https://vercel.com)**.
2. Pulsa en **"Add New Project"** y sube la carpeta, o si usas el terminal, ejecuta:
   ```bash
   cd ~/Desktop/Tsukihana_Web_Produccion
   npx vercel deploy --prod
   ```
3. Tu web estará operativa de inmediato en una URL global de alta velocidad.

---

## 📞 Datos de Contacto Oficiales Configurados

- **Teléfono y WhatsApp:** `+34 655 35 07 09`
- **Enlace directo WhatsApp:** `https://wa.me/34655350709`
- **Ubicación:** Vigo, Galicia (Obrador y delivery de sushi artesanal)
- **Tarifa Chef Privado (Omakase / Eventos):** `18,99 €/hora`

---

## 🔗 Cómo Conectar Resérvalo

1. **Si ya tienes cuenta en Resérvalo (`reservalo.es`):**
   - Cópianos tu enlace público de reservas (ejemplo: `https://reservalo.es/r/tsukihana`).
   - Puedes pegarlo en el chat y lo dejamos grabado en el código fuente, o entrar en `operaciones.html` y guardarlo en el campo de configuración rápida.
2. **Si todavía no tienes cuenta en Resérvalo:**
   - Entra en [reservalo.es](https://reservalo.es) y date de alta como establecimiento hostelero / catering.
   - Crea tus turnos (Viernes noche, Sábado mediodía/noche, Domingos) y obtendrás tu enlace exclusivo.
   - Mientras tanto, **todos los pedidos entran de forma directa e instantánea a través del WhatsApp oficial (+34 655 35 07 09)**.

---

## 📂 Contenido del Paquete de Producción

| Archivo | Función |
| :--- | :--- |
| **`index.html`** | **Página Web Principal de Clientes**. Carta, cajas, alérgenos, fotos interactivas, botón flotante de WhatsApp (+34 655 35 07 09) y reservas. |
| **`operaciones.html`** | **Portal Privado del Equipo**. Acceso rápido para la dirección y el chef a todos los módulos internos. |
| **`02_Calculadora_Escandallos_y_Carta_Tsukihana.html`** | Control de Food Cost %, gramajes limpios y mermas. |
| **`03_Dossier_Catering_y_Experiencias_Editable_Tsukihana.html`** | Presupuestos de Catering y Omakase con chef a 18,99 €/h y exportación PDF A4. |
| **`04_Cabina_Operativa_Pedidos_y_Lanzamiento_Tsukihana.html`** | Gestión de pedidos entrantes, cálculo de arroz shari y checklist de cocina. |
| **`05_Pagina_Carta_y_Maquetas_Tsukihana.html`** | Carta 16 piezas, formato QR y carta A4 imprimible. |
| **`06_Gestor_Inventario_y_Calculadora_Gramaje_Tsukihana.html`** | Stock en nevera y desglose por ingredientes. |
| **`07_Integracion_Reservalo_x_Tsukihana_Maqueta.html`** | Control de cupos y turnos de Resérvalo. |
| **`08_App_Movil_Tsukihana_Maqueta.html`** | Simulador iPhone de app de cliente y app de cocina. |
| **`09_App_Escaneado_Inventario_x_Tsukihana.html`** | Terminal ScanStock con lector físico USB/Bluetooth y cámara con sonido láser. |
