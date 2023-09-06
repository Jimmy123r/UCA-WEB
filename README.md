# UCA-WEB

Ejemplo: codigo responsive CSS 

```css
/* Establecemos un tamaño de fuente base para el cuerpo de la página */
body {
  font-size: 16px;
}

/* Estilos para dispositivos móviles (hasta 767px) */
@media (max-width: 767px) {
  /* Agrega estilos específicos para dispositivos móviles aquí */

  /* Por ejemplo, podrías cambiar el tamaño de fuente para dispositivos móviles */
  body {
    font-size: 14px;
  }
}

/* Estilos para tabletas (768px - 1023px) */
@media (min-width: 768px) and (max-width: 1023px) {
  /* Agrega estilos específicos para tabletas aquí */
}

/* Estilos para pantallas más grandes (a partir de 1024px) */
@media (min-width: 1024px) {
  /* Agrega estilos específicos para pantallas más grandes aquí */
}

/* Estilos generales para todos los tamaños de pantalla */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
  display: flex; /* Usamos flexbox para un diseño flexible */
  flex-wrap: wrap; /* Los elementos se envuelven en pantallas pequeñas */
  justify-content: space-between; /* Espaciado uniforme entre elementos */
}

.header {
  background-color: #333;
  color: #fff;
  padding: 10px;
  text-align: center;
}

.nav {
  background-color: #555;
  color: #fff;
  padding: 10px;
}

.main-content {
  flex: 2; /* El contenido principal ocupa 2/3 del ancho en pantallas grandes */
  padding: 20px;
}

.sidebar {
  flex: 1; /* La barra lateral ocupa 1/3 del ancho en pantallas grandes */
  padding: 20px;
}

.footer {
  background-color: #333;
  color: #fff;
  padding: 10px;
  text-align: center;
}
```


1. Establecemos un tamaño de fuente base para el cuerpo de la página.

2. Luego, utilizamos media queries para definir estilos específicos para dispositivos móviles, tabletas y pantallas más grandes. En cada media query, puedes agregar estilos personalizados según sea necesario.

3. Después, establecemos estilos generales que se aplicarán a todos los tamaños de pantalla, como la fuente y el margen y relleno del cuerpo.

4. La clase `.container` se utiliza para el diseño principal de la página, con flexbox. En pantallas pequeñas, los elementos se envuelven y ocupan todo el ancho disponible.

5. Las clases `.header`, `.nav`, `.main-content`, `.sidebar` y `.footer` contienen estilos específicos para esas secciones de la página.


