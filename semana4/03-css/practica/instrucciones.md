## ✍🏻 Práctica en equipo: Agregando estilos con CSS

En esta práctica en equipo, ampliaremos la práctica anterior para agregar estilos CSS.

### 📌 Instrucciones:
Sigue los pasos a continuación para completar la práctica:

1. En el archivo HTML, agrega una referencia al archivo CSS donde colocarás los estilos. Puedes hacerlo utilizando la etiqueta `<link>` en la sección `<head>` de tu documento HTML. Por ejemplo:
    
```html
<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Contenido de tu página -->
</body>
</html>
```

2. Crea un nuevo archivo CSS llamado "styles.css" (o el nombre que hayas elegido en el paso anterior) en la misma ubicación que tu archivo HTML.
3. Ahora puedes comenzar a agregar estilos CSS a tu estructura HTML. Puedes utilizar los selectores CSS para apuntar a los elementos específicos que deseas estilizar. Por ejemplo, para estilizar la sección del "Integrante 1" podrías utilizar el selector #integrante1 que hace referencia al atributo "id" de la sección.

```css
...
#integrante1 {
    background-color: #f1f1f1;
    padding: 20px;
    margin-bottom: 20px;
}
...
```

4. Continúa agregando estilos para los elementos dentro de la sección. Puedes utilizar selectores de descendencia para apuntar a los elementos secundarios y estilizarlos según sea necesario.
5. Repite el proceso para estilizar otros elementos dentro de la sección, como el párrafo `<p>`, la imagen `<img>` y la lista `<ul>`. Puedes utilizar selectores de clase, etiqueta o cualquier otro selector que se ajuste a tus necesidades.
6. Guarda el archivo CSS y actualiza tu navegador web para ver los cambios aplicados.

Recuerda que estos son solo ejemplos básicos y puedes agregar más estilos según tus preferencias y necesidades. Además, asegúrate de ajustar las rutas de los archivos en tu archivo HTML según la estructura de tu proyecto.

### 📌 Actualiza tu repositorio remoto en GitHub

Una vez que hayas terminado de trabajar en tu proyecto, es importante actualizar tu repositorio remoto en GitHub para que todos los cambios estén disponibles para tu equipo. Para ello, sigue los pasos a continuación:

1. Abre la terminal de comandos.
2. Agrega los cambios realizados a tu repositorio local. Para ello, ejecuta el comando `git add .` en la terminal.
3. Crea un nuevo commit con los cambios agregados. Para ello, ejecuta el comando `git commit -m "mensaje"` en la terminal. Reemplaza `mensaje` con un mensaje que describa los cambios realizados.
4. Por último, ejecuta el comando `git push` en la terminal para subir los cambios a tu repositorio remoto en GitHub.
