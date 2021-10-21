# NetCoreCostosoPizza

Para subir el proyecto:
    git init

    git add .

    git commit -m "first commit"

    git remote add origin https://github.com/NOMBRE_USUARIO/NOMBRE_PROYECTO.git

    git push -u origin master
    
La url del [curso](https://docs.microsoft.com/es-es/learn/modules/build-web-api-aspnet-core/)

Las acciones son:
- GET. Devuelve un IActionResult con el resultado de la buúsqueda.
- POST. Devuelve CreatedAtAction(201) si es correcto. El error 400 está implícito
- PUT. Devuelve BadRequest(400) si la petición es incorrecta, NotFound(404) si no existe y NoContent si es correcta
- DELETE. Devuelve NotFound(404) si no existe   y NoContent si es correcta
