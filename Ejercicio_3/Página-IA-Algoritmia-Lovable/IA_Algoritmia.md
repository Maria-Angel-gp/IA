# Página desplegada - hecha con stitch y lovable
link: https://studio-work-shelf.lovable.app/  

Imagen de inicio:
### Sugerencia: Inicia como invitado  

<img width="1856" height="887" alt="Captura de pantalla 2026-11-16 131837" src="https://gist.github.com/user-attachments/assets/1f23b273-d467-4338-9300-240810bb5283" />

## Prompt utilizado

```
📋 PROMPT MAESTRO: Medellín Explora – Plataforma Turística & Experiencias Locales
Objetivo: Diseñar y desarrollar una plataforma web y móvil integral (PWA / Responsive) para Medellín Explora, una plataforma de turismo experiencial, comunitario y nocturno en el Valle de Aburrá (Medellín, Colombia). La plataforma conecta viajeros y locales con planes auténticos (miradores, chivas tradicionales, cantinas históricas, senderismo, café y gastronomía paisa), integrando mapa interactivo, sistema de reservas con tiquete digital QR y panel para anfitriones locales.

1. Identidad de Marca y Sistema de Diseño (Design System)
Nombre de Marca: Medellín Explora
Eslogan / Propuesta de Valor: "Tu pasaporte a miradores mágicos, chivas con sabor paisa, café de altura y senderos verdes."
Paleta de Color Institucional:
Color Primario (Esmeralda Paisa): #059669 / #047857 (Naturaleza, confianza, identidad colombiana).
Color Acento / Acción: #EA580C / #F97316 (Naranja atardecer y energía de las chivas).
Superficies y Fondos: Modos claro cálido (#FFF8F5, #FCF2EB) y modo nocturno profundo (#0F172A, #1E293B) para rutas de luces y miradores.
Tipografía: Plus Jakarta Sans (moderna, geométrica, altamente legible en interfaces complejas).
Bordes y Formas: Bordes redondeados consistentes (rounded-xl / rounded-2xl) con micro-interacciones suaves y sombras sutiles.
Sellos de Confianza: Integración de insignias oficiales (🇨🇴 Valle de Aburrá, Registro Nacional de Turismo RNT 94218 y sello MinCIT / Alcaldía de Medellín).
2. Arquitectura de Navegación y Shell
Navegación Móvil (Bottom Bar fijada de 5 tabs):
Explorar (Home): Feed de experiencias curadas, carruseles temáticos y acceso rápido.
Mapa: Vista geoespacial en tiempo real con pines categorizados, filtros y toggle diurno/nocturno.
Publicar (+): Acceso directo para que guías locales y anfitriones publiquen nuevas experiencias.
Reservas: Billetera digital de tiquetes QR activos y pasados.
Perfil: Preferencias de viaje, datos personales, rol y soporte.
Top Bar (Header): Isotipo de montaña/brújula, buscador rápido, selector de idioma (ES / EN) y notificaciones.
Flujos Modales / Stack: Vistas sin tab bar inferior para procesos focalizados (Login, Registro, Checkout, Filtros Avanzados y Creación de Eventos).
3. Especificación Detallada de Pantallas del Ecosistema
A. Flujo de Entrada, Onboarding y Autenticación
Bienvenida & Splash:
Hero inmersivo del Valle de Aburrá al anochecer con badges de respaldo institucional.
Píldoras de experiencias destacadas (Miradores y Fogatas, Chivas & Tradición, Acceso Inmediato QR).
Acceso con botones: "Comenzar Ahora (Bono +$15.000 COP)", "Ya tengo cuenta • Iniciar Sesión" y "Explorar como invitado".
Iniciar Sesión (Login):
Acceso con Google, Apple o Correo/Celular, soporte biométrico (Face ID / Huella) y recuperación de contraseña.
Crear Cuenta / Registro Gratis:
Selector de rol ("Quiero Explorar" vs. "Ser Guía Local"), validación por WhatsApp para envío de tiquetes QR y términos de turismo seguro.
Onboarding de Preferencias de Aventura:
Selección interactiva de intereses (Miradores, Gastronomía Paisa, Chivas Rumberas, Café, Senderismo Arví, Vida Nocturna) y nivel de exigencia física.
B. Exploración, Búsqueda y Geo-localización
Home Principal (Inicio):
Buscador contextual por fecha, sector (Poblado, Laureles, Centro, San Félix, Arví) y tipo de plan.
Categorías en chips horizontales y secciones destacadas ("Planes para hoy", "Atardeceres con fogata", "Rutas en Chiva").
Resultados de Búsqueda (Lista):
Tarjetas ricas con precio en COP, valoración (estrellas y total de reseñas), duración, cupos disponibles y badges de calidad.
Filtros Avanzados:
Filtros por rango de precio, franja horaria (Mañana, Tarde, Noche bohemia), transporte incluido, accesibilidad y experiencias pet-friendly.
Mapa Interactivo de Experiencias (Modo Diurno):
Mapa del Valle de Aburrá con pines temáticos, clústeres por zona y tarjeta emergente inferior (preview card) con CTA directo.
Mapa Nocturno & Luces de la Ciudad:
Estilo oscuro/satélite destacando los mejores miradores para ver la panorámica nocturna, corredores de alumbrados y rutas seguras.
C. Páginas de Detalle de Experiencias y Tours Insignia
Detalle: Atardecer & Picnic en San Félix / Parque Arví:
Galería fotográfica, itinerario por horas, punto de encuentro MetroCable, qué incluye (chocolate caliente, guía, fogata) y widget de reserva.
Detalle: Ruta de Luces y Chivas Rumberas:
Recorrido nocturno panorámico con música, animación típica y paradas en miradores icónicos.
Detalle: Tour en Chiva Cantinas Históricas, Tango y Fogón Paisa:
Enfoque gastronómico y cultural (+18 años): Salón Málaga, cantinas de Guayaquil, picada montañera en fonda tradicional y terraza tanguera en La 45 de Manrique.
Opciones de boleto (Cantinero Clásico y Mesa de Honor VIP con cata de mistelas y aguardiente).
D. Transacción, Confirmación y Gestión
Checkout y Reserva Final:
Resumen de boletos, desglose de tarifas con impuestos locales, políticas de cancelación flexible y pasarela de pago segura (Wompi, PSE, Tarjetas de Crédito, Nequi/Daviplata).
Confirmación Exitosa & Tiquete Digital QR:
Pase de abordar digital con código QR dinámico listo para escanear en la puerta de la chiva o punto de encuentro, botón de descarga PDF y botón "Añadir a Apple Wallet / Google Wallet".
Crear Evento / Experiencia (Host/Guía):
Asistente por pasos para anfitriones: título, categoría, punto de encuentro en mapa, itinerario, cupos máximos, precio y requisitos.
Mis Reservas & Perfil de Usuario:
Historial de viajes, tiquetes activos con acceso rápido al QR offline, gestión de favoritos y configuración de cuenta.
4. Directrices Técnicas y de Frontend
Tecnologías: HTML5 semántico, Tailwind CSS, iconos vectoriales (Lucide / Material Symbols) y JavaScript nativo para micro-interacciones (carruseles, pestañas, modales, acordeones).
Responsive: Mobile-first óptimo para pantallas de ~390px con escalabilidad fluida hacia tablets y Desktop (layouts de 2 y 3 columnas, sidebars fijos y mapas interactivos split-screen).
Localización & Moneda: Moneda en Pesos Colombianos ($XX.000 COP), lenguaje en español con expresiones locales amigables y respetuosas de la cultura antioqueña.
```