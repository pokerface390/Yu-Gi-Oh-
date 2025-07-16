🃏 <p align="center">Yu-Gi-Oh! Dashboard</p>
<p align="center">✨ Portada del Proyecto</p>
<p align="center"> <img src="https://github.com/user-attachments/assets/7a1e7243-ee8a-4318-86b5-6af9b7779048" alt="Portada Yu-Gi-Oh Dashboard" /> </p>
<p align="center">📌 Breve explicación</p>
<p align="justify"> Este proyecto fue desarrollado con Angular usando configuración <strong>standalone</strong>. Es un <strong>Dashboard interactivo de cartas de Yu-Gi-Oh!</strong> que permite visualizar, filtrar, agregar, modificar, eliminar y ver en detalle las cartas extraídas de una API externa (<code>https://db.ygoprodeck.com/api/</code>), todo desde el frontend. El diseño es responsivo y moderno, utilizando estilos limpios y bien organizados. </p
<p align="center">🔐 Sistema de Login</p>
<p align="center"> <img src="https://github.com/user-attachments/assets/bdec31e4-c097-4200-90ae-928d91105d93" alt="Login" /> </p> <p align="justify"> Antes de acceder al dashboard, los usuarios deben ingresar un nombre de usuario. Este login es sencillo y simulado (sin backend), pero permite personalizar la experiencia al mostrar la foto y nombre del usuario dentro del dashboard. Los datos del usuario se almacenan localmente para su uso inmediato en la interfaz. </p>                                                                                                                                                                   
<p align="center">🧭 Barra superior y perfil</p>
<p align="center"> <img src="https://github.com/user-attachments/assets/ec05af74-99d6-4f2c-bb45-111353b1e163" alt="Barra de usuario" /> </p> <p align="justify"> En la parte superior del dashboard se encuentra el perfil del usuario con nombre y fotografía. Este componente le da un toque personal a la aplicación y está fijo en la parte superior, lo que mejora la experiencia del usuario. </p>
<p align="center">🔍 Funcionalidades destacadas</p>
<p align="center"> <img src="https://github.com/user-attachments/assets/71b7f7e1-6753-474c-b594-6339c84491dd" alt="Tabla de Cartas" /> </p> <p align="justify"> La tabla principal es el núcleo de la aplicación. Muestra las cartas obtenidas desde la API de Yu-Gi-Oh! con una vista ordenada que incluye imagen pequeña, nombre y una columna de acciones. A continuación, se describen las funcionalidades implementadas: </p>
🔎 Filtro en tiempo real por nombre de carta.

➕ Botón Agregar: Añade una carta de prueba localmente (no se comunica con la API).

✏️ Modificar: Simula una edición local con mensaje visual.

🗑️ Eliminar: Elimina la carta de la tabla con confirmación previa.

👁️ Ver más: Abre un modal con imagen grande y descripción detallada.

<p align="justify"> El sistema utiliza mensajes temporales para confirmar las acciones realizadas, mejorando la retroalimentación del usuario. </p>
<p align="center">🪄 Modal descriptivo</p>
<p align="center"> <img src="https://github.com/user-attachments/assets/78812afc-bc89-4e26-bc71-6659a08ddae8" alt="Modal Descripción" /> </p> <p align="justify"> Al hacer clic en "Ver más", se despliega un modal con la imagen ampliada de la carta y su descripción completa. Este modal se puede cerrar fácilmente y permite conocer más detalles sin salir de la aplicación. </p>
<p align="center">📦 Tecnologías utilizadas</p>
<p align="center"> <img src="https://skillicons.dev/icons?i=angular,typescript,html,css" /> </p>
🔺 Angular Standalone Components

🧠 TypeScript

🎨 CSS personalizado

🌐 Consumo de API externa (YGOPRODeck)

<p align="center">🎯 Objetivo del proyecto</p>
<p align="justify"> Desarrollar una aplicación Angular que consuma una API pública, presentando los datos de forma estructurada y funcional. También se buscó reforzar el uso de formularios, ngModel, servicios HTTP, modales, y filtrado en tiempo real. </p>
🌐 API utilizada y justificación
API: https://db.ygoprodeck.com/api/v7/cardinfo.php
Justificación:

✅ Gratuita y de libre acceso.

✅ Bien documentada.

✅ Permite obtener cartas de Yu-Gi-Oh! con imágenes, descripción, estadísticas y más.

✅ Ideal para una app de tipo catálogo con filtros, acciones y vista detallada.

