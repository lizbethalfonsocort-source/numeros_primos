Comprobador de Números Primos Neón 🔢✨

Una aplicación web interactiva de un solo archivo que permite a los usuarios verificar si un número es primo o no. Cuenta con un diseño moderno de temática neón oscuro, animaciones flotantes de fondo y efectos visuales gratificantes según el resultado.

✨ Características

Comprobación Rápida: Utiliza un algoritmo optimizado en JavaScript para verificar rápidamente la primalidad de números enteros.

Diseño Neón Oscuro: Interfaz de usuario atractiva con colores cian brillantes, sombras simulando luces de neón y un fondo oscuro (bg-gray-900).

Fondo Dinámico: Números flotantes animados en el fondo que añaden un toque tecnológico y lúdico.

Feedback Visual Animado:

Si es Primo: La interfaz se ilumina en verde neón y una lluvia de emojis de celebración (🎉, ✨, ⭐) cae por la pantalla.

Si NO es Primo: La interfaz se ilumina en rojo neón y una lluvia de emojis de error (❌, 🔴, 🚫) indica el resultado negativo.

Detalles Explicativos: Proporciona la razón matemática por la cual un número no es primo (ej. "Es divisible por 3" o "Es un número par").

Diseño Responsivo: Construido con Tailwind CSS para adaptarse perfectamente a cualquier tamaño de pantalla (móviles, tablets y computadoras de escritorio).

Todo en Uno: HTML, CSS (Tailwind a través de CDN + estilos personalizados) y JavaScript contenidos en un único archivo index.html.

🚀 Cómo usar

Dado que es una aplicación de un solo archivo, su uso es sumamente sencillo:

Descarga el archivo: Guarda el archivo como index.html.

Abre en tu navegador: Haz doble clic sobre el archivo index.html o arrástralo a tu navegador web favorito (Chrome, Firefox, Safari, Edge, etc.).

Interactúa:

Escribe un número entero en el campo de texto.

Haz clic en el botón "Comprobar Número" o presiona la tecla Enter.

¡Disfruta de las animaciones y descubre si tu número es primo!

🛠️ Tecnologías Utilizadas

HTML5: Estructura de la aplicación.

CSS3 & Tailwind CSS (vía CDN): Estilos, diseño responsivo, sombras de neón y animaciones clave (@keyframes).

JavaScript (Vanilla): Lógica de comprobación de números primos, manipulación del DOM y generación de partículas animadas.

🧠 Algoritmo de Comprobación

El algoritmo implementado en JavaScript está optimizado para evitar iteraciones innecesarias:

Descarta números menores o iguales a 1.

Verifica rápidamente si es 2 o 3.

Descarta todos los múltiplos de 2 y 3.

Itera comprobando divisibilidad empezando desde 5 y avanzando en incrementos de 6 (es decir, comprueba $i$ e $i+2$), deteniéndose al alcanzar la raíz cuadrada del número ingresado.

Esto garantiza un rendimiento excelente incluso con números grandes.

🤝 Contribuciones

Este es un proyecto simple y de código abierto. Si deseas agregar nuevas características, como un historial de comprobaciones, soporte para números extremadamente grandes (BigInt) o más efectos visuales, ¡siéntete libre de bifurcar (fork) el código o modificar tu archivo local!

Desarrollado con ❤️ para explorar la combinación de matemáticas básicas y diseño web interactivo.